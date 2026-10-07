# Registro de Decisiones de Diseño y Arquitectura - Portafolio Web

## 1. Secciones del Portafolio
El sitio estará estructurado en las siguientes secciones clave para comunicar mi perfil profesional de manera clara y directa:
- **Inicio / Hero**: Presentación personal rápida, mi rol actual y un llamado a la acción (CTA) para contactar.
- **Sobre mí / Habilidades**: Breve descripción de mi trasfondo, tecnologías que domino y herramientas con las que trabajo.
- **Proyectos**: Muestra de proyectos destacados con descripción, tecnologías usadas, enlace a código fuente y demo en vivo.
- **Contacto**: Formulario accesible e información directa (correo, redes sociales, GitHub).

## 2. Paleta de Colores
Se seleccionaron colores con alto contraste para asegurar una puntuación sobresaliente en accesibilidad (Lighthouse):
- **Color Primario (Acento):** `#2563EB` (Azul vibrante, transmite profesionalismo y confianza).
- **Fondo Modo Claro:** `#F8FAFC` (Gris muy claro, reduce la fatiga visual frente al blanco puro).
- **Texto Modo Claro:** `#0F172A` (Azul/Gris muy oscuro, alto contraste de lectura).
- **Fondo Modo Oscuro:** `#0F172A` (Azul/Gris oscuro profundo).
- **Texto Modo Oscuro:** `#F1F5F9` (Gris claro de alta legibilidad).

## 3. Tipografía
- **Fuente Principal (Cuerpo):** `'Inter', system-ui, sans-serif`
- **Fuente Secundaria (Encabezados):** `'Inter', system-ui, sans-serif`
- **Justificación:** Se eligieron fuentes *sans-serif* legibles en pantallas de diversos tamaños, con renderizado óptimo y tiempos de carga rápidos mediante tipografías del sistema o cargas optimizadas.

## 4. Justificación Técnica
- **HTML Semántico:** Uso estricto de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer` y etiquetas ARIA donde sea necesario para asegurar accesibilidad con lectores de pantalla y excelente SEO.
- **CSS Modular:** Separación de estilos en variables, componentes y *media queries* para garantizar mantenibilidad y código limpio.
- **JavaScript Vainilla:** Implementación directa sin librerías pesadas para garantizar máxima velocidad de carga y rendimiento óptimo en Lighthouse.