# Proyecto CRUD Java con Docker

Este proyecto es un CRUD desarrollado en Java utilizando Spring Boot y una base de datos MariaDB, y se ejecuta en contenedores Docker.

## Integrantes del Equipo

- Albert Uziel Hernandez Mendoza 1 (Carnet: HM20019)
- Leonel Antonio Hernandez Perez 2 (Carnet: HP12002)
- Franklin Giovanny Avila Gonzalez 3 (Carnet: AG22046)

## Instrucciones de Ejecución

1. **Clonar el Repositorio:**

    ```
    git clone <URL_DEL_REPOSITORIO>
    ```

2. **Eliminar Imágenes Previas y Limpiar la Caché:**

    Ejecutar el siguiente comando para eliminar las imágenes previamente creadas y borrar la caché de esas imágenes:

    ```
    docker-compose down --rmi all --remove-orphans             *Solo si tiene contenedor creado
    docker system prune -a -f --volumes
    ```

3. **Ejecutar Docker Compose:**

    Una vez que las imágenes y la caché se hayan limpiado, ejecuta el siguiente comando para correr el proyecto:

    ```
    docker-compose up -d
    ```

Esto iniciará la aplicación Java y la base de datos MariaDB en contenedores Docker.S