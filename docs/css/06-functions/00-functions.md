---
icon: lucide/parentheses
---
# Funciones y variables

![Tarjeta de resumen CSS 6-1](../../assets/images/css/06-functions/00-summary.svg)

=== "Variables"

    Nos permiten almacenar valores. Facilitan el mantenimiento y realizar cambios globales con mayor facilidad.

    !!! tip "Guía de uso"

        Son declaradas en la pseudo-clase `:root`

        ```css
        :root {
            --primary: #339af0
        }
        ```

        Y utilizadas por medio de la función `var()`

        ```css
        :root {
            .highlight-primary {
                background-color: var(--primary);
            }
        }
        ```

=== "Calculations"

    Realiza cálculos dinámicos al establecer valores.

    !!! tip "Guía de uso"

        Es común utilizar variables y cálculos en combinación.

        ```css
        :root {
            --text-h1: 50px
        }

        h1 {
            font-size: calc(var(--text-h1) + 10vh)
        }
        ```
