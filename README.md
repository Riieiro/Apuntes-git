# Proyecto IAW - GIT/Github

---------------
## Vincular GIT con Github
- ```git config --global user.name "<NOMBRE>"```
- ```git config --global user.mail "<EMAIL>"```
--------------
## Comandos útiles
- ```git init``` -> Crear rama (Por default crea nombre master)
- ```git branch -M main``` -> Cambiar el nombre a la rama
- ```git status``` -> Ver el estado de la rama(Si tienes archivos en el directorio que no están subidos te lo avisa)
- ```git add <FILE>``` -> Subir un archivo a la rama (Si pones un git add . añade todos los archivos del directorio || También es necesario este comando para actualizar el contenido de un archio)
- ```git commit -m "<TEXT>"``` -> Subimos el cambio a github
- ```git log``` -> Muestra el registro de todos los cambios
- ```git log --oneline``` -> En una línea muestra el registro de una manera acortada
- ```git tag <HASH> <TAG>``` -> Creamos una etiqueta a un commit
- ```git checkout <TAG>``` -> Retrocedemos al commit que queramos 
- ```git switch -``` -> Volver a la rama principal
- ```git switch -c <NAME>``` -> Crear y meterse en una nueva rama
- ```git merge <TAG>``` -> Fusionar ramas 
- ```git merge --abort``` -> Abortar proceso de fusión
- ```git remote add origin <URL.git>``` -> Vincular con el repositorio 
- ```git remote remove origin``` -> Desvincular del repositorio
- ```git push origin main``` -> Subir a origin la raiz main (Github)
- ```git push --tags``` -> Subir las etiquetas a Github
---------------
