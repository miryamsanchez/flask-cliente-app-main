# Aplicación Flask Cliente

Esta es una aplicación web desarrollada con Flask que te permite mostrar y buscar información de clientes. La aplicación carga datos de clientes desde un archivo CSV y proporciona una interfaz para buscar clientes y ver detalles de cada cliente.

## Requisitos

Antes de ejecutar la aplicación, asegúrate de tener Python instalado en tu sistema. Además, se recomienda utilizar un entorno virtual para evitar conflictos con las dependencias. Sigue los siguientes pasos para configurar el entorno virtual y ejecutar la aplicación:

1. Clona el repositorio desde GitHub:

   git clone https://github.com/Luisaap-dev/flask-cliente-app.git

2. Accede al directorio del proyecto:

   cd flask-cliente-app
   
3. Opcional: Crea y activa un entorno virtual (recomendado):

   python3 -m venv venv
   source venv/bin/activate

4. Instala las dependencias:

   pip install -r requirements.txt


## Uso

Para ejecutar la aplicación, sigue estos pasos:

1. Asegúrate de estar en el directorio del proyecto y de tener el entorno virtual activado (si lo creaste).

2. Ejecuta el siguiente comando:

   python app.py
   
3. Abre un navegador web y ve a la siguiente dirección:

   http://localhost:5000
   
   Esto te llevará a la página principal de la aplicación, donde podrás buscar clientes y ver detalles de cada cliente.

## Estructura del proyecto

El proyecto tiene la siguiente estructura de archivos y directorios:

- `app.py`: El archivo principal de la aplicación que contiene la lógica del servidor Flask.
- `model.py`: El archivo que define la clase `Cliente` y sus métodos para cargar, filtrar y buscar clientes.
- `data/clientes.csv`: El archivo CSV que contiene los datos de los clientes.
- `templates/`: Directorio que contiene las plantillas HTML utilizadas para renderizar las páginas web.
  - `base.html`: Plantilla base que define la estructura común de las páginas.
  - `clientes.html`: Plantilla para mostrar la lista de clientes y la paginación.
  - `detalle_cliente.html`: Plantilla para mostrar los detalles de un cliente específico.
- `static/`: Directorio para archivos estáticos como hojas de estilo CSS, imágenes, etc.

## Contribuciones

Si deseas contribuir a este proyecto, puedes realizar lo siguiente:

- Reportar problemas o errores en la sección de [Issues](https://github.com/TuUsuarioDeGitHub/flask-cliente-app/issues).
- Realizar solicitudes de extracción para mejorar el código o agregar nuevas características.

## Licencia

Este proyecto está bajo la [Licencia MIT](LICENSE).
