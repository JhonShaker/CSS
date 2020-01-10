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
