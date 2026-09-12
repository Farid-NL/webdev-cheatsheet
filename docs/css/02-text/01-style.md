---
icon: lucide/italic
---

# Estilo de texto

![Tarjeta de Resumen CSS 2](../../assets/images/CSS-Summary-Card-2.svg)

=== "Font Weight"

    Establece el grosor de los caracteres de texto

    !!! tip "Guía"

        - ^^Encabezados^^ deberían estar entre **500 a 900**
        - ^^Otros textos^^ deberían estar entre **300 a 400**

    _Valores comúnes_

    |Valor|Descripción|
    |---|---|
    |400|Normal|
    |500|Medium|
    |700|Bold|

=== "Font Style"

    Establece el estilo de la fuente

    !!! tip "Guía"

        - Prefiere utilizar _font weight_ y color
        - Puede ser usado para llamar la atención.
          ```html
          <h1>Cut your publishing time <span style="font-style: italic;">in half</span></h1>
          ```

=== "List Style"

    Establece el estilo de la lista

    !!! tip "Guía"

        **Siempre** remueve el estilo de las listas cuando sean
        usadas con [propositos estructurales](../../html/02-text/#__tabbed_1_3).

=== "Text Decoration"

    Establece las lineas decorativas del texto

    !!! tip "Guía"

        - **Siempre** remueve el subrayado de hipervínculos (`#!html <a href="...">`).
        - Utiliza la decoración de texto con **poca frecuencia**.

    ```css
    ... {
                            /* (1)! */    /* (2)! */   /* (3)! */
        text-decoration: underline blue dotted
    }
    ```

    1. Tipo de línea
    2. Color de la línea
    3. Estilo de la línea

=== "Text Transform"

    Establece las mayúsculas y minúsculas del texto.

    !!! tip "Guía"

        Mantén el uso de mayúsculas en cada oración.

        ```txt
        Sentence Case
        ```
