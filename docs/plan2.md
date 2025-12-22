# Plan 2 — Diseño visual e implementación de la UI

## 1. Prompt enviado a la IA

"Ayúdame a planificar el rediseño visual de una web de portfolio profesional.
El proyecto ya cuenta con:
- Estructura HTML base
- Reset CSS y variables globales
- Repositorio configurado y despliegue activo en GitHub Pages

Necesito un plan claro y estructurado que cubra:
- Jerarquía visual y estructura de layout
- Estrategia de paleta de colores y tipografía
- Estilado de componentes (botones, secciones, cards)
- Enfoque de diseño responsive (mobile-first)
- Consideraciones básicas de accesibilidad

No incluyas código.
Concéntrate en decisiones de diseño y estrategia de implementación."

---

## 2. Respuesta de la IA (plan completo)

La IA propuso un enfoque de rediseño visual basado en claridad, coherencia y adaptabilidad:

1. Definir una jerarquía visual clara mediante espaciado, escala tipográfica y separación de secciones.
2. Establecer una paleta de colores limitada con tonos primarios, secundarios y neutros.
3. Utilizar un sistema tipográfico que priorice la legibilidad y una apariencia profesional.
4. Aplicar un enfoque mobile-first, mejorando progresivamente el diseño en pantallas más grandes.
5. Diseñar componentes reutilizables para mantener consistencia visual.
6. Mantener las animaciones sutiles y con propósito, evitando movimientos innecesarios.
7. Garantizar accesibilidad mediante buen contraste, tamaños de texto legibles y estructura semántica.
8. Probar el diseño en los breakpoints habituales: móvil, tablet y escritorio.

---

## 3. Decisiones de diseño y técnicas

- El diseño visual será minimalista y profesional.
- Se priorizará la claridad del contenido frente a elementos decorativos.
- Se respetará la estructura CSS existente:
  - `base.css` para variables y estilos globales
  - `layout.css` para layout y espaciados
  - `components.css` para componentes reutilizables
- No se introducirán nuevos frameworks ni herramientas de build en este sprint.

---

## 4. Qué se va a implementar (Sprint 2)

- Ajuste de la estructura HTML para reflejar la jerarquía final del contenido.
- Definición de una paleta de colores consistente mediante custom properties.
- Aplicación de estilos tipográficos para encabezados y texto base.
- Implementación del layout usando Flexbox y CSS Grid cuando sea adecuado.
- Estilado de componentes básicos como botones, secciones y bloques de contenido.
- Navbar sticky, scrollspy y responsive con burger menu.
- Hero Section con imagen circular, textos alineados a la izquierda, scroll indicator y botón primario.
- Sección de proyectos con Featured Project de ancho completo y seis cards con animaciones GSAP.
- Optimización de imágenes mediante ImageKit.
- Responsividad y tipografía fluida adaptativa.
- Hover states: nav-links con línea verde brillante, botón primario negro.

---

## 5. Tecnologías y Librerías

- HTML5 (estructura semántica)  
- CSS3 (variables, responsive, estilos personalizados)  
- Bootstrap 5 (navbar, grid, responsive utilities)  
- Google Fonts – Manrope (tipografía global)  
- GSAP (animaciones en scroll y hover)  
- ImageKit.io (optimización y CDN de imágenes)  
- JavaScript (scrollspy y comportamiento interactivo del navbar)

---

