# DW Maquetado Web - Curso de Layout

Repositorio del curso de maquetación web y layout impartido por **DW Software**. Aquí encontrarás los ejemplos,
ejercicios y recursos de referencia para practicar.

---

## Contenido del curso

| Archivo                            | Tema                              |
|------------------------------------|-----------------------------------|
| `login.html` + `main.css`          | Layout con Flexbox                |
| `linktree.html` + `linktree.css`   | Componente centrado con Flexbox   |
| `dashboard.html` + `dashboard.css` | Layout con CSS Grid + Responsive  |
| `variables.css`                    | Design System / Variables CSS     |
| `extras.css`                       | Transiciones, gradientes, theming |

---

## Temas clave y recursos

### Design System

Un design system es un conjunto de reglas visuales reutilizables: colores, espaciados, tipografías, sombras y más. En
este proyecto se implementan como **variables CSS** en `variables.css` para mantener consistencia en toda la interfaz.

**Recursos en español:**

- [Qué es un Design System y cómo crear uno](https://www.figma.com/resource-library/que-es-un-design-system/)
- [Design Systems de Figma](https://www.figma.com/resource-library/design-systems/)
- [Atomic Design - Brad Frost (libro)](https://atomicdesign.bradfrost.com/)
- [Guía de design tokens de Supernova](https://www.supernova.io/es-419/what-are-design-tokens)

---

### HTML

HTML es la base de toda página web: define la estructura semántica del contenido. En este curso se practican
formularios, layouts responsivos y componentes con iconografía.

**Recursos interactivos:**

- [MDN Web Docs - HTML](https://developer.mozilla.org/es/docs/Web/HTML) - Documentación oficial en español
- [HTML Reference](https://htmlreference.io/) - Referencia visual interactiva
- [W3Schools HTML](https://www.w3schools.com/html/) - Tutoriales paso a paso
- [Can I Use](https://caniuse.com/) - Compatibilidad de elementos HTML/CSS entre navegadores

---

### CSS Flexbox

Flexbox es un modelo de diseño unidimensional que distribuye elementos en una fila o columna. Ideal para alinear y
distribuir espacio entre elementos, incluso cuando su tamaño es dinámico o desconocido.

**Recursos interactivos:**

- [Flexbox Froggy](https://flexboxfroggy.com/) - Juego para aprender Flexbox resolviendo niveles
- [Flexbox Adventure](https://flexboxadventure.com/) - Aventura interactiva para practicar propiedades
- [CSS-Tricks - Guía completa de Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Artículo de
  referencia con diagramas animados
- [Flexbox Playground de Codecademy](https://www.codecademy.com/learn/flexbox) - Playground interactivo

---

### CSS Grid

CSS Grid es un sistema de diseño bidimensional que permite crear layouts complejos con filas y columnas. Es perfecto
para estructurar páginas completas, dashboards y galerías de contenido.

**Recursos interactivos:**

- [CSS Grid Garden](https://cssgridgarden.com/) - Juego para aprender Grid plantando jardines
- [Grid by Example](https://gridbyexample.com/) - Ejemplos prácticos y patrones de diseño
- [CSS Grid Inspector de Firefox](https://developer.mozilla.org/es/docs/Tools/Page_Inspector/How_to/Examine_grid_layouts) -
  Herramienta de depuración visual
- [Layoutit Grid](https://grid.layoutit.com/) - Generador visual de Grid layouts

---

### Animaciones y Transiciones CSS

Las transiciones permiten animar cambios de propiedades CSS de forma suave. Las animaciones permiten crear movimientos
complejos con `@keyframes`. Son fundamentales para crear interfaces con buena experiencia de usuario.

**Recursos:**

- [CSS3 Transition Tool de Toptal](https://www.toptal.com/developers/css3maker/css3-transition) - Generador visual de
  transiciones CSS
- [Animista](https://animista.net/) - Generador de animaciones CSS con preview en tiempo real
- [CSS-Tricks - Guía de animaciones](https://css-tricks.com/almanac/properties/a/animation/)
- [Easing Functions Cheat Sheet](https://easings.net/) - Referencia visual de funciones de aceleración

---

### Tailwind CSS

Tailwind es un framework CSS utility-first que permite construir interfaces directamente en el HTML con clases
predefinidas. Elimina la necesidad de escribir CSS personalizado en muchos casos y acelera enormemente el desarrollo de
UI.

**Recursos:**

- [Tailwind CSS Playground](https://play.tailwindcss.com/) - Playground oficial para probar clases
- [Documentación oficial](https://tailwindcss.com/docs) - Referencia completa de clases
- [Tailwind UI](https://tailwindui.com/) - Componentes premium de UI

---

### Extras CSS - Trucos y tips

CSS tiene muchas funcionalidades modernas que facilitan el desarrollo y dan lugar a efectos muy chulos. Aquí tienes
algunos de los que veremos en clase:

- **Grid responsive sin media queries** - Usa `repeat(auto-fit, minmax(240px, 1fr))` para crear layouts que se adapten
  automáticamente al tamaño del contenedor sin necesidad de breakpoints.
- **Texto con gradientes** - Aplica `background: linear-gradient(...)` junto con `-webkit-background-clip: text` y
  `-webkit-text-fill-color: transparent` para crear texto con degradados coloridos.
- **Selección de texto personalizada** - Usa el pseudo-elemento `::selection` para cambiar el color de fondo y texto
  cuando el usuario selecciona contenido.
- **Temas dark/light con `light-dark()`** - La función `light-dark(colorClaro, colorOscuro)` permite definir dos colores
  en una sola línea. Combinada con `color-scheme: light dark`, el navegador aplica automáticamente el modo según las
  preferencias del sistema.
- **`color-mix()` para variantes de color** - La función `color-mix(in hsl, var(--primary), white 90%)` genera variantes
  claras u oscuras de un color sin necesidad de definir tokens extra.
- **Efecto 3D perspective on hover** - Combina `transform: perspective(800px) rotateX() rotateY()` con `transition` y
  `box-shadow` para crear un efecto de tarjeta que se inclina en 3D al pasar el ratón.

**Recursos:**

- [MDN - light-dark()](https://developer.mozilla.org/es/docs/Web/CSS/color_value/light-dark) - Documentación de la
  función light-dark
- [MDN - color-mix()](https://developer.mozilla.org/es/docs/Web/CSS/color_value/color-mix) - Documentación de la función
  color-mix
- [CSS-Tricks - Texto con gradiente](https://css-tricks.com/snippets/css/gradient-text/)
- [CSS Feature Queries](https://developer.mozilla.org/es/docs/Web/CSS/@supports) - Cómo detectar soporte de funciones
  CSS modernas

---

## Ejecutar el proyecto

Para visualizar los archivos HTML, simplemente abre los `.html` en tu navegador o usa un servidor local.

---

## Créditos

Curso impartido por **Emilio Sánchez - DW Software**
Contacto: esanchez@dwtraining.mx