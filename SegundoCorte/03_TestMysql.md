# Crear la base de datos y hacer test

## 1. Ingresar a la bd con workbench

![image](https://user-images.githubusercontent.com/31961588/192118542-1fa1a037-ef85-480b-a78e-b63ff18547d8.png)

### 1.1 Crear schema

![image](https://user-images.githubusercontent.com/31961588/192118567-9ea37c01-e91d-4429-b919-78fc032f2473.png)

### 1.2

![image](https://user-images.githubusercontent.com/31961588/192118585-6f5d9181-8350-412a-9fdd-915ff28935cc.png)

### 1.3

![image](https://user-images.githubusercontent.com/31961588/192118617-79e2d1ff-e0d5-42e3-bd8f-15624b89e2a2.png)


### 1.4

![image](https://user-images.githubusercontent.com/31961588/192118637-a56b101d-a944-4d57-8b95-5df71f87ccd0.png)

### 1.5 Crear tabla cliente con sus campos

![image](https://user-images.githubusercontent.com/31961588/192118681-90bfe70f-eb7c-4c1e-9e24-df4828c81fcf.png)

**script create table**
```Sql
CREATE TABLE `db_saldos`.`cliente` (
  `id_cliente` INT NOT NULL AUTO_INCREMENT,
  `nombres` VARCHAR(60) NULL,
  `apellidos` VARCHAR(60) NULL,
  `email` VARCHAR(45) NULL,
  `telefono` VARCHAR(45) NULL,
  `saldo` DOUBLE NULL,
  PRIMARY KEY (`id_cliente`));
  ```

### 1.6 Insertar datos en la tabla cliente

![image](https://user-images.githubusercontent.com/31961588/192118766-a67baec1-66ab-4ca8-ae8a-fbd73dce1f7c.png)

**script insert cliente**
```Sql
INSERT INTO `db_saldos`.`cliente` (`nombres`, `apellidos`, `email`, `telefono`, `saldo`) VALUES ('Camilo Ernesto', 'Rodriguez Moreno', 'crodrigr@gmail.com', '323444', '1000');
INSERT INTO `db_saldos`.`cliente` (`nombres`, `apellidos`, `email`, `telefono`, `saldo`) VALUES ('Maria Celilna', 'Torres Serrano', 'mtorres@gmail.com', '38858585', '2000');
INSERT INTO `db_saldos`.`cliente` (`nombres`, `apellidos`, `email`, `telefono`, `saldo`) VALUES ('Juan Carlos', 'Camargo Perez', 'jcamargo@gmail.com', '48484', '3000');
INSERT INTO `db_saldos`.`cliente` (`nombres`, `apellidos`, `email`, `telefono`, `saldo`) VALUES ('Diego Fernando', 'Rangel  Guzman', 'drangel@gmail.com', '48848448', '4000');
```

## 2 Tes de conexion. 

## 2.1 Descargar el driver de conexion de mysql para tomcat

![image](https://user-images.githubusercontent.com/31961588/192119260-32ccb644-3b40-4448-83ab-45b7c931aa21.png)

## 2.2 

![image](https://user-images.githubusercontent.com/31961588/192119290-a5712aac-0ffe-4ac6-83e2-74d36e5bceac.png)

## 2.3 Descomprimir y copiar el .jar para colocarlo en lib del tomcat

![image](https://user-images.githubusercontent.com/31961588/192119323-2612be67-7181-4b05-a68f-59348aa65ab5.png)

#### 2.3.1 copiar y reniciar el servicio de tomcat

![image](https://user-images.githubusercontent.com/31961588/192119353-20b43ff9-c70c-4715-8243-822276994d51.png)



