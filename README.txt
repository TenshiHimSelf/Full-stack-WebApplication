"""================================================================================================
Institute....: Universidad Técnica Nacional Costa Rica
Headquarters.: Pacifico.
Career.......: IT from home
Period.......: 2024
Document.....: TenshiHimSelf/Full-stack-WebApplication
Goals........: Full stack Web proyects and APIs integrations
Professor....: My Own
Student......: Ricardo Contreras
--Es mas bien una guia la cual apunto notas, no tiene nada en especial
Cabe recalcar que solo son mis pequeños proyectos personales lo que 
voy a estar subiendo aqui.
================================================================================================"""


UI Desing = Este es mi fuerte, es crear tu diceños y pasarlos a codigo

Back-end tambien se encarga de hacer el codigo mas eficiente, pero tambien
tiene que comprobar que el codigo sea mas seguro; Usualmente ellos se enfocan 
en crear APIs para que el Front-end pueda usar

comando html:5 automaticamente crea todo el cuerpo

Si en HTML tengo algun heading "h1...6", por ley, debo de dividirlo con un <section>

Usar imagenes formato SVG, estas imangenes no se distorcionan a la hora de redimecionarlas
paginas para iconos SVG: 
https://tablericons.com/ 

Para crear un formulario, se debe de usar la biñeta "form" la cual, para dar indicaciones al usuario
se debe de usar la viñeta "Fieldset" acompañada de "legend" Esta ultima, al igual que un mapa, es para dar
indicacions al Usario final

<link rel="preload" href="css/styles.css" as="style">
Este codigo es para hacer que la pagina cargue mas fluida

HTML Semantico

En la hoja de CSS, los selectores con ":" no estan en el codigo HTML, solo existen en el documento de CSS, Es como incializar varianles en PseInt.. en ella puedes crer variables la cual pueden almacenar cosas

:root {
  --colorBLANCO :#ffffff;
}

En ese ejemplo, en la variable "colorBLANCO" se almaceno el color blanco en Hexadecimal
ellas se llaman de la misma manera..

.titulo {
  text-align: center;
  font-size: 3.8rem;
  :color var(--primario);
}

en ese ejemplo, le estoy poniendo a todas las clases "titulo" en color que fue almacenado en la variable "primario"

PARA llamar esos archivos, se tiene que poner de la siguiente manera " var(--nombre de la variable)

En ellas pueden ser almacenadas TODO tipo de cosas.. al igual que cualquer varianle de los programas de programacion.

NOTA IMPORTANTE:
Es recomendable tener las librerias cargadas siempre, tambien las fuentes, es lo mas recomendado
lo ultimo simpre es cargar la hora de estilos

Paginas para agarrar font gratis:

https://fonts.google.com/?preview.text=Ricardo%20Contreras%20Front-End%20Developer

normalize css es un "scrip" la cual ayuda a que nuestra pagina se vea "igual" en los distintos navegadores.
Link:

https://csstools.github.io/normalize.css/


<nav class="navegacion-principal contenedor">
En esa linea de codigo, se puede ver que se tiene 2 clases, una es "navegacion-principal" y "contenedor", con solo un espacio en la villetas, se puede meter mas de una clases
Ejemplo:
<a class="a b c">

en ese ejemplo, se pueden ver las clases "a" "b" "c"

la etiqueta "margin" funciona respetando este orden:
top - right - bottom - left
Ejemplo:

  width: 120rem;
  margin-top: 0px;
  margin-right: auto;
  margin-bottom: 0px;
  margin-left: auto;

  margin: 0 auto 0 auto;

  estos 2 funcionan exactamente iguales