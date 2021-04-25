# SSD Setup
## Change SSD letter to E:

Execute in CMD:

    diskmgmt.msc
Right Click on disk -> Change letter -> E:

## Add ToolBar
- Right click on Windows Tool Bar -> Tool bars -> New Tool bar -> Carpeta de Accesos Directos

## Install Alternate International Keyboard
#### Installation
Execute in CMD:

    E:/SSDSetup/KeyboardLayout/setup.exe

#### Setting as default
Configuración para dejar este teclado por defecto:
Execute in CMD:

    explorer.exe ms-settings:keyboard

Select -> Inglés (Estados Unidos) - United States (International Alternate)
#### Disabling key combination for changing layout:
Execute in CMD:

    explorer.exe ms-settings:keyboard
 Teclas de acceso rápido de idioma de entrada -> Todas las secuencias de teclas deben de ser: (Ninguno)

## Setting path
Execute in CMD as administrator:

    E:/SSDSetup/PathSetup/setup.sh

## Other installations
- Instalacion de Windows Terminal
- Instalación de fuente para VSCode
- Instalar node
- npm install -g neovim
Añadir variable de entorno 
XDG_CONFIG_HOME = E:\Portables\XDG_CONFIG_HOME
PYTHONHOME = E:\Portables\Librerias\WinPython\python-3.8.7.amd64


- Añadir todos los path que correspondan:
Lista actual:
E:\Portables\Programacion\gVimPortable\App\vim\vim80
