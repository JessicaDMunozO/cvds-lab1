# Laboratorio 1 - Intorducción a Git.
## CVDS 2023-1
#### Integrantes
+ Jessica Muñoz
+ Ricardo Pulido

## Desarrollo
### PARTE I. CREANDO REPOSITORIOS.
**1.** En una de las cuentas se creó un repositorio y se invitó al otro integrante del grupo. Para esto se siguió la siguiente ruta `Settings > Colaborators > Add people` 
y se colocó el nombre de ususario del otro integrante.

**2.** Se creó un directorio llamado *carpeta* con los archivos de *libro.txt* y *feerratas.txt*

**3.** Se creó un repositorio local con el comando `git init`, luego se clonó el repositorio remoto con el comando `git clone`, se creo el token para autenticar 
y se hizo `push` para subir los cambios al repositorio remoto.

**4.** La integrante agregó los autores al archivo de *libro.txt* y se colocó `git add .` para dejar los cambios en la zona de preparación, luego se hizo el **commit**
con el comando `git commit -m "AUTORES DE LA PAREJA 1 AGREGADOS"`. Por último se enviaron los cambios al repositorio remoto con el comando `git push`.

**5.** Se verificó que los cambios fueran aplicados en el repositorio remoto en *GitHub*.

**6.** El integrante clonó el proyecto que se encontraba en el repositorio remoto con el comando `git clone`.

**7.** El integrante agregó los autores al archivo de *libro.txt* y se colocó `git add .` para dejar los cambios en la zona de preparación, luego se hizo el **commit**
con el comando `git commit -m "Autores de la pareja 2 agregados"`. Por último se enviaron los cambios al repositorio remoto con el comando `git push`.

**8.** Se hizo `git pull` para obtener los commits realizados al repositorio remoto por el integrante.

**9.** Con el comando `gitk` para ver el historial de cambios del repositorio.

**10.** Al tiempo, de forma local, la integrante remueve los paréntesis del archivo *feerratas.txt.* y el integrante corrige la ortografía. Pero al momento de hacer el 
**add, commit** y **push**  no se actualiza el repositorio con los cambios de ambos. En la versión oficial sólo quedaron los cambios de la integrante Jessica.
Por ende, al integrante Ricardo le correspondió hacer el `git pull --rebase` para poder ejecutar el comando `git push`.

**11.** Nuevamente, con el comando `gitk` se ve el historial con todos los cambios realizados sobre el repositorio.
![cvds-lab1-i1](https://user-images.githubusercontent.com/123814482/219976795-49e3fb36-3c36-4f2d-9fca-ed2434d8c090.jpg)
Ahora, en el historial se puede ver la intervención del otro integrante. 

### PARTE II. INTRODUCCIÓN GENERAL GIT
Se creo un directorio llamado *Jessica* y otro llamado *Ricardo*. En cada uno se creó un archivo *README.md* con las características requeridas en formato *Markdown*. 

### PARTE III. GIT BRANCHING
Los pantallazos de la finalización de las secciones *Main* y *Remote* se adjuntaron en cada *README.md* en los directorios de *Jessica* y *Ricardo*.
