# Cómo agregar o cambiar fotos en Dulceria

Puedes administrar el catálogo desde GitHub sin instalar programas ni tocar el diseño de la página.

## 1. Subir una fotografía

1. Entra a [la carpeta productos](https://github.com/chocotejas/Dulces/tree/main/productos).
2. Pulsa **Add file → Upload files**.
3. Selecciona o arrastra tus fotografías.
4. Pulsa **Commit changes** para guardarlas.

Usa nombres sencillos, sin espacios ni tildes, por ejemplo chocotejas-manjar.webp. Para que la web cargue rápido en celulares, se recomiendan fotos JPG o WebP, de hasta unos 1000 px en su lado más largo y, de preferencia, menos de 250 KB por imagen.

## 2. Mostrar esa foto en el carrusel

1. Abre [productos.json](https://github.com/chocotejas/Dulces/blob/main/productos.json).
2. Pulsa el lápiz (**Edit this file**).
3. En el producto que deseas cambiar, modifica el valor de imagen por la ruta de tu archivo, por ejemplo:

    "imagen": "productos/chocotejas-manjar.webp"

4. Pulsa **Commit changes**.

La ruta distingue mayúsculas y minúsculas: el nombre debe coincidir exactamente con el archivo que subiste.

## 3. Agregar otro producto

En productos.json, copia un objeto de producto existente y cambia id, nombre, etiqueta, descripcion, imagen, respaldo, alt y mensaje. Separa los objetos con una coma. Conserva las comillas dobles y no pongas una coma después del último objeto.

- **id:** identificador corto y único, por ejemplo chocotejas-coco.
- **nombre:** nombre que verá el cliente.
- **etiqueta:** frase breve sobre el producto.
- **descripcion:** descripción corta.
- **imagen:** ruta de una imagen de la carpeta productos/, o una URL pública.
- **respaldo:** ilustración local que se muestra si la foto no carga.
- **alt:** descripción de la imagen para accesibilidad.
- **mensaje:** texto que se prepara al abrir WhatsApp.

El catálogo no incluye pagos, carrito ni base de datos. Los botones abren WhatsApp para que atiendas tú misma los mensajes.

## Recomendación

Las fotografías actuales son temporales y externas. Sustitúyelas por imágenes propias para la versión definitiva. La página usa HTML, CSS y JavaScript sencillos, sin librerías, anuncios ni servicios de analítica.
