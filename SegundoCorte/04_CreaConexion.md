# Crear la clase conexion. 

En esta clase se define todos los parametros de conexion y se establece las conexiones que va tener la aplicación usando un poolling de conexiones. Para el polling de conexion usamos la dependencia **dbcp2**

## Paso previo se debe colocar la depedencia de dbcp2 en el pom.xml. 

![image](https://user-images.githubusercontent.com/31961588/193424971-ce172536-a598-425e-9955-ea2546b8b04d.png)

```Xml
<dependency>
            <groupId>org.apache.commons</groupId>
            <artifactId>commons-dbcp2</artifactId>
            <version>2.9.0</version>
</dependency>
```

## 1. Crear clase conexion dentro el paquete datos. 

### 1.1
![image](https://user-images.githubusercontent.com/31961588/193424740-40e366e0-b9c4-4d96-8265-487102e12f83.png)

### 1.2. Se define los atributos de conexión a la base de datos como atributos de clase(static) y constantes(final)

![image](https://user-images.githubusercontent.com/31961588/193425247-37e16fe0-388a-4f70-8b62-0d186517dc92.png)

