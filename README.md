# Gestión de Estudiantes Python Basic

[![Estado](https://img.shields.io/badge/estado-activo-brightgreen)](https://github.com/DaniDevGS/student-management_python-basic)
[![Licencia](https://img.shields.io/badge/licencia-CC_BY--ND_4.0-lightgrey)](https://creativecommons.org/licenses/by-nd/4.0/)
[![Python](https://img.shields.io/badge/Python-3.6%2B-blue?logo=python)](https://python.org)
[![Tecnología](https://img.shields.io/badge/Tecnología-CLI%20&%20JSON-yellow)](https://github.com/DaniDevGS/student-management_python-basic)
[![Code Style](https://img.shields.io/badge/code%20style-PEP8-brightgreen)](https://pep8.org)

![Captura de pantalla del sistema StudentFlow en la terminal](https://images.unsplash.com/photo-1624953587687-daf255b6b80a?fm=jpg&q=60&w=800&h=400&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8cHl0aG9uJTIwcHJvZ3JhbW1pbmd8ZW58MHx8MHx8fDA%3D)

<br>

Sistema de gestión académica basica: es un sistema de gestión académica **básico y ligero**, desarrollado completamente en **Python**. Está diseñado para la terminal (CLI) y permite a los **estudiantes** registrar sus datos de forma sencilla, mientras que a los **administradores** les ofrece una vista completa y la gestión de la información.

## ✨ Funcionalidades Destacadas

- Interfaz de línea de comandos con colores (usando Colorama)
- Validación de datos integrada
- Persistencia de datos mediante archivos JSON
- Diseño colorido y amigable para terminal
- Gestión de estudiantes y administradores

## 🛠️ Tecnologías Utilizadas

<!-- [![My Skills](https://skillicons.dev/icons?i=python)](https://github.com/DaniDevGS/computer-academy_frontend-project) -->

* **Python:** Versión 3.6+ 
* **Colorama:** Utilizada para añadir colores y estilos a la interfaz de terminal.
* **JSON:** Empleado como sistema de base de datos para la persistencia de datos.


## ⚙️ Requisitos Previos

- Python 3.6 o superior
- pip (gestor de paquetes de Python)

## 🚀 Instalación y Ejecución

1. Clona el repositorio:
```bash
git clone https://github.com/DaniDevGS/student-management_python-basic
cd student-management_python-basic
```

2. Instala dependencias:
```bash
pip install -r requirements.txt
```

## 🚀 Ejecucion

1. Abrir terminal:
```bash
python main.py
```

### 🔑 Credenciales de Prueba (Modo Administrador)

Para acceder a las funciones avanzadas del menú de administrador, el sistema requiere una contraseña.

```bash
Administrador:	admin123

```


⚠️ Nota: Esta es una credencial de prueba para el desarrollo. ¡Cámbiala en producción!
##  Estructura del proyecto
```bash
student-management_python-basic/
├── utils/
│   ├── components/
│   │   ├── statistics/ # Lógica de estadísticas o reportes
│   │   │   └── stats.py
│   │   └── universitys.py # Datos o lógica específica de universidad
│   ├── database/
│   │   └── json.py # Módulo para el manejo de archivos JSON
│   └── menu.py # Módulo para la gestión del menú de la CLI
├── estudiantes.json # Almacén de datos
├── main.py # Punto de entrada principal de la aplicación
└── requirements.txt
```
