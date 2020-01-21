Hoja de estilos CSS se agrega en el area <head>
<link rel="stylesheet" type="text/css" href="css_1.css">

(Datos archivo css_1.css)
Asignacion de atributo a parrafos <p>
p{
	color:blue;
}

Asignacion de atributos a clase especifica "important"
En archivo HTML <p id="nombre"></p>
#important{
	font-size:36px;
}

Asignacion de atributos a clases con ID "info"
En archivo HTML <p class="nombre"></p>
.info{
	background-color: green;
	border:1px solid black;
}

Orden de prioridades en pesos CSS
#ID / .CLASS / ELEMENTO
ID: #id
CLASS: .class
EELEMENTO: <p>, <h1>, <table>, <a>, etc

Etiqueta <span></span> 
Para definir atributos a un determinado elemento, ejemplo:
HTML:
<h1><span>Hola mundo </span>he llegado</h1>
CSS:
h1 span{
    color: blue;
    font-size: 10px;
}

Especificación de CSS ofrece 6 valores de posición, los 4 más importantes son: static (estático), relative (relativo), absolute (absoluto y fixed (fijo)).

Funcion para centrar elemento:
#center-me{
  background: red;
  height: 100px;
  width: 100px; 
  margin: auto;
  position: absolute;
  left: 0;
  bottom: 0;
  top: 0;
  right: 0;
}

#center-me{
  background: red;
  height: 100px;
  width: 100px; 
  margin: 0 auto;
}

Reset de CSS para Compatibilidad:
(Basico)
* {
	padding: 0;
	margin: 0;
} 

(Universal)
* {
	vertical-align: baseline;
	font-weight: inherit;
	font-family: inherit;
	font-style: inherit;
	font-size: 100%;
	border: 0 none;
	outline: 0;
	padding: 0;
	margin: 0;
}

@media only screen and (max-width: 480px){
     /* we will set these stylings only if the device is a screen with a width of 480px or less */
     .navbtn {
         background-color: yellow;
     }
}

<div class="col sm-0 med-1">
   <h5>Did you know?</h5>
   <p>If you could fold a piece of paper 42 times, it would be tall enough to reach the moon.</p>
</div>

@media only screen and (max-width: 480px){
    .sm-0 {
        /* we will not display anything with the class .sm-0 if the screen's width is less than 480px */
        display: none;
     }
}
@media only screen and (min-width: 481px){
    .med-1 {
        /* anything with the class .med-1 will get 25% of the available width if the screen's width is greater than 480px */
        width: 25%;
    }
}

.navbtn{
    width: 200px;
    height: 150px;
}

@media only screen and (max-width: 480px){
    .navbtn{
        background-color: yellow;
        display: block;
    }
}

@media only screen and (min-width: 481px){
    .navbtn{
        background-color: blue;
        display: block;
    }
}

@media only screen and (min-width: 1024px){
    .navbtn{
        background-color: red;
    }
}

ESTRUCTURA BASICA:

/*@media only screen and (max-width: 480px){

}

@media only screen and (min-width: 481px){

}

@media only screen and (min-width: 1024px){

}

*/
