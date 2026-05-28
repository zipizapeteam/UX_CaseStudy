# Usability Report

**Adrián Ramírez Andrés y Pablo de la Torre Roldán**  
**Equipo: ZipiZape**

---

## 1. Resumen Ejecutivo

**Objetivo:** El objetivo principal de este estudio ha sido evaluar la usabilidad y la experiencia de usuario de dos páginas web relacionadas con restauración mediante técnicas de A/B Testing, cuestionarios SUS (System Usability Scale) y análisis de mapas de calor a través de herramientas de Gaze Mapping.

**Metodología:** La evaluación se realizó mediante pruebas de usuario centradas en dos tareas principales: realizar un pedido online y efectuar una reserva. Estas funcionalidades fueron seleccionadas por considerarse las acciones más importantes dentro de este tipo de páginas web.

**Principales Hallazgos:** Los resultados muestran diferencias claras entre ambos casos. El caso A obtuvo una puntuación SUS de 96,25 puntos, reflejando una experiencia de usuario sobresaliente. Los usuarios percibieron la interfaz como intuitiva, agradable visualmente y fácil de aprender. Además, los mapas de calor mostraron que la atención se dirigía correctamente hacia los elementos principales de navegación y acciones importantes. Por otro lado, el caso B obtuvo 81,77 puntos SUS, una puntuación igualmente positiva pero inferior a la del caso A. Durante las pruebas se detectaron algunos problemas relacionados con la navegación, especialmente en el comportamiento del logotipo, la gestión del menú y la visibilidad del botón de pago. Los mapas de calor también reflejaron cierta dispersión de atención en zonas concretas de la interfaz, indicando posibles puntos de confusión.

**Resultado Global:** De forma general, ambos sistemas ofrecen una experiencia de usuario satisfactoria y superan ampliamente la puntuación media considerada aceptable en la escala SUS. Sin embargo, el caso A presenta una navegación más intuitiva, una jerarquía visual más clara y una experiencia más fluida para el usuario, obteniendo mejores resultados tanto en las pruebas prácticas como en la percepción subjetiva de usabilidad.

---

## 2. Metodología y Reclutamiento

**Perfil de los participantes:** Los participantes seleccionados para las pruebas contaban con perfiles variados con el objetivo de obtener resultados más representativos. Se incluyeron usuarios con un nivel alto, medio y medio-bajo de competencia digital, desde estudiantes de Ingeniería Informática acostumbrados al uso de interfaces tecnológicas hasta personas de mayor edad con menor experiencia digital.

**Escenario de la prueba:** Las pruebas se realizaron en entornos cotidianos y controlados, utilizando principalmente ordenadores portátiles con formato 16:9. Los participantes debían completar distintas tareas relacionadas con las funcionalidades principales de la web, especialmente realizar un pedido online y efectuar una reserva.

**Herramientas:** Vamos a utilizar un portátil con el software de Gaze Mapping del profesor para estudiar la mirada de los participantes durante la prueba. Además, hemos usado dos cuestionarios de Tally (uno para los datos de usuario básicos y otro para el SUS). —--FALTAN HERRAMIENTAS DE ACCESIBILIDAD—---

---

## 3. Introducción a AB testing

Nuestra web tiene las siguientes funcionalidades con la página web B:

1. REALIZAR PEDIDO
2. REALIZAR RESERVA
3. INICIAR SESION/REGISTRARSE
4. ENCONTRAR Y VISUALIZAR LA CARTA
5. LOCALIZAR REDES SOCIALES

Tras analizarlo en profundidad hemos decidido realizar las pruebas sobre realizar pedido y realizar una reserva, ya que hemos interpretado que son las funciones más importantes de las páginas web.

---

## 4. Reclutamiento de usuarios

Para llevar a cabo las pruebas de usabilidad y obtener resultados lo más variados y representativos posible, decidimos seleccionar distintos perfiles de usuarios. La idea principal era contar con personas con diferentes niveles de experiencia tecnológica, de manera que pudiéramos analizar cómo interactuaban con la web dependiendo de sus conocimientos previos y detectar así posibles problemas desde múltiples perspectivas.

En primer lugar, realizamos pruebas con compañeros de clase por petición expresa del profesor. Consideramos que este perfil era especialmente interesante ya que, al tratarse de estudiantes de Ingeniería Informática, poseen un nivel elevado de conocimientos tecnológicos y están acostumbrados a navegar por interfaces similares a la propuesta en nuestro proyecto. Gracias a ello, podían detectar detalles más técnicos relacionados con la estructura, la organización de la información o la experiencia de usuario.

Posteriormente, buscamos un perfil intermedio formado por amigos y personas de nuestra misma edad que, aunque no pertenecen al ámbito de la informática, sí cuentan con conocimientos básicos y están acostumbrados al uso habitual de páginas web. Este grupo nos permitió comprobar si la navegación resultaba intuitiva para un usuario medio y si los distintos apartados podían encontrarse de manera sencilla y natural.

Finalmente, también intentamos incluir perfiles con menor experiencia tecnológica, principalmente familiares de mayor edad. Su participación nos ayudó a valorar si la página era realmente sencilla y cómoda de utilizar para cualquier tipo de usuario.

En total, seleccionamos cinco personas para realizar las pruebas sobre nuestra página web y otras cinco para realizar el mismo proceso con la página de Goiko, utilizada como referencia comparativa. En el caso de nuestra web, los participantes estaban formados aproximadamente por un 60% de usuarios con un nivel alto y un 40% con un nivel medio de conocimientos informáticos. Sin embargo, en las pruebas realizadas sobre la página de Goiko sí pudimos incluir usuarios con un nivel más básico, ya que no era posible repetir las mismas personas entre el test A y el test B, buscando así mantener cierta variedad y evitar que la experiencia previa condicionara los resultados obtenidos.

| Usuario | Edad | Género | Competencia digital | Gafas | Iluminación en la prueba | Dispositivo | Rol |
|---------|------|--------|---------------------|-------|--------------------------|-------------|-----|
| 1 | 21 | M | Alto | Si | Interior (ventana) | portatil 16:9 | Estudiante info |
| 2 | 23 | M | Alto | Lentillas | Interior (ventana) | portatil 16:9 | Estudiante info |
| 3 | 21 | M | Alto | No | Interior (ventana) | portatil 16:9 | Estudiante info |
| 4 | 22 | F | Alto | No | Interior (flexo) | portatil 16:9 | Estudiante info |
| 5 | 21 | F | Medio/Alto | Si | Interior (flexo) | portatil 16:9 | Estudiante Química |
| 6 | 55 | F | Medio/Bajo | Si | Interior (flexo) | portatil 16:9 | Profesora instituto |
| 7 | 21 | F | Alto | No | Interior (ventana) | portatil 16:9 | Estudiante BBAA |
| 8 | 55 | M | Medio | No | Interior (ventana) | portatil 16:9 | Profesor Universidad |
| 9 | 42 | M | Medio | No | Exterior | portatil 16:9 | Estudiante info |
| 10 | 21 | M | Alto | Si | Exterior | portatil 16:9 | Estudiante |

---

## 5. A testing

### 5.1. Tarea Realizar Pedido

**Usuario 1:** consigue el objetivo, sin problemas para acceder, directo y rápido.

![Inicio - Pedido Usuario 1](A_testing/A_1/inicio_pedironline1.jpg)
![Pide Online - Pedido Usuario 1](A_testing/A_1/objetivopedir_pedironline1.jpg)
![Carrito - Pedido Usuario 1](A_testing/A_1/carrito_pedironline1.jpg)

**Usuario 2:** consigue el objetivo. Navega rápidamente a la página pide online, sin problemas.

![Inicio - Pedido Usuario 2](./A_testing/A_2/inicio_pedironline2.jpg)
![Pide Online - Pedido Usuario 2](./A_testing/A_2/objetivopedir_pedironline2.jpg)
![Carrito - Pedido Usuario 2](./A_testing/A_2/carrito_pedironline2.jpg)

**Usuario 3:** consigue el objetivo de manera sencilla e intuitiva.

![Inicio - Pedido Usuario 3](./A_testing/A_3/inicio_pedironline.jpg)
![Pide Online - Pedido Usuario 3](./A_testing/A_3/objetivopedironline_pedironline.jpg)
![Carrito - Pedido Usuario 3](./A_testing/A_3/carrito_pedironline.jpg)

**Usuario 4:** consigue el objetivo directamente sin problemas.

![Inicio - Pedido Usuario 4](./A_testing/A_10/inicio_pedironline10.jpg)
![Pide Online - Pedido Usuario 4](./A_testing/A_10/objetivopedir_pedironline10.jpg)
![Carrito - Pedido Usuario 4](./A_testing/A_10/carrito_pedironline10.jpg)

**Usuario 5:** consigue el objetivo de manera sencilla.

![Inicio - Pedido Usuario 5](./A_testing/A_5/inicio_pedironline5.jpg)
![Pide Online - Pedido Usuario 5](./A_testing/A_5/objetivo_pedironline5.jpg)
![Carrito - Pedido Usuario 5](./A_testing/A_5/carrito_pedironline5.jpg)

### 5.2. Tarea Realizar Reserva

**Usuario 1:** consigue el objetivo, sin problemas para acceder, directo y rápido (más familiarizado que la anterior prueba).

![Inicio - Reserva Usuario 1](./A_testing/A_1/inicio_reservar1.jpg)
![Reserva - Reserva Usuario 1](./A_testing/A_1/objetivoreserva_reserva1.jpg)

**Usuario 2:** consigue el objetivo. Va directo a la página reservar, tarda muy poco.

![Inicio - Reserva Usuario 2](./A_testing/A_2/inicio_reservar2.jpg)
![Reserva - Reserva Usuario 2](./A_testing/A_2/reservarobjetivo_reservar2.jpg)

**Usuario 3:** consigue el objetivo de manera fluida y ha apreciado que la estética es muy adecuada.

![Inicio - Reserva Usuario 3](./A_testing/A_3/inicio_reservar.jpg)
![Reserva - Reserva Usuario 3](./A_testing/A_3/objetivoreserver_reservar.jpg)

**Usuario 4:** consigue el objetivo. Consigue hacer la tarea directamente.

![Inicio - Reserva Usuario 4](./A_testing/A_10/inicio_reservar10.jpg)
![Reserva - Reserva Usuario 4](./A_testing/A_10/objetivoreserva_reservar10.jpg)

**Usuario 5:** consigue el objetivo en poco tiempo.

![Inicio - Reserva Usuario 5](./A_testing/A_5/inicio_reservar5.jpg)
![Reserva - Reserva Usuario 5](./A_testing/A_5/objetivo_reservar5.jpg)

### 5.3. Cuestionario SUS

La página obtuvo una puntuación extremadamente alta, alcanzando los 96,25 puntos sobre 100, cuando lo cotidiano es 68 para un buen resultado, lo que indica una experiencia de usuario excelente. Los participantes percibieron el sistema como muy fácil de usar, intuitivo y consistente. Además, prácticamente no encontraron dificultades durante la navegación. Al final la página era muy sencilla y la mayoría de usuarios tenían conocimientos sobre informática.

---

## 6. B testing

### 6.1. Tarea Realizar Pedido

**Usuario 6:** consigue el objetivo. Le ha costado darse cuenta de que al pedir online tienes que darle a la tarjeta del producto. Recomendación: utilizar un botón que diga "añadir".

![Inicio - Pedido Usuario 6](./B_Testing/B_1/inicio_pedironline1.jpg)
![Hamburguesas - Pedido Usuario 6](./B_Testing/B_1/pedir_pedironline1.jpg)

**Usuario 7:** consigue el objetivo. le ha costado pagar pero lo ha conseguido. Recomendación: destacar mejor el botón para pagar.

![Inicio - Pedido Usuario 7](./B_Testing/B_2/inicio_pedironline2.jpg)
![Hamburguesas - Pedido Usuario 7](./B_Testing/B_2/pedir_pedironline2.jpg)

**Usuario 8:** consigue el objetivo. Le ha costado encontrar el botón de finalizar pedido. Mismo problema que con el usuario anterior.

![Inicio - Pedido Usuario 8](./B_Testing/B_3/inicio_pedironline3.jpg)
![Hamburguesas - Pedido Usuario 8](./B_Testing/B_3/pedir_pedironline3.jpg)

**Usuario 9:** consigue el objetivo fácilmente.

![Inicio - Pedido Usuario 9](./B_Testing/B_4/INICIO_pedironline4.jpg)
![Hamburguesas - Pedido Usuario 9](./B_Testing/B_4/PEDIR_pedironline4.jpg)

**Usuario 10:** consigue el objetivo muy fácilmente porque no necesita navegar apenas.

![Inicio - Pedido Usuario 10](./B_Testing/B_5/inicio_pedironline5.jpg)
![Hamburguesas - Pedido Usuario 10](./B_Testing/B_5/pedir_pedironline5.jpg)

### 6.2. Tarea Realizar Reserva

**Usuario 6:** consigue el objetivo. Ha ido directamente a la página de reservas y ha reservado sin problemas.

![Inicio - Reserva Usuario 6](./B_Testing/B_1/inicio_reservar1.jpg)
![Reserva - Reserva Usuario 6](./B_Testing/B_1/reserva_reservar1.jpg)

**Usuario 7:** consigue el objetivo sin problemas de forma eficiente.

![Inicio - Reserva Usuario 7](./B_Testing/B_2/inicio_reservar2.jpg)
![Reserva - Reserva Usuario 7](./B_Testing/B_2/resreva_reservar2.jpg)

**Usuario 8:** consigue el objetivo. No le ha costado encontrar la página de reserva y hacerla.

![Inicio - Reserva Usuario 8](./B_Testing/B_3/inicio_reservar3.jpg)
![Reserva - Reserva Usuario 8](./B_Testing/B_3/reserva_reservar3.jpg)

**Usuario 9:** consigue el objetivo, aunque le cuesta un poco salir del menú que se abre al pinchar en el logo.

![Inicio - Reserva Usuario 9](./B_Testing/B_4/INICIO_reservar4.jpg)
![Menu - Reserva Usuario 9](./B_Testing/B_4/menu_reservar4.jpg)
![Reserva - Reserva Usuario 9](./B_Testing/B_4/reserva_reservar4.jpg)

**Usuario 10:** consigue el objetivo de manera sencilla.

![Inicio - Reserva Usuario 10](./B_Testing/B_5/Inicio_reservar5.jpg)
![Reserva - Reserva Usuario 10](./B_Testing/B_5/reserva_reservar5.jpg)

### 6.3. Cuestionario SUS

El resultado del cuestionario SUS de Goiko ha sido de 81,77 puntos, lo que está muy por encima de la media esperada para un buen resultado, que es de 68.

---

## 7. Conclusiones

### 7.1. Análisis del caso A

Este resultado refleja que la interfaz consigue transmitir confianza al usuario y permite aprender su funcionamiento de manera rápida y natural. En términos de usabilidad, puede considerarse un sistema sobresaliente.

| Prioridad | Hallazgo | Recomendación de Mejora |
|-----------|----------|-------------------------|
| Baja | El SUS obtenido refleja una experiencia de usuario muy positiva, indicando que la interfaz transmite confianza y permite aprender su funcionamiento de manera rápida y natural. Además, los usuarios destacaron el apartado visual de la página, calificándola como atractiva y agradable de utilizar. | Mantener la línea visual y la coherencia estética actual, ya que favorecen la permanencia de los usuarios en la página y facilitan la familiarización con la interfaz. |
| Baja | Los usuarios valoraron positivamente la integración de los colores y la jerarquía visual, indicando que estos ayudan a dirigir la atención hacia los botones y elementos más importantes de la página. | Continuar utilizando contrastes visuales y colores diferenciados para reforzar la visibilidad de las acciones principales y mejorar la experiencia de navegación. |
| Baja | Los mapas de calor muestran que la mayoría de usuarios centran rápidamente su atención en el menú de navegación y en los elementos principales de cada página. No obstante, los resultados del Gaze Mapping pueden no ser totalmente precisos debido a las limitaciones del software utilizado. | Mejorar la precisión de futuras pruebas utilizando herramientas de eye tracking más avanzadas o complementando el análisis con pruebas de usuario adicionales. |

### 7.2. Análisis del caso B

La puntuación obtenida también puede justificarse por algunos problemas de navegación detectados durante las pruebas.

| Prioridad | Hallazgo | Recomendación de Mejora |
|-----------|----------|-------------------------|
| Media | Varios usuarios señalaron que al pulsar sobre el logotipo esperaban ser redirigidos automáticamente a la página de inicio, ya que es el comportamiento habitual en la mayoría de sitios web. Sin embargo, el logotipo desplegaba un menú poco intuitivo, generando cierta confusión durante la navegación. | Añadir la funcionalidad estándar de redirección al inicio al pulsar el logotipo o mejorar la claridad visual del menú desplegable para que su funcionamiento sea más intuitivo. |
| Media | Algunos participantes tuvieron dificultades para cerrar el menú o regresar fácilmente a la pantalla principal, especialmente los usuarios con menor experiencia tecnológica, debido a la ausencia de un botón visible de "cerrar" o de una opción clara para volver al inicio. | Incorporar botones visibles de cierre y navegación, además de reforzar las indicaciones visuales para facilitar la orientación del usuario dentro de la interfaz. |
| Media | Varios usuarios encontraron dificultades para finalizar el pedido y realizar el pago, ya que el botón correspondiente no destaca visualmente lo suficiente dentro de la página. Aunque esto puede verse afectado por las limitaciones del software de Gaze Mapping, se considera un punto a revisar. | Mejorar el contraste, tamaño o posicionamiento del botón de pago para aumentar su visibilidad y facilitar la finalización del proceso de compra. |
| Baja | Los mapas de calor muestran que los usuarios centraron gran parte de su atención en los elementos principales de navegación y en acciones destacadas como "Pedir online" y "Reservar", lo que indica una correcta jerarquía visual. | Mantener la estructura visual actual y continuar reforzando los elementos clave mediante contrastes y diseño visual coherente. |
| Baja | En algunos mapas de calor se aprecia una dispersión de clics en zonas superiores y laterales de la interfaz, especialmente alrededor del logotipo y del menú, indicando posibles dudas sobre el funcionamiento de determinados elementos de navegación. | Simplificar la navegación y reforzar la consistencia de los elementos interactivos para reducir la confusión y mejorar la experiencia general del usuario. |
