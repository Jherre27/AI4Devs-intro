

Chatbot IA: ChatGPT


Primer prompt:
Quiero que seas un desarrollador de paginas web, con 20 años de experiencia y bastante versátil en diferentes áreas de la profesión.
Entendiendo lo anterior, tienes una nueva tarea, esta consiste en desarrollar una pagina web donde se invierta el orden de una cadena de texto.
Ejemplo: si introduzco "Gato Albino" devuelve "oniblA otaG".
El proyecto debe de realizarse en dos archivos:

Index.html
html
Copiar
Editar
<!DOCTYPE html>  
<html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Reverse String</title>    
</head>  
<body>  
<script src="script.js"></script>  
</body>  
</html>  
Debes de crear la estructura del frontend partiendo del código anterior. Ten en cuenta que el diseño debe ser minimalista y llamativo. Además, este debe de tener capacidad para:
a. El botón debe aparecer cuando haya texto suficiente, más de 3 letras.
b. Que te dé la cadena en tiempo real, que no dependa del botón.
2. script.js
En este se debe de construir la lógica necesaria con JavaScript para ejecutar lo requerido en Index.html.
Si tienes dudas o sugerencias por favor házmelo saber preguntándomelo.

Segundo prompt:
Muy bien!, excelente trabajo, solo algo más.
Noto que el botón no hace nada. Pongámosle una función. Su función será invertir el texto ingresado.
Ejemplo: Si el usuario ingresa "Hola", en la otra casilla se muestra "aloH", pero al dar clic al botón, el texto se debe de resaltar.
Si nuevamente hay clic después de resaltar el texto, el texto debe de invertir nuevamente y también resaltado.
Ejemplo: "aloH" al dar clic entregará "Hola".

Tercer prompt:
Bien, ahora debes acondicionar la funcionalidad del clic del botón, cuando yo presione por primera vez el botón, este solo debe poner en negrita el texto invertido, cuando lo presione por segunda vez, debe funcionar para lo que fue programado anteriormente.

Cuarto prompt:
Excelente, muy buen trabajo, adiciónale al botón que después de revertir el texto, al dar clic nuevamente, el texto invertido se resalta en negrita.

Quinto prompt:
Primer clic: Pone el texto en negrita.
Segundo clic: Invierte el texto y quita la negrita.
Haz que el botón solo tenga estos dos estados después de aparecer.