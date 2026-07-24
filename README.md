# corporacion-grupo-tacsa (sitio estático - starter)

Estructura mínima:
- index.html
- css/style.css
- js/main.js
- pages/*.html
- assets/ (imágenes, fuentes, etc)

Cómo previsualizar localmente:
- Python 3: `python -m http.server 8000` y abrir http://localhost:8000
- Node: `npx serve` o usar cualquier servidor estático

Cómo subir a GitHub y activar GitHub Pages:
1. Crea una cuenta en https://github.com si no la tienes.
2. Crea un nuevo repositorio, por ejemplo `corporacion-grupo-tacsa`.
3. Sube los archivos y carpetas (sube el contenido, no el ZIP):
   - index.html
   - css/
   - js/
   - assets/
   - pages/
4. En el repositorio, ve a Settings → Pages, selecciona "Deploy from a branch", elige la rama `main` y la carpeta `/` y guarda.
5. Tras unos minutos, el sitio estará disponible en:
   `https://<tu-usuario>.github.io/corporacion-grupo-tacsa`

Sustituye los textos, logos y correos por los reales antes de publicar.
