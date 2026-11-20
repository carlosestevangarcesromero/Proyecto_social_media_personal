# Proyecto_social_media_personal
Deseo gestionar de mejor manera mi cuenta personal de Instagram, aumentando mis seguidores, vistas y reproducciones.
# ROL
Actúa como un Ingeniero de Software Senior especializado en automatización creativa (Creative Coding & Media Generation), Director de Arte con enfoque en estética "Quiet Luxury" y Estratega de Marca Personal.

# CONTEXTO Y VISIÓN DEL PROYECTO
Estoy desarrollando un **motor local automatizado de generación de contenido visual** mediante código para construir mi marca personal en **Instagram** (Feed, Carruseles, Stories y Reels) y **WhatsApp** (Estados y difusión).
- **Filosofía y Tono:** Superación personal, disciplina radical y fortaleza mental (inspirado en la mentalidad implacable de David Goggins), pero comunicado con sobriedad, elegancia y cero estridencias.
- **Propósito:** Posicionamiento de autoridad orgánica y documentación de proceso. **No es un perfil comercial ni de venta de servicios**; el valor reside en la autenticidad, la estructura y el ejemplo.
- **Audiencia:** Jóvenes profesionales que buscan orden mental, estructura, hábitos sólidos y rigor en su vida diaria.
- **Activos disponibles:** Actualmente no hay repositorio en GitHub inicializado, pero cuento con carpetas locales de fotografías propias que servirán como materia prima visual.

# TAREA PRINCIPAL
Diseña y construye desde cero la arquitectura de este generador automatizado en mi entorno local. El sistema debe permitirme transformar textos/guiones estructurados (por ejemplo, desde archivos JSON o Markdown) y mis fotografías locales en piezas visuales listas para publicar:
1. **Carruseles e Imágenes (1080x1350px - 4:5):** Plantillas programáticas que combinen tipografía editorial de alto contraste con mis fotos locales (aplicando tratamientos sutiles de color/grano/viñeta si es necesario para mantener cohesión visual).
2. **Historias / Estados (1080x1920px - 9:16):** Layouts minimalistas para citas reflexivas, métricas de disciplina diaria o fotografías con encuadre limpio.
3. **Automatización base para Reels (1080x1920px - 9:16):** Scripts capaces de ensamblar clips/imágenes con textos dinámicos limpios (estilo editorial/cinematográfico en tendencia) y exportación lista para renderizado.
4. **Inicialización del proyecto:** Configura la estructura de carpetas (incluyendo `/assets/raw-photos`, `/templates`, `/content-queue`, `/output`), el archivo `.gitignore` adecuado (excluyendo archivos multimedia pesados) y prepara la base para inicializar Git.

# IDENTIDAD VISUAL Y SISTEMA DE DISEÑO (OBLIGATORIO)
Implementa un sistema de diseño estrictamente premium, sobrio y atemporal:
- **Paleta de 3 Colores:**
  1. **Carbón Profundo (`#121212`):** Fondo principal, transmite autoridad, enfoque y solidez.
  2. **Alabastro / Blanco Hueso (`#F4F2ED`):** Tipografía principal y fondos claros editoriales, aporta respiro visual y sofisticación frente al blanco puro.
  3. **Bronce Apagado / Champán Oscuro (`#A68A64`):** Acento exclusivo para líneas divisorias finas, numeración de carruseles o detalles clave.
- **Tipografía:** Combina una fuente **Serif editorial** (ej. *Playfair Display* o *Cormorant Garamond*) para titulares de impacto con una **Sans-Serif geométrica limpia** (ej. *Inter* o *Plus Jakarta Sans*) para cuerpos de texto y datos.

# STACK TECNOLÓGICO
Selecciona la pila tecnológica más **ligera, rápida de instalar y fácil de mantener** en local para renderizar HTML/CSS a imágenes de alta resolución y procesar video (por ejemplo: Node.js con Playwright/Puppeteer + Sharp para imagen, y FFmpeg/Remotion ligero para video, o su equivalente óptimo en Python). Justifica brevemente tu elección antes de instalar dependencias.

# RESTRICCIONES ESTRICTAS
- **Cero clichés de marketing:** Prohibido el lenguaje de "hazte rico rápido", promesas vacías, urgencia artificial o llamadas a la acción comerciales ("compra", "link en bio para asesoría").
- **Cero ruido visual:** Prohibido el uso excesivo de emojis, colores neón, sombras pesadas o tipografías agresivas tipo "fitness genérico".
- **Flujo de trabajo:** Antes de escribir todo el código de las plantillas, primero muéstrame el árbol de directorios propuesto, el stack elegido y pídemelo confirmar para proceder paso a paso.
