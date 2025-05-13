**ejemplos de programación orientada a objetos**
## 1. crear eel archivo **.gitignore**

se crea el archivo **.gitignore** para configurar los archivos que no se sincronizaán con el repositorio 


````shell
    *.pyc
__pycahe__/
.venv/
````

## 2. se crea el **virtual enviroment**

se crea el ambiente virtual de trabajo de python 

````shell
python3 -m venv .venv
````

## 3. iniciar el **virtual enviroment**

se crea el **virtual enviroment** para instalar las librerias necesarias para el protecto 

````shell
source .venv/bin/activate
````

## 4. actualizar **pip** dentro de el **virtual enviroment**

se actualiza la version instalada de **pip** para poder descargar las ultimas versiones de las librerias 

````shell
pip install --upgrade pip
````
## 5. verificar las librerias instalada

se verifican que las librerias y versiones se  tienen instaladas 

````shell
pip freeze
````
## 6. intalar librerias 

se instalan las librerias que van a a ocupar en el proyecto

````shell
pip install web.py
````

## 7. crear el archivo **requirements.txt**

se crea el archivo **requirements.txt** con las liberias y el numero de version  utilizada

````shell
pip freeze > requirements.txt
````

## 8. crear el archivo **runtime.txt**

se crea el archivo **runtime.txt** con la version de python3 que se esta utilizando para el proyecto

````shell
python3 -V > runtime.txt
````

## 9. indexar los archivos 






## 10. generar **commit**
 se realiza un **commit** con un texto que describa los cambios realizados en el proyecto

 ````shell
 git commit -m "CREATED configuracion basica "
 ````

 ## 11. realizar un **push**

 se realiza un **push** para subir los cambios realizados al repositorio de **GitHub**

 ````shell
 git push -u origin main
 ````

 ## 12.