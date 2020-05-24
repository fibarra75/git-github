https://www.youtube.com/watch?v=HiXLkL42tMU

git init #Incializar git en el proyecto
git add app.js #Agrega el archivo app.js al staging area
git status #Ve el estado de los archivos en la carpeta/directorio
git * #Agrega todo los archivos de la carpeta al staging area
git status
#Identificarse en git, quien soy
git config --global user.email "fibarra75.m@gmail.com"
git config --global user.name "Fernando Ibarra M"
#Crear nuestro primer punto de partido -snapshot-. Pasa los archivos al repository
git commit -m "Version inicial"
git log
git checkout -- index.html #Vuelve el archivo a la versión que esta en el area de staging
git diff index.html #Muestra la diferencia en el archivo
git add * #Agregar archivos nuevos y modificados al area de staging

