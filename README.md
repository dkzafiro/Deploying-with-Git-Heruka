# Deploying-with-Git-Heruka
Luego de estar en la carpeta SRC del proyecto
en consola CMD
- Archivos necesarios
# requirements.txt /pip freeze > ../../src/requirements
# runtime.txt / python-3.7.6
# Procfile / web gunicorn index:app
Instalar gunicorn en el entorno virtual
# pip install gunicorn
------------------------------------------
# git init // inicia git en nuestro proyecto
# git status // estado de los files
# git add . // para agregar todos los files
# git commit -m "nombre del commit" // para guardar commit
# heroku create (nombre de proyecto en heruka) sin parentesis
# heroku git:remote (nombre de proyecto en heruka) sin parentesis //enlaza el proyecto de git con heruka
# git push heroku master // sube el proyecto a heruka
# heruka open //abre el proyecto en navegador web ya desplegado

Para agregar a GitHub
# git remote add origin (ruta del repositorio de GitHub) sin parentesis
# git push -u origin master // para subir a GitHub
