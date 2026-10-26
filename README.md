# Dulceria — catálogo de dulces

Sitio estático para mostrar chocotejas, trufas y alfajores y llevar a los visitantes directamente a WhatsApp. No tiene carrito ni pagos en línea.

## Publicar con GitHub Pages

1. Abre **Settings → Pages** en este repositorio.
2. En **Build and deployment**, selecciona **GitHub Actions** como fuente si aún no está configurada.
3. Cada cambio en la rama `main` ejecutará el flujo de despliegue definido en `.github/workflows/pages.yml`.
4. En **Actions**, comprueba el estado del flujo. Al terminar correctamente, el sitio estará en `https://alexantunez0194-beep.github.io/Dulces/`.

## Editar el catálogo

- **Nombre:** en `index.html`, busca `Dulceria`.
- **WhatsApp:** busca `WHATSAPP_NUMBER`. Usa el código de país y solo números. El número configurado actualmente es el que se compartió para el negocio.
- **Textos:** cambia los títulos y las descripciones dentro de la sección `Nuestros productos`.
- **Imágenes:** reemplaza los SVG de la carpeta `assets` con fotos propias o modifica las rutas `src` de las etiquetas `img` en `index.html`.

Para editar desde GitHub, abre el archivo, pulsa el lápiz, guarda los cambios con **Commit changes** y espera al despliegue.
