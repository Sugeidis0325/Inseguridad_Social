# Inseguridad_Social

## Descripción

La aplicación web **Inseguridad Social** tiene como objetivo permitir a los ciudadanos registrar actividades sospechosas, incidentes o emergencias en su barrio para mejorar la seguridad local. Los usuarios pueden reportar actividades sospechosas, adjuntar fotos y videos como evidencia, y acceder rápidamente a números de emergencia.

La aplicación permite seleccionar hasta 3 barrios y proporciona acceso a un directorio con los números de emergencia locales. Además, incluye grupos de chats por barrios para fomentar la colaboración comunitaria y ayudar a mantener la seguridad.

**Bien sabemos que esta propuesta no es la solución definitiva para erradicar la delincuencia en el país, pero sí representa una buena oportunidad como servicio comunitario para atacar esta problemática.**

## Características

- **Registro de usuario** con máximo 3 barrios.
- **Grupos de Chats** por barrio.
- **Reporte de actividad sospechosa**, incidentes o emergencias con ubicación activa y opción de adjuntar fotos o videos.
- **Directorio telefónico** con números de autoridades competentes (CAI, emergencias).
- **Seguridad de la información** con cifrado y protección de datos.

## Tecnologías utilizadas

- **Frontend**: React (o Angular)
- **Backend**: Java, Spring Boot
- **Base de Datos**: MySQL o MongoDB
- **Infraestructura**: AWS, Google Cloud o Azure
- **Seguridad**: Cifrado de datos, HTTPS, almacenamiento seguro de contraseñas

## Instrucciones de instalación

1. Clona el repositorio:

    ```bash
    git clone https://github.com/Sugeidis0325/Inseguridad_Social.git
    ```

2. Instala las dependencias del frontend:

    ```bash
    cd frontend
    npm install
    ```

3. Instala las dependencias del backend:

    ```bash
    cd backend
    mvn install
    ```

4. Configura las credenciales de la base de datos y las API de emergencia (ver `config/`).

5. Ejecuta el servidor backend:

    ```bash
    mvn spring-boot:run
    ```

6. Ejecuta el frontend:

    ```bash
    npm start
    ```

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir a este proyecto, por favor sigue los siguientes pasos:

1. Haz un fork de este repositorio.
2. Crea una rama con tu funcionalidad: `git checkout -b feature/nueva-funcionalidad`.
3. Realiza tus cambios y haz commit: `git commit -am 'Añadida nueva funcionalidad'`.
4. Sube tus cambios: `git push origin feature/nueva-funcionalidad`.
5. Crea un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.
