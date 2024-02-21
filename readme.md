## ___Ejercicio 1 - Como crear un repositorio___
1. _Primero se habre el git.bash para realizar el proceso_
![Missing file](./img/abir%20git.bash.png "Consola del git-bash") 
_Despues se moviliza a la carpeta del escritorio para mas comodidad_  
![Missing file](./img/ir%20al%20escritorio.png "Cd = change directory hacia el escritorio")  
 _una vez en el escritorio se puede utilizar el comando __get init__ y el nombre de la carpeta_  
![Missing file](./img/get%20initpng.png "get init y el nombre de la carpeta que deseamos")       

#### ___para realizarlo en un entorno visual mas comodo hare uso del visual studio code, para vincular la consola del git.bash haremos lo siguiente___

    1.1 _indicamos el comando __“code .“__ para que se nos abra el programa visual studio code_  
![Missing file](./img/code..png "code hace referencia a visual studio code")  

![Missing file](./img/visual%20studio%20consola.png "visual studio code consola vinculada")  

_ahora el visual studio code está vinculado a nivel de consola pero a nivel de archivos no, para que se vincule arrastramos la carpeta creada (repo01) hacia el programa_  
![Missing file](./img/visual%20studio%20carpteapng.png "carpeta vinculada")  

2. ___Creacion del archivo .md___  
    
    
    _al lado del nombre de la carpeta hay distintos botones_  


     ![Missing file](./img/carpeta%20botones%201.png "opciones para crear ")  
   _utilizaremos la primera opción_  

    ![Missing file](./img/carpeta%20botones%202.png "crear fichero ")  

    _se crea el readme.md_  

    ![Missing file](./img/readme.png "readme.md ")  
   
## Pasos para subir un archivo  
|Pasos |Comando | explicacion |
|:---: |:- |----:| 
|1.|![Missing file](./img/git%20status.png "git status ")| Se verifica si el archivo esta en Undifined (no identificado,modificado o borraro)|
|2.|![Missing file](./img/se%20añade%20al%20staged%20area.png "se añade al staged area ")| para poder realizar una subida de archivos a la nube, se debe añadir dichos archivos al staged area (es decir area pre-preparada para ser subidas a la nube)|
|3.|![Missing File](./img/comit.png "mensaje del commit") | El commit se encarga de fijar los archivos del staged area para que sean subidos a la nube es recomendable añadirle un comentario al paquete con los distintos archivos para que no se pierda la linea de modificaciones que se puede realizar|
|4.|![Missing File](./img/git%20push%20problema.png "primer problema del git push")|la primera vez que se realiza el "git push" no tenemos un puntero a donde dirigir nuestros paquetes con distintos archivos a la nube para ver si tenemos configurado algun punto se indica git remote -v|
|4.1|![Missing File](./img/github.png "se crea el repositorio")|Primero se crea el repositorio en github|
|4.2|![Missing file](./img/git%20remote.png "git remote configurado")|mediante el siguinte comando remote origin establecemos que nuestro repositorio en la nube|
|4.3|![Missing File](./img/branch.png "cambio del master por main")|cuando se trabaja con github es recomendable cambiar el branch (rama) de master a main para mas comodidad|
|4.4|![Missing File](./img/push.png "el push con puntero")|Finalmente se sube a la nube con el comando "push"