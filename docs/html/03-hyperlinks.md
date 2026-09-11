---
icon: lucide/link
---

# Rutas de archivo, hipervínculos y atributos

![Tarjeta de Resumen HTML 3](../assets/images/HTML Summary Cards_page_4.svg)

=== "Anchor Tags & Attributes"

    Los atributos proveen información adicional a las etiquetas mediante pares de `nombre="valor"`.

    ```html
    <a href="register.html">Get Started</a>
    ```

    - **Nombre del atributo:** `href`
    - **Valor del atributo:** `register.html`

=== "Absolute vs Relative URLs"

    - **URL Absoluta:** Dirección completa en la web.
        ```html
        <a href="[https://www.facebook.com/quillapp](https://www.facebook.com/quillapp)">Facebook Page</a>
        ```
    - **URL Relativa:** Enlace a un archivo dentro del mismo proyecto.
        ```html
        <a href="register.html">Get Started</a>
        ```

=== "The ID Attribute"

    Asigna un identificador único para vincular o dar estilo a un elemento.

    ```html
    <h2 id="features">How it works</h2>
    <a href="#features">Learn More</a>
    ```
