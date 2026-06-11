CATÁLOGO REFACCIONES DELIVERY V4

Archivos:
- index.html: página principal.
- productos.json: productos exportados desde PRODUCTOS.xlsx.
- logo-delivery.jpg: logo.
- imagenes/: fotos de productos destacados.

Esta versión NO usa IA.
Está preparada para conectar Google Sheets publicado como CSV.

Para conectar Google Sheets:
1. Sube PRODUCTOS.xlsx a Google Drive.
2. Ábrelo como Google Sheets.
3. Asegúrate de tener columnas: clave, producto, descripcion, categoria, unidad, precio, imagen, destacado, activo.
4. Archivo > Compartir > Publicar en la web > Hoja actual > CSV.
5. Copia el link CSV.
6. En index.html busca: const SHEET_CSV_URL='';
7. Pega el link entre las comillas.
8. Sube index.html a GitHub y haz commit.

Para imágenes:
- Sube fotos a Google Drive y hazlas públicas.
- Copia el enlace directo o URL pública en la columna imagen.
- Para destacar un producto, escribe SI en la columna destacado.
- Para ocultar un producto, escribe NO en la columna activo.

Contacto configurado:
WhatsApp: 618 309 8635
Correo: refaccionesdelivery@gmail.com
Precios: Solo cotizar.
