## Crear la rama "primera" en el repositorio local
 Usando el comando `git branch -b primera`
![jzcr](./images/eje3.2_images/1.jpg)



  ### Instrucción para comprobar la creación de la rama
Usando el comando `git branch`

![jzcr](./images/eje3.2_images/2.jpg)

## Añadir un nuevo fichero en la rama "primera" y fusionarlo con la rama principal


   ### Explicación del proceso:
 Primero, añadir un nuevo archivo en la rama "primera" , por ejemplo llamarlo `archivo.txt`

   ![jzcr](./images/eje3.2_images/3.jpg)

Luego, cambiar a la rama principal main:
![jzcr](./images/eje3.2_images/4.jpg)

Ahora, fusionar la rama "primera" con la rama principal :
![jzcr](./images/eje3.2_images/5.jpg)

   ### ¿Se ha producido conflicto?
      No 

   ### Razón de la respuesta
porque no hay modificaciones simultáneas en los mismos archivos desde ambas ramas.


## Eliminar la rama "primera"
![jzcr](./images/eje3.2_images/6.jpg)

## Crear la rama "segunda" y provocar un conflicto
primero creamos la rama `segunda` :

![jzcr](./images/eje3.2_images/7.jpg)


   ### Modificación del fichero para generar un conflicto
   modificamos el fichero dentro de la rama `segunda` :

![jzcr](./images/eje3.2_images/9.jpg)

entramos en el mismo archivo desde la rama main y hacemos modificacion : 

![jzcr](./images/eje3.2_images/10.jpg)

hacemos `git merge segunda`: y nos da el **conflicto** :

![jzcr](./images/eje3.2_images/11.jpg)

![jzcr](./images/eje3.2_images/12.jpg)




## Resolver el conflicto y sincronizar la rama "segunda" en GitHub



   ### Solución del conflicto
![jzcr](./images/eje3.2_images/13.jpg)
![jzcr](./images/eje3.2_images/14.jpg)


   ### Sincronización de la rama en el repositorio remoto
   
![jzcr](./images/eje3.2_images/15.jpg)


   ### Captura de pantalla del repositorio en GitHub mostrando la creación de la rama