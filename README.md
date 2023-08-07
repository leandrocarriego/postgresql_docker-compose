# BASE DE DATOS POSTGRESQL
## PostgreSQL - PgAdmin - Docker

Si quieres inicializar una base de datos PostgreSQL sin tenerla instalada localmente puedes clonar este repositorio e inicializarla utilizando Docker.

### Clonar y Ejecutar Proyecto con Docker compose

### Requisitos previos

1. [Docker](https://www.docker.com/) - Asegúrate de tener Docker instalado y configurado correctamente.

2. [Git](https://git-scm.com/) - Necesitarás Git para clonar el repositorio.

## Pasos para clonar y ejecutar el proyecto

1. **Clonar el repositorio:**
   Abre tu terminal (o línea de comandos) y ejecuta el siguiente comando para clonar el proyecto desde GitHub:

   ```bash data-copyable
    git clone https://github.com/leandrocarriego/postgresql_docker-compose.git

2. **Configura tus variables de entorno en un archivo .env utilizando el archivo .env.example:**

3. **Iniciar proyecto en docker**
    
    ```bash data-copyable
    docker-compose up

### Puedes acceder importando la variable de entorno POSTGRESQL_URI en tu proyecto.

