# Mi primer React

Ejercicio de **Programación Orientada al Usuario**, basado en el [ejemplo de clase del profesor Néstor Aldana](https://github.com/Nexxtor/miPrimerReact).

**Estudiante:** Pan Lijian Wong  
**Universidad:** Universidad Centroamericana José Simeón Cañas (UCA)

## Qué muestra

Una página sencilla con el título **Mi primer sitio React con Vite** y el nombre del estudiante.

El componente `Saludo` recibe el nombre mediante props. Se incluye `src/components/Saludo.jsx` y se utiliza en `App.jsx` para completar la importación del ejemplo de referencia.

## Requisitos

Node.js 22.12 o posterior compatible con Vite y npm. Se recomienda una versión LTS vigente.

## Abrir en Visual Studio Code

1. Descarga o clona este repositorio.
2. Abre la carpeta del proyecto en Visual Studio Code.
3. Abre una terminal dentro de la carpeta y ejecuta:

```bash
npm install
npm run dev
```

4. Abre la dirección local que muestra la terminal.

## Archivos principales

| Archivo | Función |
| --- | --- |
| `src/main.jsx` | Monta `App` dentro del elemento `root`. |
| `src/App.jsx` | Contiene el título e incorpora `Saludo`. |
| `src/components/Saludo.jsx` | Muestra el nombre recibido mediante props. |
| `index.html` | Documento HTML de entrada. |
| `package.json` | Dependencias y comandos del proyecto. |
| `eslint.config.js` | Revisión del código. |

## Comprobar el proyecto

```bash
npm run lint
npm run build
```

## Guardar cambios en GitHub

Después de clonar el repositorio y modificar los archivos:

```bash
git add .
git commit -m "Actualizar mi primer proyecto React"
git push origin main
```

Las carpetas `node_modules` y `dist` se excluyen mediante `.gitignore`.
