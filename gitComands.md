*****************************************
Comandos git para el control de proyecto*
*****************************************

Antes de realizar los pasos descritos a continuación se debe verificar que en la terminal se este situado en la direccion del proyecto.
Nota: Solicitar al administrador que le otorgue permisos de edición.

1) Clonar nuestro proyecto
git clone https://github.com/UN-Bogota/Proyecto_1.git

2) Crear una nueva rama
git checkout -b NUEVARAMA

3) Verificar que se esta sobre la rama nueva: NUEVARAMA
git branch

4) Despues de realizar los cambios validar el estado de la rama
git status

5) Agregar los cambios a git
git add .

6) hacer el commit de los cambios
git commit -m "Descrcipcion de los cambios"

7) Bajar los cambios de la rama master
git pull origin main

8) Hacer el push al servidor 
git push origin NUEVARAMA    


***********************************************************************************************
ANTES DE DESPLEGAR POR FAVOR AVISAR EN EL GRUPO, PARA PODER VALIDAR CAMBIOS ANTES DE PUBLICAR
***********************************************************************************************

8) pasar a la rama master
git checkout main


10) bajar cambios para resolver posibles conflictos
git pull origin main		


9) hacer el merge (Juntar la rama de trabajo NUEVARAMA con la rama main)
git merge NUEVARAMA

10) publicar master
git push origin main


*******************************************************************************
Validar en el proyecto puesto en produccion que los cambios se hayan realizado
*******************************************************************************