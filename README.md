# ntopng
docker-compose ntopng | High-Speed Web-based Traffic Analysis and Flow Collection

![ntop](https://github.com/JLalib/docker-ntopng/assets/57844755/bd01f959-91f5-4c50-ad07-c1fb0d505f5a)

Crea el directorio de trabajo en docker y situate en él.

mkdir ntopng && cd ntopng

Crea los directoios ntopng y redis y dales permisos 777.

mkdir -p /data/ntopng

mkdir -p /data/redis

Crea el fichero docker-compose.yml o copialo de aquí.

nano docker-compose.yml

Modificalo a tu configuración, guarda los cambios.

Levanta el contenedor

docker-compose up -d

