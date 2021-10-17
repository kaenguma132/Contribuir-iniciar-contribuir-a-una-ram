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

## contribuir a un repositorio existente
- "creamos Previamente una rama nuenva ha modo de que hace bastante que ya esta para poder hacer este aprtado ya sea a traves de consola o con el comando **git branch alejandro-onfire**" ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/19.png)


- Descargamos un repisitorio que tengamos ya creado en este caso yo descargare un repositorio que se llama  Projecte-Lunar ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/8.png)
- Usando el comando **git clone https://github.com/kaenguma132/Projecte-Lunar.git** ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/9.png)
- Entramos dentro de la careta y creamos  una rama nuenva con el comando **git branch alejandro-alterado** ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/10.png)
- Cambuiamos a la rama que acabamos de crear usando el comando **git checkout alejandro-alterado** ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/11.png)
- Ahora paso a modificar el archibvo README.md para seguir con la practica ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/12.png)
- Pasamos a preparar los archivos que he modificado con el comando **git add README.md** ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/13.png)
- Comentamos el cabio con el comando **git commit -m "my snapshot"** ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/14.png)
- Ahora subimos los cambios desde la rama que hemos creado anteriormente con el comando **git push --set-upstream origin alejandro-alterado** ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/15.png)
- Revisamos que en el repositorio se ha echo el cambio en el archivo en la rama que hemos creado no en la master ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/16.png)

 ## Contribuir a una rama existente en GitHub
- Descargamos un repisitorio que tengamos ya creado en este caso yo descargare un repositorio que se llama subidagitlab ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/17.png)
- Entramos en la carpeta con el comando  **cd subidagitlab** y usamos otro comando para verificar que esta actualizado  con el comando **git pull** ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/18.png)

- Cambuiamos a la rama que acabamos de crear usando el comando **git checkout alejandro-onfire** ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/20.png)
- Ahora nos dice de modificar algun archivo pero yo he creado 2 nuenvos archivos ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/21.png)
- Pasamos a preparar los archivos que he modificado co nel comando **git add prueba1.txt** y el segundo tambien lo preparamos ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/22.png)
- Comentamos el cabio con el comando **git commit -m "my snapshot"** ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/23.png)
- Realizamos la subida con el comando **git push origin alejandro-onfire** ![GitHub Logo](/Contribuir-iniciar-contribuir-a-una-ram/24.png)
