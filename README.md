# Formulario de solicitud de crédito FINPROP

Página pública del formulario de solicitud. Se abre en el navegador del
solicitante, se completa y devuelve el PDF oficial ya diligenciado.

- No contiene datos de ningún solicitante: el formulario se publica en blanco.
- Se genera desde el esquema de campos de la aplicación de escritorio
  (`npm run publish-form`), no se edita a mano.
- Existe porque iOS abre un archivo HTML local con un origen opaco: los scripts
  corren, pero la página no es un contexto seguro, así que no hay hoja de
  compartir y la descarga no deja archivo. Un iPhone solo puede usarla por esta
  dirección https.
