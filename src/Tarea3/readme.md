El primer apartado consta de descargar la imagen "alpine",para eso usamos por terminal el comando siguiente:

![Docker1.png](Fotos/Docker1.png)

Y para comprobar que esta se encuentra el equipo ejecutamos el comando:

![Docker2.png](Fotos/Docker2.png)


El segundo apartado es crear un contenedor sin asignarle un nombre.

![Docker3.png](Fotos/Docker3.png)

Este contenedor adquiere autimaticamente un nombre aleatorio, y para comprobar si está en ejecución o no ejecutamos el siguiente comando que nos muestra los contenedores activos, el cual está vacío

![Docker4.png](Fotos/Docker4.png)

Para obtener el nombre usamos el siguiente comando que muestra todos los contenedores:

![Docker5.png](Fotos/Docker5.png)

Para el tercer apartado creamos un contenedor llamado dam_alp1

![Docker6.png](Fotos/Docker6.png)

Para acceder a ella primero debemos iniciarla y después introducir el siguiente comando

![Docker7.png](Fotos/Docker7.png)

El cuarto apartado nos pregunta cual es la IP del contenedor, ejecutamos el siguiente comando

![Docker8.png](Fotos/Docker8.png)

Para saber si se puede usar ping google.com, debemos iniciar el contenedor y ejecutar el siguiente comando:

![Docker9.png](Fotos/Docker9.png)

Ahora creamos un segundo contenedor llamado dam_alp2

![Docker10.png](Fotos/Docker10.png)

Para usar el comando ping entre los dos contenedores, debemos ejecutar el primer contenedor y después usar el comando ping sobre el segundo

![Docker11.png](Fotos/Docker11.png)

Al cerrar la terminal, el conenedor en ejecución termina.