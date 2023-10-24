# frond2

primero verificamos las version de npm y node
despues creamos una carpteta ya sea en el escritorio o documemtos 
despues en la misma consola que abrimos las terminal para verificar las versiones hacemos el siguiente codigo :

npx create-react-app "le asignamos un nombre a la carpeta" proyect_2

esperamos que se descarguen los paquetes y dependencias
depsues para poder ejecutar el proyecto tenemos de darle:

cd y el nombre que se le puso a la carpeta donde de guardaron los paquetes en este caso seria proyect_2:

"cd proyect"

despues si se podra ejecutar con el comando 
npm start


enlace para plantillas
https://adminlte.io/
https://adminlte.io/themes/v3/index2.html

para verificar la instalacion de estas platillas ver el package-jso 

copiar la carpeta plugins , y dist de admin-lte que se encuentra en node modules

sirve para la navegar entre paginas:
npm install react-router-dom 
confirmar si esta instalado en package.json (Linea 12)

despues vamos a app.js para crear importaciones para que se pueda navegar entre paginas con las rutas 
import React, {Fragment} from 'react';
import {BrowserRouter as Router, Route, Routes} from 'react-router-dom';

agregar un archivo llamado login.js a la carpeta paginas


seleccioanr el codigo de login.js dentro del return y darle click derecho en convert html to jsx

en login.js se cambian las (a) por link y href por to  


proxima clase investigar:

las appy falsas para que siven como se intregran al chrome como se intregran a la modulos para que sirven
