

********************Metodología para crear un proyecto nuevo con nodjs y npm********************

0. Crear un repositorio remoto y uno local (conectarlos localmente).

1. Instalar nodejs: sudo apt install nodejs (verificar: node -v).

2. Instalar npm: sudo apt install npm (verificar: npm -v).

3. Crear una carpeta donde guardar el proyecto.

4. Abrir una terminal y ejecutar: npm init (diligenciar la información del proyecto).

5. Definir el servidor web (lite-server para dev. instalar con npm install lite-server --save-dev) (documentación: https://www.npmjs.com/package/lite-server).

6. Agregar un archivo .gitignore para ignorar node_modules, debido a que contiene los archivos de las dependencias del proyecto. 

7. En el archivo "package.json" en el ámbito de "scripts", agregar el comando  "dev": "lite-server", se verá así: 

"scripts": {
   "test": "echo \"Error: no test specified\" && exit 1",
    "dev": "lite-server"
  },
  
8. Para validar que todo bien ejecutar: npm run dev 
   Debería abrir una página del navegador con un error en el GET (normal... no hemos hecho nada)
   Cerrar el servidor. Ir a la terminal y presonar ctrl+c (esto hace un sigint y cierra el servidor.

9. Empezar a desarrollar. 

