# kommi-links

Página pública mínima que redirige los links de invitación de Mesa Kommi
(`?code=XXXXXX`) hacia `kommi://mesa/unirme?code=XXXXXX` dentro de la app.
Existe porque WhatsApp (y la mayoría de apps de chat) no reconoce esquemas
propios como link tocable — solo `http(s)://` — así que este repo público
sirve únicamente para tener un link real `https://` sin exponer el código
fuente de Kommi (que vive en un repo privado aparte).

Publicada con GitHub Pages desde la rama `main`, raíz del repo:
`https://dan-ar5.github.io/kommi-links/?code=XXXXXX`

Si cambia el link de descarga del APK (nuevo build de EAS), hay que
actualizar la constante `LATEST_APK_URL` dentro de `index.html`.
