# Documentación GIT
## Ejercicio 1 Git


### 1 .Se crea el fichero y se inicializa (repo01) 
Creo una carpeta llamada repo01 desde
la linea de comandos y la inicializo en 
git con la linea git init repo01:
![alt text](/imagenes/1.png)

### 2. Se añade el fichero Readme.md
Se cea un fichero readme.md y se registran todos
los pasos de este ejercicio:

![alt text](/imagenes/3.png)

### 3. Se añade al stagging area
Para añadirlo al stagging area 
se utiliza git add readme.md

El fichero se encuentra en un "file cycle status" 
se encuentra en un estado unmodified (no modificado)

![alt text](/imagenes/2.png) 

### 4 / 5. Se intentan añadir ficheros con git push
No se esta sincronizando porque no
tenemos el repo de la nube asociado con el
repo local, por eso no pasa nada

### 6. Se crea el repositorio remoto
Se crea un repositorio remoto desde
GitHub:
![alt text](/imagenes/7.png)
y lo sincronizo con los comandos:
![alt text](/imagenes/6.1.png)

### 7. Se crea el repositorio remoto
Ahora si aparece porque tenemos configurada
la ruta del repositorio de github con el local: 
![alt text](/imagenes/6.png) 

### 8. Se realiza snapshot local y se sube al remoto
Se realiza un commit capturando asi el estado
actual del fichero y se realiza con un push la subida
al repositorio remoto:
![alt text](/imagenes/8.png) 
![alt text](/imagenes/9.png) 


## Ejercicio 2 Git


### 1 .Se crea (repo02) desde Github
Se considerará un repositorio remoto, 
no local porque se esta creando de manera
remota desde github. Tampoco esta asociado de ninguna
manera al local:

![alt text](/imagenes/2.1.png) 


### 3 .Se realiza un git clone
Se realiza copiando la URL desde GitHub
y luego se pasa el comando git clone "URL" :

![alt text](/imagenes/2.2.png) 
![alt text](/imagenes/2.2.2.png) 

### 4 .Se crea un readme.md
Creamos el readme.md y le realizamos todos
los comandos necesarios para realizar el commit
(Se incluye la realización del commit):

![alt text](/imagenes/2.3.png) 








