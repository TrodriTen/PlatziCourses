# MacOS

## Configuracion ambiente de desarrollo

- **Instalacion IDE:**
  1. Descaragr el zip en la pagina web oficial
  2. Descomprimir
  3. Instalar
  4. No eliminar la carpeta, ponerlo en la barra de tareas (arrastrandolo)
- **Instalacion Homebrew y Nodejs:**
  1. /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  2. brew install node
  3. brew update
  4. node -V
  5. npm -V
- **Crear proyecto Reactjs:**
  1. npx create-react-app "Nombre app"
  2. Instalacion de paquetes
  3. npm start (Iniciar el servidor de reactjs para evidenciar el proyecto)
  4. npm run build (Convertir app en static files)
  5. npm test (Correr los test de la app)