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
