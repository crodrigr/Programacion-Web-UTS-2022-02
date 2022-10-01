# Crear la clase conexion. 

En esta clase se define todos los parametros de conexion y se establece las conexiones que va tener la aplicación usando un poolling de conexiones. Para el polling de conexion usamos la dependencia **dbcp2**

![image](https://user-images.githubusercontent.com/31961588/192671209-8bb5e3d4-d98f-498f-98b5-8d160e74bebf.png)

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

![image](https://user-images.githubusercontent.com/31961588/193425320-acc643b6-e10b-499a-8597-85991b1aebb9.png)

### 1.3 Se define el obejto dataSource que solo se instancia una sola vez 

![image](https://user-images.githubusercontent.com/31961588/193425981-1a7d685d-c09d-415d-b8da-b01d5e3943dc.png)
