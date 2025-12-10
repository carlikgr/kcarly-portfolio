# Plan 1 — Configuración base del proyecto

## 1. Prompt enviado a la IA
«Ayúdame a planificar el Sprint 1 del proyecto de plantilla de portfolio profesional. Necesito un plan claro para: estructura de carpetas, HTML base, CSS base, configuración del repositorio, despliegue inicial y documentación.»

## 2. Plan de la IA (respuesta completa)
Sprint 1 — Estructura Base y Despliegue Inicial

1. Configuración del repositorio  
   - Crear el repositorio en GitHub.  
   - Inicializar Git localmente.  
   - Crear `.gitignore`.  
   - Realizar el primer commit con la estructura inicial.

2. Creación de la estructura de archivos y carpetas  
   - Crear `/docs`.  
   - Crear `/assets` con subcarpetas: `css`, `js`, `images`, `fonts`.  
   - Crear archivos principales: `index.html`, `404.html`, `README.md`, `LICENSE`.  
   - Crear archivos iniciales de CSS y JS vacíos.

3. Construcción de la estructura HTML mínima  
   - Definir la estructura base del documento.  
   - Configurar el `<head>` con los metadatos esenciales.

4. Inicio de los estilos base  
   - Crear estilos globales y reset.  
   - Definir la organización del CSS (base, layout, componentes).  
   - Crear el archivo “barrel” de CSS.

5. Configuración de GitHub Pages  
   - Activar GitHub Pages para la rama principal.  
   - Verificar el despliegue inicial.  
   - Confirmar el funcionamiento de `404.html`.  
   - Añadir la URL final al README.

6. Documentación inicial  
   - Completar el README (descripción, stack, instrucciones).  
   - Añadir política de uso de IA.  
   - Documentar este sprint dentro de `docs/plan1.md`.

7. Revisión final del sprint  
   - Verificar posición y existencia de todos los archivos.  
   - Comprobar que la consola del navegador no muestre errores.  
   - Confirmar que los enlaces funcionan correctamente.  
   - Hacer el commit final del sprint.

## 3. Decisiones tomadas
- Crearé una estructura minimalista con `assets/css`, `assets/js`, `assets/images`.  
- Usaré custom properties desde el inicio.  
- Desplegaré en GitHub Pages para asegurar un flujo de publicación estable.

## 4. Qué voy a implementar exactamente
- `index.html` con estructura semántica vacía  
- `404.html` básico  
- `base.css` con reset + variables  
- `README.md` actualizado con la URL del deployment  
- Configuración de GitHub Pages
