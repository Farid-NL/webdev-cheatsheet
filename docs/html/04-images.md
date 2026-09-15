---
icon: lucide/image
---

# Imágenes y Etiquetas Autocerradas

![Tarjeta de Resumen HTML 4](../assets/images/html/04-images/00-summary.svg)

!!! info "Etiquetas de autocierre"
    Son etiquetas que no contienen texto de cierre explícito, como `#!html <hr>` o `#!html <hr />`.

=== "Images"

    ```html
    <img src="images/dolphin.jpg" alt="blue dolphin">
    ```

    - **src:** Ruta o fuente de la imagen.
    - **alt:** Texto alternativo de descripción.

=== "SVGs"

    Se pueden utilizar directamente mediante código vectorial o dentro de etiquetas `<img>`:

    ```html
    <!-- SVG Inline -->
    <svg fill="none" stroke-width="1.5">
        <path d="m8.25 4.5 7.5 7.5-7.5 7.5" />
    </svg>

    <!-- SVG en img -->
    <img src="images/logo.svg" alt="logo">
    ```
