# Mi aprendizaje

### Aprendizaje obtenido al configurar SonarQube con Docker Compose

Durante la configuración de SonarQube utilizando Docker Compose, adquirí los siguientes aprendizajes:

- **Configuración eficiente**: Aprendí a utilizar Docker Compose para definir y configurar servicios de manera estructurada y eficiente, especificando versiones de imágenes y variables de entorno clave.

- **Selección de imágenes**: Utilizar imágenes oficiales (`sonarqube:latest` y `postgres:latest`) garantiza estabilidad y seguridad en las aplicaciones Dockerizadas.

- **Variables de entorno**: Definir correctamente variables como `SONARQUBE_JDBC_URL` y configurarlas para la conexión con PostgreSQL aseguró una integración sin problemas desde el inicio.

- **Networking en Docker**: Manejar redes (`bridge`) en Docker permitió conectar servicios como SonarQube y PostgreSQL de forma segura dentro del entorno Docker.

- **Healthchecks**: Configurar healthchecks para SonarQube y PostgreSQL (`curl` y `pg_isready`) aseguró la monitorización continua de la salud de los contenedores, mejorando la disponibilidad del sistema.

- **Acceso y prueba**: Verificar el acceso a SonarQube mediante `localhost:9000` después de iniciar los contenedores confirmó la correcta configuración y conexión entre servicios.

Esta experiencia fortaleció mi comprensión práctica en DevOps y me preparó mejor para futuras implementaciones utilizando herramientas similares en entornos de desarrollo y producción.
