# Plan 3 — Interacción, animaciones y refinamiento de experiencia

## 1. Objetivo del Sprint 3

El objetivo del Sprint 3 es mejorar la experiencia de usuario del portfolio mediante animaciones e interacciones con un propósito claro, reforzando la jerarquía visual, el feedback al usuario y la percepción de calidad del producto final.

Este sprint se centra en refinar la UI ya implementada durante el Sprint 2, sin añadir nuevas secciones estructurales.

---

## 2. Criterio de uso de animaciones

Las animaciones se aplicarán únicamente cuando cumplan al menos uno de los siguientes objetivos:

- Guiar la atención del usuario
- Reforzar la jerarquía visual
- Proporcionar feedback en elementos interactivos
- Mejorar la percepción de fluidez y calidad visual

Se evita el uso de animaciones puramente decorativas o que puedan distraer de la lectura y navegación.

---

## 3. Tipos de animaciones a implementar

### 3.1 Animaciones de entrada al hacer scroll

- Aplicadas a:
  - Hero section
  - Títulos de sección
  - Cards de proyectos
  - Footer
- Animaciones sutiles basadas en opacidad y desplazamiento vertical
- Aparición progresiva mediante `stagger`
- Ejecución una sola vez para evitar distracciones

Estas animaciones ayudan a guiar la lectura y a estructurar visualmente el contenido.

---

### 3.2 Microinteracciones en botones

- Aplicadas a botones primarios y secundarios
- Estados `hover`, `focus` y `active`
- Transiciones suaves de color, sombra y/o ligera traslación

Estas microinteracciones refuerzan la sensación de respuesta y control del usuario.

---

### 3.3 Interacción en cards de proyectos

- Elevación sutil de la card al hacer hover
- Transición progresiva de sombras
- Ligero zoom en la imagen

El objetivo es destacar la interactividad de los proyectos sin restar protagonismo al contenido.

---

### 3.4 Navegación y orientación (Navbar)

- Refinamiento del estado activo mediante scrollspy
- Subrayado animado y transición de color en los enlaces
- Feedback visual claro para indicar la sección actual

Esto mejora la orientación del usuario dentro de la página.

---

### 3.5 Scroll indicator

- Animación sutil en bucle para indicar continuidad de contenido
- Posicionado de forma que no interfiera con el botón principal del hero
- Función puramente informativa

---

### 3.6 Interacciones en el footer

- Hover en enlaces sociales
- Uso de iconos de Bootstrap
- Pequeñas animaciones de desplazamiento horizontal en flechas
- Transiciones suaves para cerrar la experiencia de navegación

---

## 4. Herramientas y enfoque técnico

- GSAP para animaciones de entrada y control por scroll
- CSS para microinteracciones simples
- Reutilización de clases existentes (`gsap-reveal`)
- Coherencia en duraciones, delays y curvas de easing

---

## 5. Accesibilidad y rendimiento

- Respeto a la preferencia del usuario `prefers-reduced-motion`
- Se respeta WCAG 2.1 en relación a movimiento y animación.
- Animaciones ligeras y optimizadas
- Estados interactivos accesibles mediante teclado
- Animaciones que no dependan únicamente del color
- No se penaliza el rendimiento en dispositivos móviles
- Safari iOS muestra el contenido correctamente incluso sin animaciones.

---

## 6. Criterios de finalización del Sprint 3

- Todas las animaciones tienen un propósito claro
- La navegación y lectura siguen siendo fluidas
- No se compromete el rendimiento del sitio
- El resultado transmite profesionalidad y coherencia visual

---

## 7. Decisiones tomadas

- Se implementan animaciones únicamente cuando aportan contexto o refuerzan la jerarquía.
- Se utilizan animaciones de entrada sutiles (opacity, translate).
- No se depende de animaciones para transmitir información.
- En dispositivos móviles se prioriza una experiencia estática si el sistema lo indica.
- Se respeta completamente la media query `prefers-reduced-motion`.

---

## 8. Qué se ha implementado

- Animaciones de entrada en:
  - Hero section
  - Project cards
  - Títulos de sección
- Animaciones suaves y no intrusivas con GSAP.
- Eliminación de animaciones innecesarias o decorativas.
- Media query para desactivar animaciones cuando el usuario lo solicita.

---

## 9. Notas posteriores a la implementación

23/12/2025: Las animaciones del proyecto respetan la preferencia del usuario prefers-reduced-motion.
En dispositivos móviles, donde esta opción suele estar activada por defecto, se prioriza la accesibilidad y el rendimiento, mostrando el contenido sin animaciones innecesarias.
Esto garantiza una experiencia inclusiva sin comprometer la comprensión del contenido.

24/12/2025: Se ajustó la animación de entrada de las project cards moviendo el
estado inicial a CSS y animando hacia el estado final con GSAP,
evitando flashes y mejorando la suavidad, especialmente en móvil.

## 10. Reflexión final del sprint

Este sprint refuerza la idea de que las animaciones deben tener un propósito claro.
El proyecto prioriza una experiencia accesible, inclusiva y profesional, donde el diseño
visual y el movimiento trabajan juntos sin comprometer la usabilidad.
