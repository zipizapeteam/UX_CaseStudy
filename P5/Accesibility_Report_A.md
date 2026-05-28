# Informe de Accesibilidad - Análisis 1: Nuestra Web

## 1. Ficha Técnica del Informe

* **Nombre del proyecto:** Diseño A - Nuestra página web.
* **Normativa de referencia:** WCAG 2.1 / 2.2, nivel AA.
* **Herramientas utilizadas:** Lighthouse.
* **Fecha de la auditoría:** 28/05/2026.

## 2. Puntuaciones Globales

* **Performance:** 74/100.
* **Accessibility:** 82/100.
* **Best Practices:** 100/100.
* **SEO:** 63/100.

La puntuación de accesibilidad es aceptable, aunque no perfecta. Lighthouse detecta varios problemas que afectan principalmente al contraste visual, a la identificación de enlaces y a la estructura semántica de la página.

## 3. Análisis por Principios POUR

### A. Perceptible

* **Hallazgo:** Algunos colores de fondo y primer plano no tienen suficiente contraste.
* **Impacto:** Usuarios con baja visión o con dificultades para distinguir colores pueden tener problemas para leer determinados textos o botones.
* **Criterio WCAG incumplido:** 1.4.3 - Contraste mínimo.
* **Solución:** Aumentar el contraste entre texto y fondo, usando colores más oscuros para el texto o fondos más claros.

### B. Operable

* **Hallazgo:** La página no presenta claramente elementos de navegación como regiones principales o enlaces de salto.
* **Impacto:** Los usuarios que navegan con teclado o tecnologías de asistencia pueden tener más dificultad para moverse rápidamente por la página.
* **Criterio WCAG relacionado:** 2.4.1 - Evitar bloques.
* **Solución:** Añadir un enlace de “Saltar al contenido principal” y mejorar la estructura de navegación.

### C. Comprensible

* **Hallazgo:** Algunos enlaces no tienen un nombre discernible.
* **Impacto:** Los lectores de pantalla no pueden explicar correctamente al usuario para qué sirve ese enlace.
* **Criterio WCAG incumplido:** 2.4.4 - Propósito de los enlaces.
* **Solución:** Añadir textos descriptivos o atributos `aria-label` en los enlaces que solo usen iconos o elementos visuales.

### D. Robusto

* **Hallazgo:** El documento no tiene una región principal correctamente definida.
* **Impacto:** Las tecnologías de asistencia pueden interpretar peor la estructura de la página.
* **Criterio WCAG relacionado:** 4.1.2 - Nombre, función y valor.
* **Solución:** Usar etiquetas semánticas como `<main>`, `<nav>`, `<header>` y `<footer>`.

## 4. Tabla de Hallazgos y Prioridades

| ID     | Prioridad | Criterio WCAG              | Error detectado                            | Recomendación Técnica                                      |
| ------ | --------- | -------------------------- | ------------------------------------------ | ---------------------------------------------------------- |
| ACC-01 | Alta      | 1.4.3 Contraste mínimo     | Contraste insuficiente entre fondo y texto | Modificar los colores para mejorar la legibilidad          |
| ACC-02 | Alta      | 2.4.4 Propósito de enlaces | Enlaces sin nombre discernible             | Añadir texto descriptivo o `aria-label`                    |
| ACC-03 | Media     | 2.4.1 Evitar bloques       | No existe una región principal clara       | Añadir etiqueta `<main>` y mejorar la estructura semántica |
| ACC-04 | Media     | Buenas prácticas           | Falta un landmark principal                | Definir correctamente las zonas principales del documento  |

## 5. Conclusiones y Declaración de Conformidad

La página cumple parcialmente con los criterios de accesibilidad del nivel AA. Aunque obtiene una puntuación positiva de 82/100, todavía existen barreras importantes relacionadas con el contraste, los enlaces y la estructura semántica.

Los próximos pasos recomendados serían mejorar el contraste visual, revisar todos los enlaces sin etiqueta accesible y añadir una estructura HTML más clara mediante etiquetas semánticas. Con estos cambios, la página podría alcanzar una accesibilidad mucho más sólida y cercana al cumplimiento completo.
