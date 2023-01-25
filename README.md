#comandos utiles de git

1. git init (este comando inicializa el repositorio)
2. git add . (este comando agrega todos los archivos al escenario que se conoce como el stage y los prepara para el commit)
3. git reset . (revierte el git add .) 
4. git commit -m "" (guarda los cambios)
5. git checkout --. (recontruye los archivos a como estaban en el ultimo commit, esto es siempre y cuando se le este dando seguimiento con git)
6. git log (es para ver un historial de los commit realizados)
7. git commit --amend (es para editar los commit ,una vez el comando ingresado se debe presionar i para ingresar los datos y luego de tener los datos editados se debe presionar esc luego : seguido de w luego el comando q para salir y finalmente ! para que lo haga inmediatamente el comando completo es :wq! )
8. git checkout -b rama-heroes (para crear una rama nueva, el -b signica branch en este ejemplo el rama-heroes seria el nombre de la rama)

9. git checkout master (para cambiar de rama, el nombre master es el nombre de la rama a la que se desea cambiar)

10. git branch -d rama-heroes (este comando es para borrar una rama el -d es por delete y en este ejemplo la rama-heroes es el nombre de la rama que deseamos borrar)

11. git push (este comando es para subir los cambios hechos)