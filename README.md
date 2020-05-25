https://www.youtube.com/watch?v=HiXLkL42tMU

git init #Incializar git en el proyecto
git add app.js #Agrega el archivo app.js al staging area
git status #Ve el estado de los archivos en la carpeta/directorio
git * #Agrega todo los archivos de la carpeta al staging area
git status
#Identificarse en git, quien soy
git config --global user.email "skulka@gmail.com"
git config --global user.name "Shulka"
#Crear nuestro primer punto de partido -snapshot-. Pasa los archivos al repository
git commit -m "Version inicial"
git log
git checkout -- index.html #Vuelve el archivo a la versión que esta en el area de staging
git diff index.html #Muestra la diferencia en el archivo
git add . #Agregar archivos nuevos y modificados al area de staging
git commit -m "Se modifico el index.html y README"
#Para ignorar archivos y/o carpetas en el traspado a staging area, se utiliza el archivo .gitigonore
git commit -m "he agragado un .gitignore"
git branch #Lista la version de la aplicacion/software
git branch login #Nueva version o rama de la aplicacion
git checkout login #Se cambia a la rama login
git add . 
git commit -m "Nueva rama con login"
git log
git branch
git checkout master
#Enlazar con repositorio en github
git remote add origin https://github.com/fibarra75/git-github.git
git push -u origin master #sube version directory a remoto