# kommi-links

Página pública mínima que redirige los links de invitación de Mesa Kommi
(`?code=XXXXXX`) hacia `kommi://mesa/unirme?code=XXXXXX` dentro de la app.
Existe porque WhatsApp (y la mayoría de apps de chat) no reconoce esquemas
propios como link tocable — solo `http(s)://` — así que este repo público
sirve únicamente para tener un link real `https://` sin exponer el código
fuente de Kommi (que vive en un repo privado aparte).

Publicada con GitHub Pages desde la rama `main`, raíz del repo:
`https://dan-ar5.github.io/kommi-links/?code=XXXXXX`

El botón de descarga lleva a Google Play (Android) o a la App Store
(iPhone) según el celular. Los links son fijos (`PLAY_STORE_URL` y
`APP_STORE_URL` dentro de `index.html`) y solo hay que cambiarlos si cambia
la ficha de la app en alguna tienda.

## Descarga (QR de los stickers)

`https://dan-ar5.github.io/kommi-links/descargar/` lleva directo a Google
Play en Android y a la App Store en iPhone; en computadora muestra los dos
botones. Es el link del QR que va en los stickers de las comidas. Tiene su
propia copia de `PLAY_STORE_URL` y `APP_STORE_URL`: si cambia un link, hay
que cambiarlo en `index.html`, en `descargar/index.html` y en
`src/constants/app.ts` del proyecto.
