# Reporte de Retos

> Completar este archivo como parte de la entrega final.

## Datos del estudiante

Nombre: Valentina Hernandez y Juan Manuel Trujillo.

Usuario Github: avhernandezr y juanmtrujillo2008-pixel

Fecha: 21/04/2026


---

## Reto 1

### Comandos usados
- control +s 
- git romote -v
- git status
- git add equipo/integrantes.txt
- git commit -m "Reto 1: Valentina Hernandez"
- git checkout main
- git push


### Decisiones
Descargué el repositorio y lo cloné para luego abrir una nueva terminal.
Realicé el cambio en el documento y oprimí "Ctrl+s" para seleccionarlos.
Luego utilicé "git status" para revisar el estado del repositorio. 
Seguidamente, utilicé "git add equipo/integrantes.txt", para colocar el cambio del archivo en el area de preparación.
Luego con "git commit -m "Reto 1: Valentina Hernandez"" lo que hago es nombrar dicha prparación o cambio, de este modo queda registrada.
Finalmente con "git checkout main" me dirijo al origen y con "git push" guardo los cambios en el servidor, en este caso el repositorio de GitHub.


### Dificultades (opcional)


## Reto 2

### Comandos usados
git branch equipo-A-objetivos
git checkout equipo-A-objetivos
Ctrl + s
git add docs/objetivos.md
git commit -m "objetivo"
git checkout main
it branch equipo-A-modulos
git checkout equipo-A-modulos
Ctrl + s
git add app/modulos.txt
git commit -m "modulos"
git checkout main
git merge equipo-A-Objetivos
git merge equipo-A-modulos
git push

### Decisiones
Primero uso "git branch equipo-A-objetivos" para crear la rama. Luego uso "git checkout equipo-A-Objetivos" para dirigirme a esa rama. Hago los cambios necesarios, selecciono las lineas que cambie y toco "Ctrl+S" y pongo "git add docs/objetivos.md" para preparar los cambios. Luego "git commit -m "objetivo"" para guardarlo. Repito el mismo procedimiento para la segunda rama.
 Luego voy a la rama principal con "git checkout main" y con "git merge equipo-A-Objetivos", "git merge equipo-A-modulos" guardo los datos de las dos ramas en la principal. 
 Finalmente uso "git push" para subirlo a GitHub.

### Dificultades 
Al no introducir mensaje, tuve que poner el mensaje entre comillas y "esc :wq" 
 "esc" me permite salir.
 ":" indica que voy a introducir un comando.
 "w" siginifica write y me permite guardar los cambios.
 "q" signifca quit, le dice al editor que se cierre y te devuelve a la terminal.


## Reto 3

### Comandos usados
git ckeckout main
git branch rama-tarea-AB
Ctrl + S
git add docs/comanods.md
git commit -m ""
git checkout main
git merge rama-tarea-AB
git push 
git pull origin main




### Decisiones
Agregué a mi colaborador como participante desde GitHub. 
Luego repetimos el proceso de la tarea 2 para crear una rama y editar el archivo. Finalmente, "git pull origin main" nos permitió actualizar los cambios hechos por el respectivo colaborador para que aparecieran en ambos repositorios.

### Dificultades (opcional)



## Reto 4

### Comandos usados
git ckeckout main
git branch version-ajuste-1
Ctrl + S
git add app/comanods.md
git commit -m ""
git checkout main
git merge version-ajuste-1
git push 
git ckeckout main
git branch version-ajuste-2
Ctrl + S
git add app/comanodos.md
git commit -m ""
git checkout main
git merge version-ajuste-2
CONFLICT
git status 
Borro la línea <<<<<<< HEAD.
Borro la línea =======. 
Borro la linea que no quiero 
git status 
git add app/versiones.txt git commit -m "resolucion" 
git checkout main 
git checkout version-ajuste-1
git push

### Decisiones
Una vez ocurrido el error, insertamos "git status" para identificarlo. Esto nos dirige al problema y allá procedemos a borrar la línea <<<<<<< HEAD. 
Luego a borrar la línea =======. 
Si se desea conservar solo una modificacion, se borra la linea que no queremos. Sino se hace lo mismo pero conservando ambas lineas.
Finalmente se vuelve a checkear el status "git status" y se guarda la resolucion, "git add app/versiones.txt", "git commit -m "resolucion"", "git checkout main", "git checkout version-ajuste-1", "git push".
### Dificultades 



## Reto 5

### Comandos usados
Caso 1 previo a add
Hacer el cambio y lo seleccionar con Ctrl +S 
git diff 
git restore docs/flujo-trabajo.md
git status

Caso 2 habiendo ingresado add
Hacer el cambio y seleccionar con Ctrl +S 
git add docs/flujo-trabajo.md
git restore --staged docs/flujo-trabajo.md
git restore docs/flujo-trabajo.md
### Decisiones
Caso 1 previo a add
Hago un cambio pero no lo guardo, lo selecciono con Ctrl+s. Oprimo "git diff" para ver el cambio realizado, una vez oprimido, te muestra -texto en color rojo, para indicar lo que borraste y +texto en color verde para mostrar el nuevo texto. Ingreso git "restore docs/flujo-trabajo.md" para volver a la version anterior, al error cometido, de esta forma se borra lo último agregado. Finalmente, se oprime "git status" para ver el estado del archivo corregido.

Caso 2 habiendo ingresado add
Hago un cambio, lo selecciono con Ctrl+s y lo guardo con "git add docs/flujo-trabajo.md" . Oprimo "git diff" para ver el cambio realizado, esto te muestra -texto en color rojo, para indicar lo que borraste y +texto en color verde para mostrar el nuevo texto. Luego para sacar el archivo del area de preparacion, a la cual ingreso con "git add" pongo "git restore --staged docs/flujo-trabajo.md". Posterior a haberlo sacado del "area de preparacion" al igual que en el caso anterior oprimo "git restore docs/flujo-trabajo.md" para volver a la versión anterior al error cometido, de esta forma se borra lo último agregado. Finalmente, se usa "git status" para ver el estado del archivo corregido" 
### Dificultades (opcional)


