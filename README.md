# VIORA

Sitio web estático del catálogo VIORA. Incluye navegación adaptable, selector de acabados, grabado ilustrativo y comparación de ediciones.

## Estructura

```text
index.html                 Página principal
assets/css/styles.css      Estilos y diseño adaptable
assets/js/main.js          Acabados, grabado y navegación activa
catalogo-original.html     Catálogo original descargable
.nojekyll                  Publicación estática en GitHub Pages
```

## Vista previa

Abre `index.html` en el navegador. No requiere instalación, dependencias ni compilación.

También puedes servir la carpeta con Python:

```sh
python -m http.server 4173
```

Después abre http://localhost:4173.

## Subir a GitHub

Este repositorio ya tiene configurado `origin` como `https://github.com/Willrdgz/Viora.git`.
Desde esta carpeta:

```sh
git add .
git commit -m "Preparar catálogo VIORA como sitio estático"
git push origin main
```

## Publicación

Para GitHub Pages, configura el repositorio para publicar desde la rama `main` y la carpeta raíz (`/`). La disponibilidad depende de la configuración y el plan del repositorio.

También puedes publicar esta misma carpeta en cualquier alojamiento estático: el directorio de publicación es la raíz del repositorio, el archivo de entrada es `index.html` y no hay comando de compilación.

Los enlaces a CSS, JavaScript y descargas son relativos para admitir publicación en un subdirectorio.

## Edición

- Contenido: `index.html`.
- Diseño y tamaño de la pulsera: `assets/css/styles.css`.
- Ilustración SVG y funciones interactivas: `assets/js/main.js`.

Las ilustraciones son representaciones del proyecto. El precio Premium es propuesto y las especificaciones conservan la indicación de validación pendiente del catálogo.
