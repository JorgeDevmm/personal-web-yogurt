# Plantilla inicial proyectos con gulp y sass 🚀

---

- Cambiar el nombre, descripción del proyecto de acuerdo a su preferencia
- Instalar npm install, para descargar la carpeta de node_modules, que son necesarias las dependencias para el uso del gulpfile.js

- Ejecutamos gulp para que realiza todo las tareas detalladas del gulpfile.js

* En el archivo index, ya viene agregado una fuente por defecto, modficar a elección del proyecto, el archivo generado build/css/app.css previmente al ejecutar gulp ya viene generado los codigos css, se puede generar nuevos codigos, de acuerdo al proyecto por medio de la carpet src/ \*

* Agregar .gitignore antes de iniciar el proyecto para solo guardar los cambios de la carpeta generada build y el archivo index

* referencias a omitir en el .gitignore para poder cargar en git hub y desplegar en **netlify**

# rerencias de node_modules

node_modules/

#referencia de carpeta archivo sass(opcional)
src/

# referencia de archivos visualcode

.vscode/

# referentes a sass(temporales se crea al volver a copilar)

.sass-cache/ #_.css.map
_.sass.map
\*.scss.map

#Archivos de configuración de Gulp(opcional para compilar)

gulpfile.js

# Archivos de dependencias de Node.js

package-lock.json
