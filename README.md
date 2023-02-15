# Proyecto web Django con patrón MTV

Este proyecto incluye las siguientes funcionalidades:

- Herencia HTML en las plantillas
- Tres clases en modelos: Producto, Cliente y Pedido
- Formularios para insertar datos en las clases de modelos
- Formulario de búsqueda en la base de datos

Para probar estas funcionalidades, sigue los siguientes pasos:

1. Clona este repositorio en tu máquina local.
2. Crea un entorno virtual y activa el mismo.
3. Instala los requisitos de la aplicación ejecutando `pip install -r requirements.txt`.
4. Ejecuta las migraciones para crear las tablas de la base de datos: `python manage.py migrate`.
5. Crea un superusuario para acceder al panel de administración: `python manage.py createsuperuser`.
6. Inicia el servidor de desarrollo: `python manage.py runserver`.
7. Prueba las siguientes funcionalidades:

   - Herencia HTML: visita la página principal (http://localhost:8000/) y las páginas de las diferentes secciones del sitio web para comprobar que heredan la estructura HTML de la plantilla base.
   - Clases en
