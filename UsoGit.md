# Comandos principales de Git

Una vez instalado Git usaremos una serie de comandos para realizar las operaciones básicas.

1. Para clonar un repositorio existente en GitHub tendremos que poner ```git clone url``` donde url es la url al repositorio de GitHub.
2. Luego con ```git init``` inicializas el repositorio local, para que al hacer cambios en el, puedas mas tarde hacer commits o subirlo al repositorio remoto.
3. Una vez has modificado algun archivo del repositorio local puedes comprobar esos cambios con ```git status```.
4. Después para añadir esos archivos modificados al staging area usamos ```git add``` o ```git add -A```.
5. Una vez hemos modificados archivos y los hemos llevado al staging area ya podremos hacer commit de esos cambios con ```git commit -m "nombre del commit"```.
6. Por último para que ese commit se refleje en el repositorio remoto deberemos hacer ```git push origin main```.