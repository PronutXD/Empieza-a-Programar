# Página de recursos (GitHub Pages)

Página estática: solo `index.html` y `css/style.css`. No necesita PHP ni servidor.

## Antes de subirla
1. Abre `index.html` y busca "Tu nombre aquí" (al final, en el pie de página) para poner tu nombre.
2. Ábrela con doble clic para verla en tu navegador.

## Publicarla en GitHub Pages
1. En github.com, crea un repositorio nuevo, público (por ejemplo `empieza-a-programar`).
2. Sube `index.html` y la carpeta `css/` (botón "Add file" > "Upload files").
3. Ve a Settings > Pages. En "Build and deployment" elige "Deploy from a branch", rama `main`, carpeta `/ (root)`, y guarda.
4. Espera uno o dos minutos. La dirección será:
   https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/
5. Esa dirección es la que va en el código QR y en `config.php` de la presentación (`$url_recursos`).

## Cambiar o agregar videos
Cada video es un bloque `<a href="...">`. Cambia la dirección y el texto. Los enlaces se verificaron
(título, canal e idioma) el 28 de octubre de 2026, pero YouTube puede borrar o mover videos:
revisa que sigan funcionando antes de la charla.
