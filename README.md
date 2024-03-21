# BigDataDeveloper

## Descripción del Repositorio
Este repositorio cuenta con las siguientes herramientas:

- MySQL
- Hadoop
- Spark
- Hive
- Jupyter

Todo el contenido se ejecutara en codespace de github.

## Desplegar container

1. Crear un codespace para el repositorio e ingresar al mismo
2. Abrir terminal de codespace
3. Ejecutar el siguiente comando para desplegar los contenedores<br>
```    >_ docker-compose up     ``` <br>
Esta linea desplegara los contenedores y podras ver estos utilizando la extension Docker explorer

## MySQL
Este contenedor contiene una base de datos llamada retail_db y consta de las siguientes tablas: <br>
- customers
- orders
- order_items
- products
- categories
- departments
<br>
credenciales:
user: root
pass: root
port: 3310
<br>
Ejecutar ifconfig en terminal para obtener la ip (eth0)

## Hadoop

Para poder trabajar con hadoop ingresamos al contenedor del datanode. <br>
Abrimos un terminal nuevo y ejecutamos lo siguiente
```     >_ docker exec -it datanode bash     ``` <br> 
Asi para cada contenedor con el que queremos trabajar. <br>

Para utilizar sqoop en el datanode debemos ejecutar lo siguiente
```     >_ sh /datanode/scripts/script.sh     ``` <br> 



