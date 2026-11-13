# Mi primer React

Proyecto básico de **React con Vite**, preparado para practicar los primeros pasos de Programación Orientada al Usuario.

**Autor:** Pan Lijian Wong  
**Universidad:** Universidad Centroamericana José Simeón Cañas (UCA)

## Contenido

- Componente `Saludo` que recibe el nombre mediante props.
- Contador con `useState`: aumentar y reiniciar.
- Estilos CSS adaptables a celular y computadora.
- Configuración de Vite y revisión de código con Oxlint.

## Requisitos

Node.js 22.12 o posterior compatible con Vite y npm. Se recomienda una versión LTS vigente.

## Abrir y ejecutar

1. Descarga el repositorio o clónalo y abre la carpeta en Visual Studio Code.
2. Abre la terminal dentro de la carpeta y ejecuta:

```bash
npm install
npm run dev
```

3. Abre la dirección local que muestra Vite en la terminal.

## Verificar

```bash
npm run lint
npm run build
```

## Archivos principales

| Archivo | Función |
| --- | --- |
| `src/main.jsx` | Monta la aplicación en el elemento `root`. |
| `src/App.jsx` | Pantalla principal y estado del contador. |
| `src/components/Saludo.jsx` | Componente reutilizable con props. |
| `src/App.css` | Estilos de la pantalla. |
| `src/index.css` | Estilos generales. |
| `index.html` | Documento HTML de entrada. |

## Guardar cambios en GitHub

Después de clonar el repositorio, ejecuta estos comandos cuando hayas hecho cambios:

```bash
git add .
git commit -m "Actualizar proyecto de React"
git push origin main
```

`node_modules` y `dist` se excluyen mediante `.gitignore`; las dependencias se instalan con `npm install`.
