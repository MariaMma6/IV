##PRÁCTICA 0 - Discos en RAID

**1. Creación de clave ssh y añadido a GitHub de la misma**

Para generar la clave ssh-rsa usaremos el siguiente comando:


	ssh-keygen -t rsa -C "mariia_ma_6@hotmail.com"

Se nos generará una clave la cual encontraremos en el archivo C:\Users\Maria Martin\.ssh\id_rsa.pub

Copiamos dicha clave y nos dirigimos al apartado Personal Settings de nuestro GitHub,concretamente a la pestaña SSH and GPG keys.
Le damos a opción "New SSH key" y pegamos la clave generada para añadirla.

![img](https://github.com/MariaMma6/IV//imagenes/P0-0.PNG  " ")


**2. Configuración de perfil**
Añadiremos nuestro usuario y correo mediante los siguientes comandos para que aparezcan en los commits.

	git config --global user.name "MariaMma6"
	git config --global user.email mariia_ma_6@hotmail.com

**3. Creación de hitos e issues**
Crearemos nuestro primer hito el cual será la entrega de la práctica 0, y además crearemos un issue para
actualizar el archivo README.md

![img](https://github.com/MariaMma6/IV//imagenes/P0-1.PNG  " ")

Seguidamente clonaremos nuestro repositorio.

![img](https://github.com/MariaMma6/IV//imagenes/P0-2.PNG  " ")

Actualizamos nuestro archivo README.md y cerramos el issue creado para dicha tarea.

![img](https://github.com/MariaMma6/IV//imagenes/P0-3.PNG  " ")


**4. Creación de ramas**

Por último creamos una rama:

	git cheackout -b hito0
	git push origin hito0

Y nos posicionamos en ella para subir la practica 0:

	git branch


![img](https://github.com/MariaMma6/IV//imagenes/P0-4.PNG  " ")

