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

<div align="center">
![Creación de base de datos](https://raw.githubusercontent.com/ramajoballester/dispocen-gui/main/docs/01.png)
</div>

Una vez creada, se añade el archivo de léxico:

<div align="center">
![Subida archivos léxico](https://raw.githubusercontent.com/ramajoballester/dispocen-gui/main/docs/02.png)
</div>

para el cual se ajustan las cabeceras de las columnas:

<div align="center">
![Ajuste cabeceras léxico](https://raw.githubusercontent.com/ramajoballester/dispocen-gui/main/docs/03.png)
</div>

El archivo sociológico es opcional. Al añadirlo se debe seleccionar la columna correspondiente con los IDs de los participantes, que deben coincidir con los IDs del archivo de léxico:

<div align="center">
![Archivo sociológico](https://raw.githubusercontent.com/ramajoballester/dispocen-gui/main/docs/04.png)
</div>

Para realizar el análisis, se selecciona la base de datos, se ajusta el modelo, filtros y parámetros, y se pulsa el botón "Analizar". Si se ha añadido el archivo sociológico, se podrá realizar el análisis segregando por una de sus variables. Una vez analizado, se pueden visualizar los resultados en forma de tablas y gráficos, así como exportarlos a diferentes formatos para un posterior tratamiento o presentación:

<div align="center">
![Resultados](https://raw.githubusercontent.com/ramajoballester/dispocen-gui/main/docs/05.png)
</div>

<div align="center">
![Gráficos](https://raw.githubusercontent.com/ramajoballester/dispocen-gui/main/docs/06.png)
</div>

