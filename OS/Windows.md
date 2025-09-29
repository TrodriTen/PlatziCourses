# Windows

## Configuracion de ambiente de desarrollo

- **Instalacion de un Navegador:**
  + En estos casos el mejor es google chrome
- **Visualizar sitios web por medio de conexiones:**
   + HTTP/HTTPS
- **Este soporta lenguajes de programacion como:**
   + JavaScript: Funcionalidades, acciones y demas logica que implementa el sitio web en cuestion
   + CSS: Parte grafica y de decoracion del HTML 
   + HTML: Estructura universal de los sitios web
- **Tipos de Google Chrome:**
   + Stable: Version sin errores
   + Dev: Version con nuevas funcionalidades proximas a salir al mercado
   + Canary: Version experimental con demasiados errores
- **DevTools de Chrome:**
   + LightHouse: Es una extension que indica la calidad y optimizacion de un sitio web
   + DevTools: Se usa para ver la estructura interna (HTML) de un sitio web, tambien tiene herramientas de red.
- **Instalacion IDE:**
   + Un IDE es un Editor de codigo como: Descaragar el instalador en la pagina oficial de cada IDE
      * VsCode
      * Eclipse
      * Nano
      * Atom
      * Etc.
- **Extensiones de VsCode:**
   + Ofrecen personalizacion al IDE
   + Tienen las herramientas de desarrollo necesarias para casi cualquier lenguaje (Node Require - Modulos de Node faltantes en un archivo de JS)
- **Windows Subsystem for Linux:**
   + Permite tener el Kernel de Linux en Windows
   + Todos los desarrollos se llevan a cabo en MAC o Linux
   + Windows esta encaminado a diseño grafico
- **Configuracion de Windows para soportar WSL:**
  + Instalar PowerShell
  + Instalar WSL:
    * wsl --install
  + Instalacion VirtualBox(Si falla WSL)
    * Este permite instalar maquinas virtuales (VM) en un computador.
    * Servidores utilizan esto con el fin de soportar gran cantidad de VM
    * Servidores son mantenibles
    * Pasos:
      1. Descargar VirtualBox de web
      2. Descargar Imagen ISO de la distribucion de Linux preferida
      3. Crear VM con oracle junto con la imagen ISO
      4. Setear los recursos a la VM
      5. Instalar lo necesario en la VM
      6. Setting parte superior se paga la VM
- **Instalacion Nodejs:**
  1. sudo apt-get update (Este paso siempre hacerlo antes de instalar algo, este actualiza las librerias linux del sistema)
  2. sudo apt install nodejs
  3. node -V
  4. sudo apt install npm (NPM manejador de paquetes de Node)
  5. sudo n latest
- **Instalacion Python:**
  1. sudo apt-get update
  2. sudo install software-properties-common
  3. sudo add-apt-repository pp:deadsnakes/ppa (actualiar lanzamiento repos recientes)
  4. sudo apt-get update
  5. sudo apt install python."version"
  6. python o python3 --version
- **Instalacion Git:**
  1. sudo apt-get update
  2. sudo apt-get install git-all
  3. git version