# ntopng
docker-compose ntopng | High-Speed Web-based Traffic Analysis and Flow Collection

![ntop](https://github.com/JLalib/docker-ntopng/assets/57844755/bd01f959-91f5-4c50-ad07-c1fb0d505f5a)

Crear el directorio de trabajo en docker y situarse en él.

mkdir ntopng && cd ntopng

Crear los directoios ntopng y redis y darles permisos 777.

mkdir -p data/ntopng

mkdir -p data/redis

Crear el fichero docker-compose.yml o copiarlo de aquí.

nano docker-compose.yml

Modificar la configuración y guardar los cambios.

Levantar el contenedor

docker-compose up -d

Acceso vía http://IP-SERVER-DOCKER:3000

Usuario y contraseña

admin:admin

Nota: Es importante que en caso de parar el contenedor ntopng y redis, levantar previamente le redis antes, para que así coja las credenciales guardadas en la bbdd.
