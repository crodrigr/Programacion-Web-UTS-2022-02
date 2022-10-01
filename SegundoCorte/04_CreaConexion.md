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


![image](https://user-images.githubusercontent.com/31961588/193424740-40e366e0-b9c4-4d96-8265-487102e12f83.png)
