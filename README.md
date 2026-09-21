# ¿Cómo instalar `cine-jorge` con Docker Desktop?

> [!NOTE]
> Estas instrucciones van hechas específicamente para Docker Desktop

## 1. Instalar Docker Image
Primero Inicializamos docker con el siguiente comando: ```docker run -p 8080:80 nginx```.

> [!NOTE]
> El puerto `8080:80` puede ser reemplazado por cualquier otro con la misma estructura `XXXX:YY`.

## 2. Clonar este repo dentro de la carpeta

1. Haces click en _Containers_, luego en el contendor correspondiente y por último en _Exec_.

2. Una vez arrancada el docker y donde le hemos indicado, navegamos hacia `usr/share/nginx` con el siguiente comando: ```cd usr/share/nginx```.

3. Una vez dentro de la carpeta ejecutamos el comando par clonar este repo: ```git clone https://github.com/0w4n/cine-jorge.git```.

4. Posteriormente, eliminamos la carpeta html actual con el siguiente comando: ```rm -rd html```.

5. Renombramos la carpeta actual con un nombre que NGINX entiende ```move cine-jorge html```.


> [!IMPORTANT] 
> Cualquier duda con respescto a docker, puedes resolverla [aquí](https://docs.docker.com/).
