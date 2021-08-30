<!DOCTYPE html>
<html>
   <body>
<h2>Ingresar datos desde teclado</h2>
<p id = "demo"></p>
<script>
  var signo = "piscis";
  while  (signo != "capricornio") {
     signo = prompt("¿Cuál es tu signo?")  ;
     if (signo.toLowerCase() == "capricornio" ) {
            alert("Yo también soy de Capricornio") 
        }  else {
            alert("Mi signo sodiacal es otro") 
        }
   }     
document.getElementById("demo").innerHTML = "El signo es: " + signo;
</script>
  </body>
</html>
