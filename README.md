# :whale: Práctica con docker-compose :whale:

Wordpress con PHP-FPM, MariaDB y Nginx como proxy.

Crear un fichero _.env_ en el directorio con el siguiente contenido:

```
USER_DB=<NombreUsuario>
ROOT_DB_PASSWORD=<ContraseñaRoot>
USER_DB_PASSWORD=<ContraseñaUsuario>
```

Lanzar la siguiente linea en la consola situado en el directorio:

```
docker-compose up -d
```
