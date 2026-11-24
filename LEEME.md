# Publicar los enlaces de La Purísima

Copia el contenido de esta carpeta al repositorio del sitio de usuario `300Ech.github.io`. El archivo `assetlinks.json` debe publicarse en `https://300ech.github.io/.well-known/assetlinks.json`; un sitio de proyecto no puede servirlo en la raíz del dominio.

Reemplaza `REEMPLAZAR_CON_SHA256_DE_LA_CLAVE_DE_FIRMA` por la huella SHA-256 que aparece en Play Console > Integridad de la app.

Además quedan publicados:

- `https://300ech.github.io/app-ads.txt`, que AdMob revisa. En Play Console pon `https://300ech.github.io` como sitio web del desarrollador.
- `https://300ech.github.io/privacidad.html`, la política de privacidad que va en Play Console > Contenido de la app.

Mientras el dominio no esté verificado, el enlace abrirá la página web. Su botón «Abrir en la app» intenta abrir La Purísima y, si no está instalada, lleva a Google Play.
