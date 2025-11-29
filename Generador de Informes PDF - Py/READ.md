🏥 Generador de Informes PDF - Sistema de Gestión Hospitalaria



📋 Descripción del Proyecto
"Generador de Informes PDF - Py" es una aplicación de escritorio desarrollada en total e integramente en Python que permite consultar, gestionar y exportar información de médicos y citas de un hospital a documentos PDF. El sistema ofrece una interfaz gráfica intuitiva para visualizar datos almacenados en una base de datos MySQL y generar informes personalizados e interactiva para el usuario según las necesidades del mismo.


✨ Características Principales del Proyecto
  ◈ Visualización de datos  (🔍): Interfaz gráfica con tabla interactiva que muestra médicos y sus citas asociadas/correspondientes.
  ◈ Exportación a PDF       (📄): Generación de informes profesionales en formato "PDF".
  ◈ Filtrado flexible       (🎯): Opciones de exportación para exportar todos y cada uno de los datos o médicos específicos.
  ◈ Organización automática (📁): Reconocimiento del "SO" y creación automática de carpeta para almacenar informes.
  ◈ Diseño moderno          (🎨): Interfaz gráfica con "Tkinter" y diseño "responsive".
  ◈ Consultas optimizadas   (🔄): Uso de sentencias "(LEFT) JOIN" para relacionar información de 'MEDICOS' y 'CITAS' y uso de "ORDER BY" para ordenar los datos obtenidos recuperados de la "DB", de la base de datos.


✨ Estructura del Proyecto
  ◊ Antes de Ejecutar (previo a la ejecución):
      Generador de Informes PDF - Py/
      │
      ├── Script DB - SQL/
      │   └── hospitalCitas.sql # Script de creación de base de datos.
      │
      ├── venv/                 # Entorno virtual de Python (opcional).
      │   ├── .../
      │   └── ...
      │
      ├── db_connection.py      # Módulo de conexión a MySQL.
      ├── export_pdf.py         # Módulo de exportación a PDF.
      └── main.py               # Interfaz gráfica principal.

  ◊ Antes de Ejecutar (previo a la ejecución):
      Generador de Informes PDF - Py/
      │
      ├── __pycache__/                              # Archivos compilados de Python auto-generados (autogeneración).
      │   ├── db_connection.cpython-313.pyc
      │   └── export_pdf.cpython-313.pyc
      │
      ├── Informes_PDF/                             # Carpeta de informes exportados.
      │   ├── informe_medicos_citas_completo.pdf
      │   ├── informe_medico_MED-010.pdf
      │   └── informe_medicos_MED-001_a_MED-005.pdf
      │
      ├── Script DB - SQL/
      │   └── hospitalCitas.sql                     # Script de creación de base de datos.
      │
      ├── venv/                                     # Entorno virtual de Python (opcional)
      │   ├── .../
      │   └── ...
      │
      ├── db_connection.py                          # Módulo de conexión a MySQL
      ├── export_pdf.py                             # Módulo de exportación a PDF
      └── main.py                                   # Interfaz gráfica principal


🛠️ Tecnologías Utilizadas
  ◆ Backend
    ◇ Python 3.13             - Lenguaje de programación principal.
    ◇ MySQL 8.0+              - Sistema de gestión de base de datos.
    ◇ MySQL Connector/Python  - Conector para Python-MySQL.

  ◆ Frontend
    ◇ Tkinter                 - Biblioteca para interfaz gráfica.
    ◇ ttk                     - Widgets temáticos de Tkinter.

  ◆ Librerías de Datos
    ◇ Pandas                  - Manipulación y análisis de datos.
    ◇ ReportLab               - Generación de documentos PDF.

  ◆ Base de Datos
    ◇ MySQL Workbench         - Herramienta de administración (opcional).


📦 Requisitos Previos
  ◆ Software Necesario
    1. Python 3.10 o superior.
      ▫ Descarga: python.org      ↦ (https://www.python.org/downloads/)
      ▫ Verificar instalación     ↦ python --version (EJECUTAR en la Terminal o Windows PowerShell)

    2. MySQL Server 8.0 o superior
      ▫ Descarga: mysql.com       ↦ (https://dev.mysql.com/downloads/mysql/)
      ▫ Verificar instalación     ↦ mysql --version (EJECUTAR en la Terminal o Windows PowerShell)

    3. MySQL Workbench (Opcional, pero recomendado)
      ▫ Descarga: MySQL Workbench ↦ (https://dev.mysql.com/downloads/workbench/)

  ◆ Librerías de Python (EJECUTAR en la Terminal o Windows PowerShell) [+Recomendable]
    ▫ pip install mysql-connector-python
    ▫ pip install pandas
    ▫ pip install reportlab

  ◆ Librerías de Python (EJECUTAR en la Terminal o Windows PowerShell) [-Recomendable]
    ▫ pip install -r requirements.txt
    ◇ Contenido de ("requirements.txt"):
      ▫ mysql-connector-python==8.0.33
      ▫ pandas==2.0.3
      ▫ reportlab==4.0.4


⚙️ Configuración e Instalación
  1. Paso 1: Clonar o Descargar el Proyecto
  # Si usas Git
    git clone https://github.com/tu-usuario/generador-informes-pdf.git
    cd generador-informes-pdf

  # O descarga el ZIP y extrae
