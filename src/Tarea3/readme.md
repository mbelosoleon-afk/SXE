El primer apartado consta de descargar la imagen "alpine",para eso usamos por terminal el comando siguiente:

![Docker1.png](Fotos/Docker1.png)

Y para comprobar que esta se encuentra el equipo ejecutamos el comando:

![Docker2.png](Fotos/Docker2.png)


El segundo apartado es crear un contenedor sin asignarle un nombre.

![Docker3.png](Fotos/Docker3.png)

Este contenedor adquiere autimaticamente un nombre aleatorio, y para comprobar si está en ejecución o no ejecutamos el siguiente comando que nos muestra los contenedores activos, el cual está vacío

![Docker4.png](Fotos/Docker4.png)

Para el apartado 3 debemos crear un contenedor llamado dam_alp1 y acceder a el. Para ello debemos crear un contenedor y usamos el comando infinity para que se ejecute continuamente.

![Docker6.png](Fotos/Docker6.png)

Para acceder al contenedor usamos el siguiente comando. Si estamos dentro de el, aparecerá el símbolo "#". Para salir de este ejecutamos ctrl + P y ctrl + Q

![Docker7.png](Fotos/Docker7.png)

Para comprobar la ip ejecutamos el siguiente comando

![Docker8.png](Fotos/Docker8.png)

Para usar el comando ping debemos ejecutar primero el contenedor y después usar el comando ping

![Docker9.png](Fotos/Docker9.png)

En el quinto apartado nos pide crear otro contenedor y hacer ping entre estos. Para ello creamos el contenedor y buscamos su IP

![Docker10.png](Fotos/Docker10.png)

Para ejecutar ping, debemos ejecutar el primer contenedor y dentro ejecutar ping con la ip del segundo contenedor

![Docker11.png](Fotos/Docker11.png)

Para salir de la terminal ejecutamos exit. Con respecto al contenedor, debido al comando infinity, este se seguirá ejecutando.

Para saber cuanta memoria en el disco duro se ocupó ejecutamos el siguiente comando

![Docker12.png](Fotos/Docker12.png)

Por último para ver la RAM que ocupan, usamos el comando docker stats

![Docker13.png](Fotos/Docker13.png)