# Practica 4 Contribuir/ iniciar /contribuir a una rama

## iniciar un nuevo repositorio y publicarlo en GitHub

- Con el comando **git init my-repo** creo automaticamente la carpeta en el escritorio sin necesirdad de usar el comando mkdir  ![GitHub Logo](/
Contribuir-iniciar-contribuir-a-una-ram /1.png)
- Entramos dentro de la carpeta con el comando **cd my-repo** y creamos un documento con el comando **sudo touch README.md** ![GitHub Logo](/
Contribuir-iniciar-contribuir-a-una-ram /2.png)
- Añadimos el archivo al proyecto, para esto tenemos que usar el comando **git add README.md** y despues usamos git status para ver si esta preparado ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram /3.png)
- Ahora pasamos a registrar cambios en el historial con el comando **git commit -m "Cambiando cositas"** y vemos que se ha realizado correctamente![GitHub Logo](/gitlab/10.png)

# provide the path for the repository you created on github
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git

# push changes to github
git push --set-upstream origin main
