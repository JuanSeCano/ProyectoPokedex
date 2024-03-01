# Pokedex

Este es un proyecto de Pokedex desarrollado utilizando Django, CSS, HTML y JavaScript.

## Descripción

La Pokedex es una aplicación web que te permite explorar una lista de Pokemones. Puedes ver detalles de cada Pokemon, como su nombre, tipo, habilidades y estadísticas.

## Funcionalidades

### Django

- **Modelos:** Se han definido modelos de datos en Django para representar los Pokemones y sus atributos.
- **Vistas:** Se han creado vistas utilizando Django para manejar las solicitudes del usuario y renderizar las plantillas HTML.
- **Plantillas:** Se han diseñado plantillas HTML para mostrar la información de los Pokemones de manera dinámica.
- **Rutas (URLs):** Se han configurado las URLs en Django para dirigir las solicitudes del usuario a las vistas correspondientes.

### HTML y CSS

- **Diseño Responsive:** Se ha implementado un diseño responsive utilizando CSS para garantizar una experiencia de usuario consistente en diferentes dispositivos.
- **Estilo Personalizado:** Se ha aplicado estilo personalizado mediante CSS para mejorar la apariencia de la aplicación y hacerla más atractiva visualmente.

### JavaScript

- **Interactividad:** Se ha utilizado JavaScript para agregar interactividad a la aplicación, como la capacidad de filtrar la lista de Pokemones o realizar búsquedas.
- **Validación de Formularios:** Se han implementado funciones de JavaScript para validar los formularios y mejorar la experiencia del usuario al ingresar datos.

## Instalación y Ejecución

Para instalar y ejecutar este proyecto, sigue los siguientes pasos:

1. **Clonar el Repositorio:** Clona este repositorio en tu máquina local utilizando el comando `git clone [URL del repositorio]`.

2. **Crear y Activar un Entorno Virtual:** Navega al directorio del proyecto y crea un entorno virtual con el comando `python3 -m venv venv`. Luego, activa el entorno virtual:
    - En Windows:
      ```bash
      venv\Scripts\activate
      ```
    - En macOS y Linux:
      ```bash
      source venv/bin/activate
      ```

3. **Instalar Django:** Dentro del entorno virtual, instala Django utilizando el comando `pip install django`.

4. **Instalar Dependencias:** Ejecuta el comando `pip install -r requirements.txt` para instalar todas las dependencias necesarias.

5. **Configurar la Base de Datos:** Ejecuta las migraciones de Django con el comando `python manage.py migrate` para configurar la base de datos.

6. **Iniciar el Servidor:** Utiliza el comando `python manage.py runserver` para iniciar el servidor de desarrollo.

7. **Acceder a la Aplicación:** Abre tu navegador web y visita `http://localhost:8000` para acceder a la Pokedex.

## Contribución

Si deseas contribuir a este proyecto, por favor abre un problema o envía una solicitud de extracción. ¡Tus contribuciones son bienvenidas!

## Autor

[Nombre del autor]

## Licencia

Este proyecto está bajo la Licencia [tipo de licencia]. Para más detalles, consulta el archivo LICENSE.
