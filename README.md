# codigo-13-semana1
semana 1 del bootcamp Codigo Tecsup -n°13

##Comando para GIT

````
git init
````
-Este comando solo se hace una vez por proyecto, sirve para inicializar nuestro proyecto con git

-:eye: crear una  carpeta oculta llamada ````.git````

````
git status 
````
-Poder listar y ver si los archivos estan listo para subir

-:eye:  de los archivos no esten listos veran en color rojo y cuando lo esten serán de color ver

````
git add .
git add nombre_de_archivo
````
-Se encarga de agregar los archivos a la memoria de GIT, es decir los guarda en un stash

````
git commit -m "comentario"
````
-Crea un punto en la linea de tiempo :clock: de nuestros cambios y a estos se le es posible adjuntar un comentario

-:eye: Los comentarios deben estar relacionados a los comentarios que hice, esto es una recomendación

````
git push origin main
````
-Sirve para poder subir los cambios a nuestro repositorio en la nube, en esta caso GITHUB

````
solucion a error "refusing to merge unrelated histories"
````
-git pull origin master --allow-unrelated-histories

````
clonar repositorio
````
-git clone url_de_github.com

-Te permite crear por default una carpeta con el nombre del repositorio

````
git branch
````

--Sirve para poder listar los branch que tengo localmente y me dice en el cual me encuentro actualmente

````
git checkout -b nombre_del_branch
````
-Sirve para crear un branch nuevo y poder trabajar en el

````
git checkout  nombre_del_branch
````
-sirve para moverme entre ramas (branch)

-:eye: Si el checkout no tiene el -b solamente es para moverse

````
git fetch
````

-Actualiza cambios en la rama pero referente a nuevas ramas cradas

````
git branch -d nombre_branch
````

-Esto elimina una branch de manera local

````
git merge nombre_de_branch_con_la_que_quieres_unir // git merge develop-jhonatan_aliaga
````

hacer el cambio en main desde otro branch previamente hecho



