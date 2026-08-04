# p-bodemall

Material privado de un directorio familiar. El contenido está cifrado en `datos.js`
(AES-256-GCM + PBKDF2-HMAC-SHA256, 200.000 iteraciones) y solo se abre con clave
en `index.html`. Sin la clave no se revela texto, cifras ni nombres.

Los archivos en claro no viven en este repo. Se regenera con
`cifrar_bodemall.py` (fuera del repo, en la carpeta del proyecto local).
