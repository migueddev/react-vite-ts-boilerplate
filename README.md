# Plantilla Base para Proyectos en React con Vite y TypeScript

Este repositorio es una plantilla base para proyectos de React utilizando Vite y TypeScript. Incluye herramientas de linting, formateo de código y control de versiones para garantizar las mejores prácticas de desarrollo.

## Características

- **React 18+**: Biblioteca para construir interfaces de usuario.
- **TypeScript 5+**: Tipado estático para JavaScript.
- **Vite**: Herramienta de desarrollo rápida para proyectos modernos.
- **Prettier**: Formateo consistente del código.
- **ESLint**: Linter para mantener un código limpio.
- **Husky**: Hooks de Git para automatizar tareas.
- **Commitlint**: Verifica que los mensajes de commit sigan las convenciones.
- **Standard-Version**: Generación automática de versiones y changelogs.

## Instalación

Sigue estos pasos para configurar el proyecto:

1. Clona el repositorio:

   ```bash
   git clone https://github.com/migueddev/react-vite-ts-boilerplate.git
   cd react-vite-ts-boilerplate
   ```

2. Instala las dependencias

   ```bash
   npm install
   ```

## Scripts

A continuación, se detalla la funcionalidad de los scripts incluidos en el archivo `package.json`:

### **Desarrollo y Construcción**

- **`npm run dev`**:
  Inicia el servidor de desarrollo con Vite. Utiliza este comando para trabajar en el proyecto en un entorno local.

- **`npm run build`**:
  Genera la versión optimizada para producción.

  - Primero, compila los archivos TypeScript (`tsc -b`).
  - Luego, ejecuta el proceso de construcción con Vite (`vite build`).

- **`npm run preview`**:
  Sirve la versión generada con `build` en un servidor local para realizar pruebas.

### **Calidad del Código**

- **`npm run lint`**:
  Ejecuta ESLint para buscar y corregir errores en los archivos JavaScript, TypeScript, JSX y TSX.

  - Opción `--fix`: Intenta corregir automáticamente los problemas detectados.

- **`npm run prettier`**:
  Aplica Prettier para formatear todo el código del proyecto.

  - Opción `--write`: Sobrescribe los archivos con el formato adecuado.

- **`npm run commit:pre`**:
  Ejecuta Prettier y ESLint antes de hacer un commit, asegurando que el código esté limpio y formateado correctamente.

### **Versionado**

- **`npm run release`**:
  Genera una nueva versión del proyecto utilizando `standard-version`. El nivel de versión (patch, minor o major) se determina automáticamente en base a los mensajes de commit.

- **`npm run release:patch`**:
  Genera una nueva versión incrementando el nivel **patch** (arreglos menores o sin romper compatibilidad).

- **`npm run release:minor`**:
  Genera una nueva versión incrementando el nivel **minor** (nueva funcionalidad que no rompe compatibilidad).

- **`npm run release:major`**:
  Genera una nueva versión incrementando el nivel **major** (cambios que rompen compatibilidad).

### **Otros Scripts**

- **`npm run prepare`**:
  Configura los hooks de Husky automáticamente al ejecutar `npm install`.

- **`npm run commitlint`**:
  Verifica que el mensaje de commit siga las convenciones definidas por Commitlint.

### **Uso General**

- Para iniciar el desarrollo:

  ```bash
  npm run dev
  ```

## Contacto

Conéctate conmigo en:

- [LinkedIn](https://www.linkedin.com/in/miguel-duran-romero/)
- [GitHub](https://github.com/migueddev)

## Licencia

Este proyecto está licenciado bajo la Licencia ISC.
Consulta el archivo [LICENSE](./LICENSE)
