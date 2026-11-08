# MRD Portfolio

Portfolio personal estático en HTML, CSS y JavaScript. Compatible con GitHub Pages.

## Estructura

```text
MRD-Portfolio/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    └── images/
        ├── pirineos.jpg    (añadir tu foto)
        ├── portugal.jpg    (añadir tu foto)
        ├── viaje-1.jpg     (añadir tu foto)
        └── viaje-2.jpg     (añadir tu foto)
```

Las fotografías no están incluidas: la web muestra tarjetas decorativas hasta que las añadas.

## Publicación en GitHub Pages

1. Entra en tu repositorio `mrd-prueba` (o crea uno nuevo).
2. Sube **el contenido** de esta carpeta a la raíz del repositorio: `index.html`, `styles.css`, `script.js` y `assets/`. No subas solamente el ZIP.
3. En GitHub abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**; selecciona `main` y `/ (root)`; guarda.
5. Visita `https://moradtest.github.io/mrd-prueba/` si mantienes esos nombres. Si cambias el usuario o repositorio, la URL también cambia.

## Añadir tus fotos

1. Crea la carpeta `assets/images/` en el repositorio si no existe.
2. Sube tus propias fotografías con los nombres exactos `pirineos.jpg`, `portugal.jpg`, `viaje-1.jpg`, `viaje-2.jpg`.
3. Para cambiar títulos o descripciones, edita los elementos `<figure>` en `index.html`.
4. Si usas otros nombres o extensiones (`.png`, `.webp`), modifica también las rutas `src` en `index.html`.
5. Guarda con **Commit changes** y espera unos minutos a que GitHub Pages publique.

## Personalizar

- **Presentación y textos:** `index.html`
- **Colores y diseño:** variables CSS al inicio de `styles.css`
- **Interacciones:** `script.js`
- **GitHub:** reemplaza `https://github.com/Moradtest` si cambias tu nombre de usuario.

## Nota

Este portfolio no ejecuta scripts remotos ni administra extensiones. MRD AutoScripts es por ahora una tarjeta de proyecto.
