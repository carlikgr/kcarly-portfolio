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
- Estilado de componentes (navbar, hero, botones, cards)
- Enfoque de diseño responsive (mobile-first)
- Consideraciones básicas de accesibilidad

No incluyas código.
Concéntrate en decisiones de diseño y estrategia de implementación."

---

## 2. Respuesta de la IA (plan completo)

La IA propuso un enfoque de rediseño visual basado en claridad, coherencia y escalabilidad:

1. Definir una jerarquía visual clara mediante escala tipográfica, espaciado consistente y alineaciones limpias.
2. Establecer una paleta de colores limitada con colores primarios, neutros y un color de acento.
3. Utilizar una tipografía moderna y legible, con tamaños adaptables mediante unidades relativas.
4. Aplicar un enfoque mobile-first, adaptando progresivamente el layout a pantallas mayores.
5. Diseñar componentes reutilizables (navbar, hero, project cards, botones).
6. Integrar animaciones sutiles y con propósito, evitando distracciones innecesarias.
7. Garantizar accesibilidad básica mediante semántica correcta, contraste suficiente y navegación por teclado.
8. Probar el diseño en distintos breakpoints: móvil, tablet y escritorio.

---

## 3. Decisiones de diseño y técnicas

- El diseño visual es minimalista, claro y orientado a un portfolio profesional.
- Se prioriza la legibilidad y la jerarquía visual frente a elementos decorativos innecesarios.
- Se utiliza Bootstrap 5 como base de layout y sistema de grid, extendido con CSS personalizado.
- La tipografía principal es **Manrope (Google Fonts)**, aplicada globalmente.
- Los colores, tamaños de texto y espaciados se gestionan mediante variables CSS definidas en `:root`.
- En este sprint, los estilos personalizados se concentran en un único archivo CSS para facilitar la iteración rápida del diseño.
- La separación en archivos específicos de layout y componentes se deja como mejora futura una vez estabilizada la UI.
- Las imágenes se sirven desde **ImageKit**, optimizadas en formato WebP y con parámetros de rendimiento.

---

## 4. Qué se ha implementado exactamente

- Navbar sticky con:
  - Logo alineado a la izquierda
  - Enlaces centrados (Home, Work, About)
  - Botón primario “Contact”
  - Menú responsive con burger en móvil
  - Estado activo por sección (scrollspy)
- Hero section con:
  - Imagen de perfil circular alineada a la izquierda
  - Texto principal (H1) y subtítulo jerárquico
  - Botón primario “View Projects”
  - Fondo claro con formas degradadas decorativas
  - Indicador de scroll situado al final del hero sin solaparse con el contenido
- Sección de proyectos:
  - Proyecto destacado a ancho completo
  - Grid de project cards responsive
  - Imágenes optimizadas desde ImageKit
- Footer rediseñado con enlaces sociales y jerarquía clara.
- Integración de favicon usando SVG.
- Navegación interna mediante anchors (#home, #about, #projects, #contact).

---

## 5. Accesibilidad y responsive

Se han aplicado las siguientes mejoras de accesibilidad:

- Uso consistente de HTML semántico (`header`, `nav`, `main`, `section`, `footer`).
- Un único `<h1>` y jerarquía correcta de encabezados.
- Enlace de “skip to content” para navegación por teclado.
- Estados de foco visibles (`:focus-visible`) para elementos interactivos.
- Contraste de color suficiente siguiendo WCAG AA.
- Uso de `aria-current` en el enlace activo del navbar.
- Elementos decorativos (formas, scroll indicator) marcados con `aria-hidden="true"`.
- Texto alternativo descriptivo en imágenes informativas.
- Respeto a `prefers-reduced-motion` para usuarios sensibles al movimiento.
- Diseño responsive mobile-first con breakpoints de Bootstrap.

---

## 6. Notas posteriores a la implementación

- El uso de IA se ha limitado exclusivamente a la **fase de planificación**.
- Todas las decisiones finales de diseño, estructura HTML y estilos CSS han sido implementadas manualmente.
- El diseño ha sido probado en desktop y móvil, verificando navegación, contraste y jerarquía visual.
- Este plan documenta fielmente el proceso seguido durante el Sprint 2 y servirá como referencia para futuras iteraciones.

