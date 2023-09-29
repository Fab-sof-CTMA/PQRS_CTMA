# PQRS_CTMA
# Proyecto de osTicket para el SENA
Este proyecto de osTicket está diseñado para el Servicio Nacional de Aprendizaje (SENA) y tiene como objetivo mejorar la gestión de solicitudes y el soporte al cliente dentro de la organización.



![img1](https://github.com/Fab-sof-CTMA/PQRS_CTMA/assets/146457965/d5dddea9-48d9-4423-921b-8643c83e207f)


## Requisitos

Antes de comenzar con la instalación de osTicket, asegúrate de contar con los siguientes requisitos:

- Servidor web compatible (por ejemplo, Apache o Nginx).
- Servidor de base de datos (por ejemplo, MySQL o PostgreSQL).
- PHP 7.2 o superior.
- Extensiones PHP: mysqli, gd, json, zlib.
- Servidor de correo electrónico (SMTP) para notificaciones por correo electrónico.

## Instalación

Sigue estos pasos para instalar osTicket en el entorno del SENA:

1. Descarga la última versión de osTicket desde [el sitio web oficial](https://osticket.com/download/).

2. Descomprime el archivo descargado en el servidor web del SENA.

3. Crea una base de datos MySQL y un usuario con permisos de lectura y escritura para osTicket.

4. Renombra el archivo `include/ost-sampleconfig.php` a `include/ost-config.php` y configura las opciones de la base de datos y correo electrónico en este archivo.

5. Abre tu navegador y accede a la URL donde has instalado osTicket.

6. Sigue el asistente de instalación para configurar osTicket de acuerdo con las necesidades del SENA.

## Uso

Una vez que hayas instalado osTicket, podrás utilizarlo para gestionar solicitudes y ofrecer soporte al cliente dentro del SENA. Algunas acciones comunes incluyen:

- Crear y gestionar tickets de soporte.
- Configurar departamentos de atención.
- Asignar tareas a agentes específicos.
- Personalizar formularios y campos según las necesidades del SENA.
- Configurar notificaciones por correo electrónico.

Para obtener más detalles sobre el uso de osTicket, consulta la documentación oficial de osTicket o comunícate con el equipo de soporte interno del SENA.

## Contribución

Si eres parte del equipo de desarrollo o soporte del SENA y deseas contribuir al proyecto de osTicket, sigue estos pasos:

1. Clona el repositorio de osTicket desde [GitHub](https://github.com/osTicket/osTicket).

2. Realiza tus modificaciones y mejoras siguiendo las pautas internas del SENA.

3. Envía una solicitud de extracción (PR) con tus cambios.

4. Asegúrate de seguir las directrices de contribución establecidas por el SENA y el proyecto osTicket.

## Licencia

Este proyecto de osTicket se distribuye bajo la licencia [GPL 2.0](https://www.gnu.org/licenses/gpl-2.0.html). Asegúrate de cumplir con los términos de esta licencia.

## Créditos

Este proyecto de osTicket para el SENA fue implementado y configurado por el equipo de practicantes en desarrollo de programacion del CTMA. Agradecemos a todos los miembros del equipo por sus contribuciones.




