
# Trabajando con ramas y uniones
## Índice

- [Trabajando con ramas y uniones](#trabajando-con-ramas-y-uniones)
  - [Índice](#índice)
  - [Listar las ramas locales:](#listar-las-ramas-locales)
  - [Crear una nueva rama :](#crear-una-nueva-rama-)
  - [Listar las ramas :](#listar-las-ramas-)
  - [Pasar a la nueva rama:](#pasar-a-la-nueva-rama)
  - [Comprobar que en la nueva rama hay los mismos ficheros que en la rama principal:](#comprobar-que-en-la-nueva-rama-hay-los-mismos-ficheros-que-en-la-rama-principal)
    - [En la rama 'main' :](#en-la-rama-main-)
    - [En la rama 'rama' :](#en-la-rama-rama-)
  - [Truco: con el comando git checkout -b \[rama\] se crea una nueva rama y te posicionas en ella:](#truco-con-el-comando-git-checkout--b-rama-se-crea-una-nueva-rama-y-te-posicionas-en-ella)
  - [Comprobar que coinciden el último commit en las tres ramas:](#comprobar-que-coinciden-el-último-commit-en-las-tres-ramas)
  - [Modificar algún fichero:](#modificar-algún-fichero)
  - [Crear un nuevo fichero en la rama Hafsa:](#crear-un-nuevo-fichero-en-la-rama-hafsa)
  - [Hacer el commit :](#hacer-el-commit-)
  - [Comprobar que estos cambios no se han reflejado en los ficheros de la rama principal:](#comprobar-que-estos-cambios-no-se-han-reflejado-en-los-ficheros-de-la-rama-principal)
  - [Realizar un push para crearlas en remoto:](#realizar-un-push-para-crearlas-en-remoto)
  - [Para eliminar una rama ejecutamos : *git branch -d \[rama\]* :](#para-eliminar-una-rama-ejecutamos--git-branch--d-rama-)
  - [Unir la rama Hafsa a la principal:](#unir-la-rama-hafsa-a-la-principal)
  - [Hacer un conflicto :](#hacer-un-conflicto-)

---


##  Listar las ramas locales:
![hsagd](./images/1.2.jpg)
## Crear una nueva rama :
![hsagd](./images/2.2.jpg)
## Listar las ramas :
![hsagd](./images/3.2.jpg)
## Pasar a la nueva rama:
![hsagd](./images/4.2.jpg)

## Comprobar que en la nueva rama hay los mismos ficheros que en la rama principal:

### En la rama 'main' :
![hsagd](./images/5.2.jpg)

### En la rama 'rama' :
![hsagd](./images/6.2.jpg)

## Truco: con el comando git checkout -b [rama] se crea una nueva rama y te posicionas en ella:
- exemple rama llama : 'Hafsa':
![hsagd](./images/7.2.jpg)

## Comprobar que coinciden el último commit en las tres ramas:
![hsagd](./images/8.2.jpg)

## Modificar algún fichero:
![hsagd](./images/9.2.jpg)
## Crear un nuevo fichero en la rama Hafsa:
![hsagd](./images/10.2.jpg)

## Hacer el commit :
![hsagd](./images/11.2.jpg)

## Comprobar que estos cambios no se han reflejado en los ficheros de la rama principal:

![hsagd](./images/12.2.jpg)

## Realizar un push para crearlas en remoto:
![hsagd](./images/13.2.jpg)
## Para eliminar una rama ejecutamos : *git branch -d [rama]* :

## Unir la rama Hafsa a la principal:

![hsagd](./images/14.2.jpg)

## Hacer un conflicto :
1. Crea un fichero pruebaH.txt en la rama principal main :

![hsagd](./images/15.jpg)

1. AccedeR a la rama Hafsa :

![hsagd](./images/16.jpg)
2. Modifica el fichero con un commit:
![hsagd](./images/17.jpg)
![hsagd](./images/18.jpg)

3. Volver a la rama principal. Y modificar de nuevo el fichero antes de realizar el merge :

![hsagd](./images/19.jpg)
![hsagd](./images/20.jpg)

4. Realizar la unión :

![hsagd](./images/21.jpg)

5. Si miramos el fichero:

![hsagd](./images/22.jpg)


