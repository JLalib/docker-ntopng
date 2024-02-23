# ntopng
docker-compose ntopng | High-Speed Web-based Traffic Analysis and Flow Collection

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

