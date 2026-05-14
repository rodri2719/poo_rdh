# poo_rdh
Problemas de programación orientada a objetos
# Poo_RDH_2025
Ejercicios de programación orientada a objetos con python3
#ejemplos de programacion orintada  a objetos
## 1. crear el archivo **.gitignore**
se crea un archivo llamado .gitignore para restringir los archivos a sincronizar.
````
*.pyc
__pycache__/
.venv/
````
## 2. crear el **crear el virtual enviroment**
se crea el ambiente el ambiente virtual de trabajo de python
````shell

python3 -m venv .venv
````
## 3. Iniciar el virtual enviroment para instalar las librerias necesesarias para el proyecto
```shell

source .venv/bin/activate
```
## 4. Actulizar ** pip ** dentro del ** virtula enviroment ** para poder descargar las ultimas versiones de librerias
````shell

pip install --upgrade pip
````
## 5. verificar mis lebrerias y versiones que se tienen instaladas
````shell

pip freeze
````
## 6. Intalar librerias necesarias para le proyecto 
se intalan las librerias necesarian para que le eproyecto y las que se van aa ocupar
```shell

pip install  web.py
```
## 7. Crear el archivo **requirements.txt** con las librerias y el numero de versiones utlizadas
````shell

pip freeze > requirements.txt
````
## 8. Crear el archivo **runtime.txt**
se crea el archivo para 

## 9. Indexar los archivos creados con git
```shell
git add .
```
## 10. se gera un commit 
se genera un comit  con un texto que describa los cambios realizados en el proyecto
```shell

git commit -m "CREATED configuracion basica"
```
## 11shell. Realizar un push

```shell

git push -u origin main
```
