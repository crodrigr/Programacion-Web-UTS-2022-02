# Taller listado de personas

![image](https://user-images.githubusercontent.com/31961588/200455669-ff86b819-6edf-4afd-bc22-13303bc11994.png)

# Configuración inicial 

![image](https://user-images.githubusercontent.com/31961588/200456636-8d648f23-7a56-47df-ab84-0779a7282039.png)


### 1. index.html

![image](https://user-images.githubusercontent.com/31961588/200456713-b09427de-bd25-4708-a4a2-5a4131024b8f.png)


**Codigo**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Listado de Personas</title>
    <link href="css/estilos.css" rel="stylesheet"/>
</head>
<body>
    <div class='contenedor' id='cabecero'>
        <h1>Listado de Personas</h1>
    </div>   
    <script src='js/persona.js'></script> 
    <script src='js/app.js'></script> 
</body>
</html>
```
## 2. app.sj y persona.js

![image](https://user-images.githubusercontent.com/31961588/200456857-3ce4710a-0b55-4592-a297-f72db0c1bd05.png)

![image](https://user-images.githubusercontent.com/31961588/200456908-afff043b-e923-4147-8647-a0bee550a137.png)

## 3. css

![image](https://user-images.githubusercontent.com/31961588/200457078-a118097a-0b98-4380-90bd-44dfac8a9a83.png)

```css
html {
    background-color: #2196f3;
    min-height: 1000px;
    font-family: "helvetica neue";
    background: url(fondo.png), #2196f3;
    background: url(fondo.png),
      -webkit-gradient(linear, right top, left top, from(#2196f3), to(#009688));
    background: url(fondo.png),
      linear-gradient(to left, #2196f3, #009688);
  }
  
  h1 {
    color: #fff;
    padding: 10px;
  }
  
  .contenedor {
    max-width: 400px;
    margin: 50px auto;
    background: white;
    border-radius: 5px;
    box-shadow: 5px 5px 15px -5px rgba(0, 0, 0, 0.3);
  }
  
  #cabecero {
    background-color: #3f51b5;
    text-align: center;
  }
  
  .elemento {
    min-height: 70px;
    display: flex;
    align-items: center;
    border-bottom: 1px solid #f1f1f1;
  }
  
  .elemento:last-child {
    border-bottom: 0;
  }
  
  input[type="checkbox"] {
    margin: 20px;
  }
  
  p {
    margin: 0;
    padding: 20px;
    font-size: 20px;
    font-weight: 200;
    color: #00204a;
  }
  
  form {
    text-align: center;
    margin-left: 20px;
  }
  
  button {
    min-height: 50px;
    width: 50px;
    border-radius: 50%;
    border-color: transparent;
    background-color: #3f51b5;
    color: #fff;
    font-size: 30px;
    padding-bottom: 6px;
    border-width: 0;
  }
  
  input[type="text"] {
    text-align: center;
    height: 60px;
    top: 10px;
    border: none;
    background: transparent;
    font-weight: 200;
    width: 40%;
  }
  
  input[type="text"]:focus {
    outline: none;
    box-shadow: inset 0 -3px 0 0 #3f51b5;
  }
  
  ::placeholder {
    color: grey;
    opacity: 1;
  }
```
