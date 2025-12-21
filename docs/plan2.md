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

## 4. Qué se va a implementar

- Ajuste de la estructura HTML para reflejar la jerarquía final del contenido.
- Definición de una paleta de colores consistente mediante custom properties.
- Aplicación de estilos tipográficos para encabezados y texto base.
- Implementación del layout usando Flexbox y CSS Grid cuando sea adecuado.
- Estilado de componentes básicos como botones, secciones y bloques de contenido.
- Mejora del espaciado y alineación para lograr equilibrio visual.

---

## 5. Consideraciones de accesibilidad y responsive

- Mantener el uso de HTML semántico.
- Asegurar contraste de color suficiente (WCAG AA).
- Utilizar unidades relativas y tipografía fluida cuando sea posible.
- Seguir un enfoque mobile-first con mejora progresiva.
- Evitar animaciones excesivas y respetar la preferencia de reducción de movimiento del usuario.

---

## 6. Notas posteriores a la implementación

(A completar una vez finalizada la implementación del Sprint 2.)
