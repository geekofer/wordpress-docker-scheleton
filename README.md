# DockPress
Docker + Wordpress + PhpMyAdmin

#### Variables de Entorno
En el archivo .env se encuentran las variables de entorno a configurar, antes de levantar los contenerdores.


| Variables de Entorno |     |
| ------------- |:-------------:|
| APP_PORT    | puerto donde estará expuesta el wordpress, por defecto es el :8100 |
| DB_DATABASE | nombre de la base de datos del proyecto|
| DB_USER | nombre de usuario de la base de datos |
| DB_PASSWORD | contraseña de la base de datos      |
| MYSQL_ROOT_PASSWORD | contraseña root del contenedor MySQL |
| PMA_PORT | puerto donde estará expuesta el PhpMyAdmin, por defecto es el :8200     |

### Running Contenedores

#### Modo interactivo
`docker-compose up`
#### Modo demonio (en segundo plano)
`docker-compose up -d`

### Stoping Contenedores
`docker-compose down`

### Entrar a un contenedor en modo interactivo

`docker exec -ti`


