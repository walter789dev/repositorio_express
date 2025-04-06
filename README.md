# Servidor Express para Aplicación React

Este repositorio contiene un servidor Express simple para desplegar una aplicación React. El servidor está configurado para servir los archivos estáticos generados durante el proceso de build de React.

## Requisitos previos

- Node.js (versión recomendada: 14.x o superior)
- npm (incluido con Node.js)
- Una aplicación React con un build generado en la carpeta `dist`

## Estructura de carpetas

```
proyecto-raíz/
├── dist/               # Build de React generado
│   ├── index.html
│   ├── assets/
│   └── ...
└── servidor/           # Carpeta del servidor Express
    ├── node_modules/
    ├── package.json
    └── server.js
```

## Ejecución del servidor

1. Asegúrate de estar en la carpeta `servidor`:
   ```
   cd servidor
   ```

2. Ejecuta el servidor:
   ```
   node server.js
   ```

3. Abre un navegador y accede a [http://localhost:3000](http://localhost:3000). Deberías ver tu aplicación React funcionando.
