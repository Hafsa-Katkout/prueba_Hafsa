##  listar las ramas locales ejecuta:
![hsagd](./images/1.2.jpg)
## Crear una nueva rama :
![hsagd](./images/2.2.jpg)
## listar las ramas :
![hsagd](./images/3.2.jpg)
## pasar a la nueva rama:
![hsagd](./images/4.2.jpg)

## Comprobar que en la nueva rama hay los mismos ficheros que en la rama principal:

### en la rama main :
![hsagd](./images/5.2.jpg)

### en la rama rama :
![hsagd](./images/6.2.jpg)

## Truco: con el comando git checkout -b [rama] se crea una nueva rama y te posicionas en ella:
- exemple rama llama : 'Hafsa':
![hsagd](./images/7.2.jpg)

## Comprobar que coinciden el último commit en las tres ramas:
![hsagd](./images/8.2.jpg)

## modificar algún fichero:
![hsagd](./images/9.2.jpg)
## crear un nuevo fichero en la rama Hafsa:
![hsagd](./images/10.2.jpg)

## Hacer el commit :
![hsagd](./images/11.2.jpg)

## compruebar que estos cambios no se han reflejado en los ficheros de la rama principal:

![hsagd](./images/12.2.jpg)

## realizar un push para crearlas en remoto:
![hsagd](./images/13.2.jpg)
## Para eliminar una rama ejecutamos : *git branch -d [rama]* :

## unir la rama Hafsa a la principal:

![hsagd](./images/14.2.jpg)

## Hacer un conflicto :
1. Crea un fichero pruebaH.txt en la rama principal main :

![hsagd](./images/15.jpg)

1. accede a la rama Hafsa :

![hsagd](./images/16.jpg)
2. Modifica el fichero con un commit:
![hsagd](./images/17.jpg)
![hsagd](./images/18.jpg)

3. Vuelve a la rama principal. Y modifica de nuevo el fichero antes de realizar el merge :

![hsagd](./images/19.jpg)
![hsagd](./images/20.jpg)

4. Realiza la unión :

![hsagd](./images/21.jpg)

5. Si miramos el fichero:

![hsagd](./images/22.jpg)


