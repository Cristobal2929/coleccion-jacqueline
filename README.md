---
sdk: static
title: Colección Jacqueline – Boutique de eventos
description: Página única y responsiva para la boutique femenina Colección Jacqueline.
author: Director de Diseño
---

# Colección Jacqueline

Esta es una web estática de una sola página que muestra el catálogo, los servicios y un formulario de contacto para **Colección Jacqueline**, boutique especializada en vestidos de evento, tocados personalizados y complementos exclusivos.

## Estructura de archivos

- `index.html` – Página única con todo el contenido, estilos y scripts embebidos.
- `static/img/imagen_1.jpg` – Hero background.
- `static/img/imagen_2.jpg` – Imagen de vestidos largos.
- `static/img/imagen_3.jpg` – Imagen de tocados personalizados.
- `static/img/imagen_4.jpg` – Imagen de complementos y bolsos.
- `README.md` – Este documento.

## Cómo usar

1. Coloca las imágenes en la carpeta `static/img/` con los nombres indicados.
2. Abre `index.html` en cualquier navegador.
3. Si deseas conectar el formulario a un servicio real, reemplaza la función `handleSubmit` en el script por la lógica correspondiente.

## Notas de diseño

- Tipografía: **Playfair Display** (título) + **Lato** (texto).
- Paleta de colores: indigo profundo como color principal y amarillo dorado como acento.
- Responsivo: columnas que se adaptan a móvil, tablet y escritorio.
- Accesibilidad: foco visible, `prefers-reduced-motion` respetado.
- No se incluyen datos de contacto falsos; el botón de WhatsApp lleva un marcador `[TU WHATSAPP]` para rellenar manualmente.