# Backlog de materiales · Planta Victoria (PVIC)

Página web del seguimiento diario de las líneas de compra del backlog de Mtto Mec Planta.

- **Página:** https://backlogs-planta-victoria.github.io/
- **Datos:** `data/backlog.json`, que sube el macro «Actualizar desde SAP» de `BD_Materiales_Backlog.xlsm` (Config C13) tras la validación del usuario.
- **Protección:** los datos están cifrados (AES-256-CBC; clave = SHA-256 iterado de sal + contraseña). La página pide la contraseña y descifra en el navegador. Sin la contraseña, el archivo es ilegible.
- **No se publican:** proveedor, precios, RUC, texto de cabecera, solicitante ni creado por.

No subir aquí archivos sin cifrar, el Excel, tokens ni contraseñas.
