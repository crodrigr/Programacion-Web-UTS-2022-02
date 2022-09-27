# Crear capas del proyecto y el servlet controlador

En este apartado se va crear las capas del proyecto:

- datos
- dominio
- web

**Datos:** clases que se relacionan con la base de datos.

**Dominio:** clases con reglas de negocio de nuestra aplicación.

**Web:** clases controladores. 

**Web-Pages:** interfaces web en archivos jsp 

## 1. Crear los paquetes: datos, dominio y web

### 4.1

![image](https://user-images.githubusercontent.com/31961588/192115619-27295d3a-ec1e-4099-9bcf-032730fc84a1.png)

![image](https://user-images.githubusercontent.com/31961588/192115640-d8eb0823-d957-486f-ab04-d460d5767d78.png)

![image](https://user-images.githubusercontent.com/31961588/192115677-4bf2f399-30ba-4aa1-aeae-69f4780703ae.png)

### 4.2 Arquitectura

![image](https://user-images.githubusercontent.com/31961588/192116045-b94c41c7-e77b-492d-be12-87d5e12184ac.png)

# 5 Crear el servlet controlador de saldos 


![image](https://user-images.githubusercontent.com/31961588/192116116-285c0f52-4f84-4b8d-9f8c-f20f047217d2.png)

![image](https://user-images.githubusercontent.com/31961588/192116133-c0212590-13b1-4a5e-9a94-dc27873f60a5.png)

### 5.1 Probar el servlet

Se debe eliminar el index.html y crear un index.jsp y colocar la siguiente para llamar al servlet controlador

**Nota**: el index.jsp debe estar dentro del Web-Pages y se debe invocar el serverlet con el meta http-equv

![image](https://user-images.githubusercontent.com/31961588/192117669-8cfc5a16-e7c1-42f7-b84a-a607fb92f3e0.png)


```Html
<meta http-equiv="refresh" content="0;url=${pageContext.request.contextPath}/SerlvetConroladorSaldos">
```



