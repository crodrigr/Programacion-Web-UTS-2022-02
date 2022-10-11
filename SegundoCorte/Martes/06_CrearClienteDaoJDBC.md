# Crear la clase clienteDaoJDBC.

ESta clase se define las consultas que se van hacer en relación a la clase cliente. 


## 1. Crear la clase ClienteDaoJDBC.java

![image](https://user-images.githubusercontent.com/31961588/193950987-6baec48a-6541-4d70-b0fa-98da463e643e.png)

## 2. Definimos las constantes que tiene las consultas sql

![image](https://user-images.githubusercontent.com/31961588/193952632-4e6a7e2d-3a64-4f54-8394-82dd4c47a302.png)

## 3. Método getAll que trae todos los clientes


![image](https://user-images.githubusercontent.com/31961588/193962938-7fde9f2a-1c15-4530-a35f-cc6872800fc0.png)



## 4. Creamos cliente.jsp dentro  WEB-PAGES

![image](https://user-images.githubusercontent.com/31961588/193962514-2b97cc80-88f5-485f-a9cf-5ff4a4405655.png)

## 4. En el método doGet del Servlet se realiza la consulta de todos los clientes que se pasa a clientes.jsp

![image](https://user-images.githubusercontent.com/31961588/193958170-069e8290-ca77-4f2a-87af-3277a0cf7650.png)

## 4. Add dependencia en el pom.xml

![image](https://user-images.githubusercontent.com/31961588/193962735-1fad8b87-57ee-4954-aa85-cd44241d6c59.png)


## 5. Add taglig para usar un foreach para recorrer el listado de clientes

![image](https://user-images.githubusercontent.com/31961588/193957898-671352b2-fc9b-4b70-b405-8bef212f84b5.png)

 -----------------------------------------------------------------------------------------------------------

##  Método encontrar

![image](https://user-images.githubusercontent.com/31961588/184731214-2a28b749-ea1a-4070-84e1-a266cba3cc99.png)

## Método insertar

![image](https://user-images.githubusercontent.com/31961588/184731564-4fb84d81-de07-4b37-bf9f-65022c42cbdf.png)

##  Método actualizar

![image](https://user-images.githubusercontent.com/31961588/184731845-3c061080-9f9d-48e5-bdb3-51d1f7a71e6c.png)


## 5. Método eliminar

![image](https://user-images.githubusercontent.com/31961588/184731923-5f1b19b6-be49-4ff6-b019-f06568c069db.png)

