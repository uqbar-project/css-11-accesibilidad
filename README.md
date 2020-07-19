
## Atributos de calidad de una página web

Si les preguntamos qué debe tener una página web, podemos nombrar varios atributos de calidad importantes:

- que sea performante,
- que estéticamente sea agradable, en cuanto a disposición espacial, elección de colores y tipografías, la organización jerárquica de lo importante y lo periférico,
- que sea "usable", que ofrezca una buena "user experience" -> sería bueno tener en cuenta quién accederá a nuestra página y qué cuestiones de accesibilidad necesitamos resolver

## Accesibilidad

La cita de Manuel Matuzovic es una gran introducción para hablar de accesibilidad:

> _"Accessibility is something that concerns all of us, you and me, every day. What we create is useless if it isn’t accessible."_

## Primer ejemplo: notas

### Versión original

Como muestra, vamos a ver la página `ejemplo_notas.html`, que simula una planilla de notas de una materia:

![ejemplo notas](./images/ejemplo_notas.png)

Vean que el tamaño de la letra no parece ser suficientemente grande: en un mundo donde [el 61% de las personas en Holanda, y más de 4.000.000.000 de personas en el mundo usamos anteojos o lentes de contacto](https://www.cbs.nl/en-gb/news/2013/38/more-than-6-in-10-people-wear-glasses-or-contact-lenses#:~:text=More%20and%20more%20people%20wear,wear%20glasses%20or%20contact%20lenses.), no parece ser una decisión que favorezca la accesibilidad.

Y si descargamos el Add-on [Let's get color blind](https://addons.mozilla.org/es/firefox/addon/let-s-get-color-blind/) de Firefox, podremos ver cómo perciben la misma página personas con deuteranopia (el tipo de daltonismo más común):

![notas para un daltónico](./images/daltonicoNotas.gif)

Se calcula un [8% de personas con daltonismo en el mundo](http://www.colourblindawareness.org/colour-blindness/).

Pero más allá de todo, la página muestra muy poca información, solo colores rojo y verde: por más que los interpretemos correctamente como algo negativo y positivo, no son para nada representativos.

### Versión mejorada

En el archivo `ejemplo_notas_fixed.html` hicimos algunos cambios:

- 

![versión mejorada](./images/versionMejorada.gif)

## Material adicional

- [HTML: Una buena base para la accesibilidad](https://developer.mozilla.org/es/docs/Learn/Accessibility/HTML)
- [Writing HTML with accessibility in mind](https://medium.com/alistapart/writing-html-with-accessibility-in-mind-a62026493412)
- [Writing CSS with Accessibility in Mind](https://medium.com/@matuzo/writing-css-with-accessibility-in-mind-8514a0007939)
- [The A11Y Project](https://www.a11yproject.com/)
- [Accessibility](https://www.w3.org/standards/webdesign/accessibility.html)
