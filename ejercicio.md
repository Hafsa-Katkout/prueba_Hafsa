# Creación y Sincronización de un Repositorio Git entre Windows y Linux Debian

Paso 1: Crear un nuevo repositorio local en Windows
Comando: **git init**
Lo primero que haremos será crear un repositorio en nuestra máquina con Windows. Este será el repositorio donde inicializaremos nuestro proyecto llamado "prueba2_Hafsa":

![Prueba](./img/2.jpg)
--- 
Archivos: archivo1.txt y archivo2.txt

![Prueba](./img/6.jpg)

crear el repositorio en Github :

![Prueba](./img/3.jpg)

Tener el URL desde GITHUB :

![Prueba](./img/4.jpg)

Para iniciar el control de versiones y permitir el seguimiento de cambios en la carpeta:
![Prueba](./img/5.jpg)

Paso 2: Conectar con un repositorio remoto en GitHub
Comando: git remote add origin [URL del repositorio en GitHub]
Ahora vamos a conectar nuestro repositorio local en Windows con un repositorio remoto en GitHub. Esto nos permitirá subir nuestros archivos para compartirlos con otros desarrolladores o simplemente para hacer una copia de seguridad en la nube:

![Prueba](./img/7.jpg)


Paso 3: Subir el repositorio local a GitHub
Comando: git push origin main
Subimos el repositorio local, incluyendo los archivos archivo1.txt y archivo2.txt al repositorio remoto en GitHub. Este proceso envía todo el contenido del repositorio local a la nube, asegurando que nuestros archivos estén accesibles desde cualquier lugar.




Paso 4: Clonar el repositorio en una máquina virtual Linux Debian
Comando: git clone [URL del repositorio en GitHub]
En la máquina virtual con Linux Debian, clonamos el repositorio remoto. Esto crea una copia local en Debian de todo lo que subimos desde Windows, demostrando cómo Git facilita el trabajo distribuido.



Paso 5: Modificar archivos y agregar un nuevo archivo en Windows
Comandos:
git add archivo1.txt archivo3.txt
git commit -m "Modificado archivo1.txt y agregado archivo3.txt"
git push origin main
Desde Windows, hacemos una modificación en archivo1.txt, y añadimos un nuevo archivo llamado archivo3.txt. Confirmamos los cambios con git commit y los subimos nuevamente a GitHub con git push. Ahora, nuestros cambios están actualizados en el repositorio remoto.





Paso 6: Actualizar el repositorio en Linux Debian
Comando: git pull
Finalmente, en la máquina virtual Debian, actualizamos la versión local del repositorio con el comando git pull. Este comando descarga los cambios que hicimos desde Windows, sincronizando los archivos locales en Debian con los más recientes subidos a GitHub.





