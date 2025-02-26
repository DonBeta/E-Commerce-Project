# E-Commerce-Project

Primeros Pasos: Clonando el repositorio desde GitHub en VS Code para poder trabajar local tambien y que puedan sincronizarse todos los cambios.

probando la sincronizacion, via vs - GitHub, GitHub - vs

instalando Node.js (LTS)
Instalando Python

instalado pip3, pipenv y Django

utilizare vite para crear el projecto con react

en el framework: REact
en la variante:

una vez realizado esto, cambio de carpeta a frontend e intsalo npm install

aqui se crean varias carpetas

comienzo a instalar django
activamos el entorno virtual pipenv shell

instalamos pipenv install django

luego ejecutamos este comando: django-admin startproject backend
que creara una carpeta backend con una estructura

ejecutamos el comando python manage.py startapp api
creara una estructura con el nombre API

definimos la aplicacion, colocamos 'api' dentro del archivo settings.py, en la seccion de INSTALLED_APPS

vamos a instalar POSTGRESQL para django
con comando pipenv install psycopg2-binary

para hacer un break y guardar el trabajo:

desde la raiz principal del proyecto
git status = para ver los archivos tocados
git add . para guardar todo
un git commit -m "hacemos uno"
luego subimos los cambios a GItHub
git push origin main

para volver y trabajar en el proyecto
lo abrir VS luego navegue hasta mi carpetra backend (cd backend)
una vez ahi introduje el comando PIPENV SHELL
y active mi entorno virtual, me di cuenta porque comienza con .env

luego navego a la carpeta principal del proyecto y voy actualizarla
en caso de que no este sincronizado con mi proyecto en github
y ejecuto el comando git pull origin main,
esto actualizara mi proyecto aqui en local, en mi editor
