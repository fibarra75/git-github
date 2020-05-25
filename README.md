# Uso comando git para manejar versiones de los archivos y subir version a github
## Video de referencia
https://www.youtube.com/watch?v=HiXLkL42tMU\

Inicializar git en el proyecto\
git init\
Agrega el archivo app.js al staging area\
git add app.js\
Ve el estado de los archivos en la carpeta/directorio\
git status\
Agrega todo los archivos de la carpeta al staging area\
git .\
git status\
Identificarse en git, quien soy\
git config --global user.email "skulka@gmail.com"\
git config --global user.name "Shulka"\
Crear nuestro primer punto de partida (snapshot). Pasa los archivos al repository\
git commit -m "Version inicial"\
Ver log de commit\
git log\
Vuelve el archivo a la versión que esta en el area de staging\
git checkout -- index.html\
Muestra la diferencia en el archivo\
git diff index.html\
Agregar archivos nuevos y modificados al area de staging\
git add .\
git commit -m "Se modifico el index.html y README"\
Para ignorar archivos y/o carpetas en el traspado a staging area, se utiliza el archivo .gitigonore\
git commit -m "he agragado un .gitignore"\
Lista la ramas/versiones de la aplicacion/software\
git branch\
Nueva version o rama de la aplicacion\
git branch login\
Se cambia a la rama login\
git checkout login\
git add .\
git commit -m "Nueva rama con login"\
git log\
git branch\
Vuelve a la rama master\
git checkout master
## Enlazar con repositorio en github\
git remote add origin https://github.com/fibarra75/git-github.git \
Sube la version de repository al github\
git push -u origin master