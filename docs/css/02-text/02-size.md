---
icon: lucide/ruler-dimension-line
---

# Tamaño y espaciado de texto

![Tarjeta de Resumen CSS 3](../../assets/images/css/02-text/02-size/00-summary.svg)

=== "Text Align"

    Establece la alineación horizontal de un texto dentro de un elemento.

    ??? warning "Block vs Inline"

        |Bloque|En línea|
        |---|---|
        |**Sí** hay espacio para que el ^^texto pueda moverse^^<br>![Text Align - Block vs Inline](../../assets/images/css/02-text/02-size/01-text-align-block.svg)|**No** hay espacio para que el ^^texto pueda moverse^^<br>![Text Align - Block vs Inline](../../assets/images/css/02-text/02-size/01-text-align-inline.svg)|

    !!! tip "Guía"

        - **No** se debe justificar el texto.
        - Los ^^bloques largos de texto^^ deben estar **alineados a la izquierda**.
        - Los ^^encabezados^^ pueden estar **centrados**.

=== "Line Height"

    Establece el interlineado del texto.

    !!! tip "Guía"

        - Los ^^encabezados^^ deben ser **menores a 1.5**.
        - El ^^texto regular^^ debe estar entre **1.5 y 2**.

=== "Letter Spacing"

    Establece el espacio entre cada letra del texto.

    !!! tip "Guía"

        Se suele aplicar un **pequeño valor negativo** en píxeles _(i.e `-3.6px`)_
        a los ^^encabezados^^ para mejorar la legibilidad.

=== "Font Size"

    Establece el tamaño de la fuente.

    !!! tip "Guía"

        - Los ^^encabezados^^ deben ser **mayores a 60px**.
        - El ^^texto regular^^ debe estar entre **16px y 32px**.

    !!! tip "¿Cómo se elige el tamaño?"

        Usando una **escala tipográfica**: Sistema estructurado de tamaños de fuente que aporta coherencia visual y agiliza las decisiones de diseño.

        :lucide-link: [Referencia](https://typescale.com/)

    ??? info "Unidades"

        |Absolutas|Relativas|
        |---|---|
        |`px`|`%`|
        |`pt`|`em`|
        |`in`|`rem`|
        |`cm`|`vh`|
        |`mm`|`vw`|
