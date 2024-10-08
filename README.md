📂 USB Auto-Copy Script

Este script en Python detecta automáticamente cuando se conecta una unidad de almacenamiento extraíble (como USB o SD) y copia los archivos más recientes (del día actual) a una carpeta en tu escritorio. ¡Es ideal para fotógrafos, editores o cualquier persona que trabaje con archivos desde unidades externas!
🚀 Características

    Detecta automáticamente las unidades USB o SD conectadas.
    Copia solo los archivos creados o modificados en el día actual.
    Crea una carpeta en el escritorio con el nombre Archivos_FechaHoraActual para organizar los archivos.

📦 Requisitos

    Python 3.x
    Las siguientes bibliotecas de Python:

    bash

    pip install psutil watchdog

📖 Instrucciones (Español)
1. Clonar el repositorio

bash

git clone https://github.com/tu-usuario/usb-auto-copy-script.git
cd usb-auto-copy-script

2. Ejecutar el script

Puedes ejecutar el script en un entorno local o Jupyter. Asegúrate de que las bibliotecas necesarias estén instaladas y luego ejecuta:

bash

python auto_copy_usb.py

El script comenzará a monitorear la conexión de nuevas unidades de almacenamiento y copiará los archivos más recientes (del día actual) cuando se detecte una nueva unidad.

📖 Instructions (English)
1. Clone the repository
2. Run the script

You can run the script in a local environment or Jupyter. Make sure the necessary libraries are installed and then run:

bash

python auto_copy_usb.py

The script will start monitoring for newly connected storage devices and will copy the most recent files (from the current day) when a new drive is detected.
