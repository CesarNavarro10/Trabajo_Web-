# Trabajo_Web<!DOCTYPE html>
<html>       
   <meta charset="iso-8559-1"/>
   <meta charset="UTF-8"/> 
  <body> 
     
     <form action="Estructuras.php" method="post">   
         <h1 align="center" style="color: orange"> En este ejercicio de Práctica tenemos 2 numeros.</h1>
         <h1 align="center" style="color: orange"> El Número 1 tiene un Valor de 1000</h1>
         <h1 align="center" style="color: orange"> El Número 2 tiene un Valor de 100</h1>
        
         <label align="center" for="Opciones"> <h3  style="color:#4682B4">Selecciona que Operación quieres realizar: </h3></label>   
         <div style="text-align:center;">
            <select name="opcion">
              <option value="suma">Suma</option>
              <option value="resta">Resta</option>
              <option value="multiplicacion">Multiplicación</option>
              <option value="division">División</option>
           
            </select>
            <br><br>
            <input type="submit" >
         </div>
      </form>

     

</body>
</html>
