# TaskMaster

# Título
Esto es TaskMaster, una aplicación diseñada para facilitar la gestión de tareas tanto personales como en equipo. 
Optimiza tu productividad con esta plataforma eficiente y sencilla.



# Índice
1. [Acerca del Proyecto](#acerca-del-proyecto)
2. [Instalación](#instalación)
3. [Cómo Usar](#cómo-usar)
4. [Características](#características)
5. [Colaboración](#colaboración)
6. [Licencia](#licencia)
7. [Requisitos](#requisitos)
8. [Recursos](#recursos)



# Acerca del Proyecto
TaskMaster es una herramienta web desarrollada con **Django** que proporciona:

- Creación y gestión de tareas tanto individuales como grupales.
- Asignación de tareas a diferentes miembros del equipo.
- Monitoreo del progreso a través de una interfaz intuitiva.
- Sincronización en la nube para acceso en tiempo real.

Perfecta para equipos que necesitan un sistema ágil para la administración de proyectos.



# Instalación
Sigue estos pasos para instalar TaskMaster en tu sistema:

```bash
# Clonar el repositorio
git clone https://github.com/usuario/taskmaster.git
cd taskmaster

# Crear y activar un entorno virtual
python -m venv venv
source venv/bin/activate  # En Windows usa: venv\Scripts\activate

# Instalar dependencias
pip install -r requirements.txt

# Configurar la base de datos
python manage.py migrate

# Ejecutar el servidor
python manage.py runserver
```



# Cómo Usar
1. Regístrate o inicia sesión.
2. Crea y organiza proyectos.
3. Asigna tareas y supervisa su evolución.
4. Mantente al día con el progreso a través del panel de control.



# Características
- [x] Creación y asignación de tareas.
- [x] Integración con servicios externos.
- [ ] Sistema de notificaciones en tiempo real.
- [ ] Versión móvil en desarrollo.



# Colaboración
¿Quieres ayudar a mejorar TaskMaster? Sigue estos pasos:
1. Haz un **fork** del repositorio.
2. Crea una nueva rama (`git checkout -b mejora-feature`).
3. Realiza los cambios y confírmalos (`git commit -m "Mejorar nueva funcionalidad"`).
4. Envía los cambios (`git push origin mejora-feature`).
5. Abre un **pull request** en GitHub.


# Licencia
Este proyecto está bajo la Licencia MIT.


# Dependencias
|-----------------------------------------------------------------------------|
|  Dependencia  |  Versión  |                    Descripción                  |
|---------------|-----------|-------------------------------------------------|
| Django        |   4.2.0   | Framework principal para el desarrollo web      |
| django-filter |   23.1    | Filtros avanzads para consultas en APIs REST    |
| Pillow        |   10.0.0  | Biblioteca para el manejo de imágenes en python |
| pytest        |   74.2    | Herramienta para realizar pruebas automatizadas |
| PostgreSQL    |   15.1    | Sistema de gestion de base de datos             |
| psycopg2      |   2.0.9   | Conector de base de datos para PostgreSQL       |
| Bootstrap     |   5.3     | Framework secundario para el desarrollo web     |
-------------------------------------------------------------------------------


# Recursos
- [Repositorio GitHub](https://github.com/marcoscantos/TaskMaster/blob/main/README.md?plain=1)
- [Documentación Django](https://docs.djangoproject.com/en/5.1/releases/4.2/)
