# Practica 4 Contribuir/ iniciar /contribuir a una rama

## iniciar un nuevo repositorio y publicarlo en GitHub
- Creamos un repositorio vacio con el nombre Contribuir-iniciar-contribuir-a-una-ram ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/0.png)
- Con el comando **git init my-repo** creo automaticamente la carpeta en el escritorio sin necesirdad de usar el comando mkdir ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/1.png)
- Entramos dentro de la carpeta con el comando **cd my-repo** y creamos un documento con el comando **sudo touch README.md** ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/2.png)
- Añadimos el archivo al proyecto, para esto tenemos que usar el comando **git add README.md** y despues usamos git status para ver si esta preparado ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/3.png)
- Ahora pasamos a registrar cambios en el historial con el comando **git commit -m "Cambiando cositas"** y vemos que se ha realizado correctamente ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/7.png)
- Apuntamos al repositorio que creamos con el comando **git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git** que en este caso es el que he creado al principio ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/4.png)
- Subimos el archivo creado co nel comando **git push --set-upstream origin master** y vemos que se ha creado correctamente ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/5.png)
- Y en la web vemos como se ha creado correctamente ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/6.png)


