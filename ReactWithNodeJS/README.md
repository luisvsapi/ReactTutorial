# ReactTutorial - StandAlone Part
Este subproyecto es para recordar como usar react solito sin usar algun tipo de framework aparte de NodeJS que actua como servidor para servir las paginas

React al ser una libreria es necesario importar la libreria obviamente, en este caso opte por usar dos paquetes de npm:
* react (Core de React)
* react-dom (Manipulacion deL DOM para integrar, porque igual necesita un elemento a donde fijarse)

# Compilación
Al usar *npm run build* se genera el main.js porque el webpack realiza la configuración para el deployment

# TailWindCss para exportar tu css
npx tailwindcss -i ./assets/styles/main.css -o ./assets/styles/mainOut.css --watch 
