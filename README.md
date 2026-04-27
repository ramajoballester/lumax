# DispoCen Graphical User Interface

Interfaz gráfica para DispoCen: software para el análisis de la disponibilidad y centralidad léxica.

## Instalación

La última versión está disponible en la sección de [releases](https://github.com/ramajoballester/lumax/releases), o directamente en los siguientes enlaces:

<!-- o [.msi](https://github.com/ramajoballester/lumax/releases/latest/download/lumax_x64_en-US.msi) -->
- [Windows](https://github.com/ramajoballester/dispocen-gui/releases/latest/download/DispoCen.GUI_x64_setup.exe)
- [macOS (Apple Silicon)](https://github.com/ramajoballester/dispocen-gui/releases/latest/download/DispoCen.GUI_aarch64.dmg)
- [Linux Debian/Ubuntu](https://github.com/ramajoballester/dispocen-gui/releases/latest/download/DispoCen.GUI_amd64.deb)
- [Linux Fedora/openSUSE/RHEL](https://github.com/ramajoballester/dispocen-gui/releases/latest/download/DispoCen.GUI_x86_64.rpm)
- [Linux portable](https://github.com/ramajoballester/dispocen-gui/releases/latest/download/DispoCen.GUI_amd64.AppImage)


## Ejemplo de uso

El primer paso para llevar a cabo los análisis es crear una base de datos:

<p align="center">
    <img src="https://raw.githubusercontent.com/ramajoballester/dispocen-gui/main/docs/01.png" alt="Creación de base de datos" width="800">
</p>

Una vez creada, se añade el archivo de léxico:

<p align="center">
    <img src="https://raw.githubusercontent.com/ramajoballester/dispocen-gui/main/docs/02.png" alt="Subida archivos léxico" width="800">
</p>

para el cual se ajustan las cabeceras de las columnas:

<p align="center">
    <img src="https://raw.githubusercontent.com/ramajoballester/dispocen-gui/main/docs/03.png" alt="Ajuste cabeceras léxico" width="800">
</p>

El archivo sociológico es opcional. Al añadirlo se debe seleccionar la columna correspondiente con los IDs de los participantes, que deben coincidir con los IDs del archivo de léxico:

<p align="center">
    <img src="https://raw.githubusercontent.com/ramajoballester/dispocen-gui/main/docs/04.png" alt="Archivo sociológico" width="800">
</p>

Para realizar el análisis, se selecciona la base de datos, se ajusta el modelo, filtros y parámetros, y se pulsa el botón "Analizar". Si se ha añadido el archivo sociológico, se podrá realizar el análisis segregando por una de sus variables. Una vez analizado, se pueden visualizar los resultados en forma de tablas y gráficos, así como exportarlos a diferentes formatos para un posterior tratamiento o presentación:

<p align="center">
    <img src="https://raw.githubusercontent.com/ramajoballester/dispocen-gui/main/docs/05.png" alt="Resultados" width="800">
</p>

<p align="center">
    <img src="https://raw.githubusercontent.com/ramajoballester/dispocen-gui/main/docs/06.png" alt="Gráficos" width="800">
</p>

