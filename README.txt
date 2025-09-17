Sitio web de ejemplo (estático) - Catálogo de accesorios

Estructura:
- index.html        -> Página principal, carga products.csv con JavaScript.
- admin.html        -> Panel admin: genera el HTML del catálogo a partir del CSV.
- data/products.csv -> Datos de prueba (5 artículos).
- static/css/...    -> Estilos CSS.
- static/images/... -> Imágenes de prueba.

Uso:
- Abrir index.html directamente en un navegador (de preferencia servir con un servidor web local para evitar problemas de CORS).
- Editar data/products.csv para cambiar/añadir productos.
- En admin.html, presionar "Generar HTML" para obtener el HTML que se puede copiar/pegar manualmente en index.html si se desea hacerlo estático.
