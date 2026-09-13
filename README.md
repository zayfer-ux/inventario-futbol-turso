# Inventario de equipos de fútbol

Este proyecto consiste en una base de datos sencilla para registrar un inventario de equipos y materiales de fútbol. La base de datos se encuentra en Turso y se administra mediante un cuaderno de Google Colab.

## Funciones del proyecto

El proyecto está dividido en las cuatro operaciones CRUD:

- **Create:** agregar nuevos equipos al inventario.
- **Read:** consultar todos los equipos registrados.
- **Update:** modificar la cantidad y el estado de un equipo.
- **Delete:** eliminar un equipo mediante su ID.

## Datos registrados

Cada registro contiene la siguiente información:

- ID
- Nombre del equipo o material
- Cantidad disponible
- Estado

## Tecnologías utilizadas

- Python
- Google Colab
- Turso
- SQL
- GitHub

## Cómo utilizar el proyecto

1. Abrir el archivo `Inventario_futbol.ipynb`.
2. Presionar el botón **Open in Colab**.
3. Ejecutar la celda para instalar `turso_serverless`.
4. Ejecutar la celda de conexión.
5. Introducir un token válido de Turso.
6. Ejecutar la celda para crear la tabla.
7. Probar las operaciones Create, Read, Update y Delete.

## Seguridad

El token de Turso no está incluido en el proyecto. Para conectarse a la base de datos, cada usuario debe introducir un token válido cuando Google Colab lo solicite.
