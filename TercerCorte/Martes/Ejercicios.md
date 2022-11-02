# Ejericios de Calculadora

**Index.html**

```Html
<!DOCTYPE html>
<html>
    <head>
        <title>Taller en JavaScript</title>
    <script src="app.js"> </script>
    </head>
    <body>
        <h1>Calculadora</h1>
        <label>Dato 1 </label>
        <input type="text" id="dato1">
        <labe>Dato 2</labe>
        <input type="text" id="dato2">
        <button onclick="sumar()">Sumar</button>
        <p id="resultado"></p>
    </body>
</html>
```

**app.js**

```JavaScript


let sumar=()=>{
   const dato1=document.getElementById("dato1").value;
   const dato2=document.getElementById("dato2").value;
   let rta=Number(dato1)+Number(dato2);
   document.getElementById("resultado").innerHTML=rta;
   console.log(dato1);   

}
```
