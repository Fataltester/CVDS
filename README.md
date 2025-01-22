## Laboratorio 01 Parte I (Individual)
### Juan David Martinez Mendez
1. Crear un repositorio localmente
Para el desarrollo de este punto, creamos una carpeta llamada "cvds" en la parte de descargas y por medio del comando git init inicialimos el repositorio dentro de la carpeta, obviamente sin antes estar ubicados dentro de esa carpeta por medio del comando cd
![](/images/1.png)

2. Para agregar un archivo al repositorio local utilizamos el comando git add nombre del archivo, para verificar que el archivo se ha agregado usaremos el comando git status
![](/images/2.png)

![README en visual](/images/0.png)

3. 

git add: agrega el contenido de todos los archivos al indice, con el objetivo de preparar este archivo para la proxima confirmacion
si utilizamos unicamente git add todos los archivos dentro del espacio de trabajo seran tomados, pero si despues del add especificamos el nombre de un archivo que este dentro del espacio de trabajo, solo se tomara ese trabajo.

git commit -m "mensaje" : comando realizar un commit con un mensaje de por medio, es decir, realizamos lla copia de los archivos en el indice y relacionamos esto con un mensaje.

4.
![](/images/4.png)

5. El repositorio se llama CVDS y lo he creado vacio, sin siquiera el readme que da como opcion a crear al configurar el repositorio
![Repositorio vacio](/images/5.png)

6.

1. Vamos a agregar tambien una carpeta de imagenes que tenemos para este markdown al git, por lo que haremos otro git add
![](/images/6.1.png)

2. Despues vamos a realizar un commit con mensaje para asi realizar la copia de los archivos y relacionarlos con un mensaje
![](/images/6.2.png)

3.Para enlazar el repositorio local con el base, utilizamos el comando remote y el enlace que nos da github para poder conectar los dos repositorios

4. finalmente hacemos el push para subir los archivos al repositorio github remoto, pasamos todo del local(origin) a la rama master del repositorio remoto.
![](/images/6.4.png)

7. Prueba de los commits que realizamos
![](/images/7.png)

8.
![](/images/8.png)

## Parte II (Trabajo en Parejas)
1. 
Owner: Juan David\
Collaborator: Santiago 

6. Al realizar el push al mismo tiempo, El Owner obtuvo el error, por lo que solo el colaborador pudo realizar exitosamente la transaccion
![](/images/parte2_6.png)
![](/images/parte2_6_1.png)

7. Para observar los cambios realizados, primero cerramos el archivo y luego realizamos un pull
![](/images/parte2_62.png)

Al realizar el pull se revisaron los cambios que habia hecho el colaborador y se aceptaron todos los cambios que realizo

8. para este punto se generara el cambio en intelliJ:
![](/images/parte2_8_1.PNG)
![](/images/parte2_8.png)
9. se muestra una pantalla dividida en 3 secciones donde la izquierda estan los cambios en local, derecha los cambios del repositorio remoto y el centro el resultado.
![](/images/merge_intellij.png)

## Parte III (Trabajo en Parejas)
1. Hay una mejor forma de trabajar con git para no tener conflictos?\
Si, se pueden utilizar diferentes ramas entre los usuarios que estan editando los archivos, para que cada uno tenga los cambios individuales;
 y cuando se terminen de generar los cambios, se hace un _Pull Request_ para mirar si son aceptados o no a la version final.
2. 
3. se generaron las ramas para cada uno de los usuarios:
![](images/ramaJuan.png)
![](images/ramaGualdron.png)
