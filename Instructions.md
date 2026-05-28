# Como subir esto a GitHub Pages

## Estructura de archivos
```
salimos/
├── index.html
├── style.css
├── script.js
└── music/
    └── cancion.mp3   ← pone aqui tu cancion con ese nombre
```

## Pasos

1. Entra a github.com y crea una cuenta si no tenes
2. Crea un repositorio nuevo, llamalo "salimos" (o lo que quieras)
3. Sube los 3 archivos (index.html, style.css, script.js)
4. Crea una carpeta llamada "music" y sube tu cancion como "cancion.mp3"
5. Ve a Settings → Pages → Source: Deploy from branch → main → / (root) → Save
6. Espera 2 minutos y tu pagina va a estar en: https://tuusuario.github.io/salimos

## Para cambiar los GIFs por tus stickers
En script.js, al principio, esta el array gifStages[].
Reemplaza cada URL por una URL directa a tus GIFs/stickers.
Los stickers webp que me mandaste los podes subir al repo y usar como:
"https://tuusuario.github.io/salimos/sticker_12.webp"
