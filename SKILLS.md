# AGENTS.md — [Social media personal] 

## Descripcion. [Motor local de generación programática de contenido visual (carruseles, historias, imágenes estáticas y reels) diseñado para Instagram y WhatsApp mediante código ligero. Dirigido a jóvenes profesionales que buscan estructura, rigor y desarrollo personal; su único fin es el posicionamiento orgánico de autoridad mediante la documentación auténtica del proceso, sin venta de servicios ni llamadas a la acción comerciales] 

## Stack y estructura - Tecnologías y versiones clave. - Qué hay en cada carpeta o archivo importante (solo lo que no es obvio). 
__________________________________________________________________________________________________________________

## Convenciones (Adición de Memoria)
- **Registro de Memoria Persistente:** El archivo `MEMORY.md` en la raíz del proyecto actúa como la bitácora oficial de evolución. Cada decisión arquitectónica, nueva estrategia de contenido, plantilla aprobada o herramienta incorporada debe quedar registrada allí con fecha, motivo e impacto.

## Forma de trabajar
- **Protocolo Obligatorio de Planeación y Consulta (Gatekeeping):**
  Antes de escribir una sola línea de código nuevo o renderizar cualquier pieza multimedia (carruseles, historias, imágenes o reels), el agente **debe detenerse y presentar una propuesta estructurada** esperando aprobación explícita. Ninguna producción inicia sin luz verde del usuario.
- **Estructura de la Propuesta de Aprobación:**
  Toda solicitud de aprobación debe responder obligatoriamente a estos 3 puntos de forma clara y concisa:
  1. **Por qué es importante:** Justificación estratégica o técnica del cambio, pieza o estrategia propuesta.
  2. **Cómo se va a implementar:** Archivos a crear/modificar, plantillas, estructura de datos o flujo técnico exacto.
  3. **Cómo beneficia al proyecto:** Impacto directo en la estética *Quiet Luxury*, la eficiencia del motor o el posicionamiento de autoridad de la marca.
- **Tamaño de los cambios:** Mantener iteraciones atómicas y controladas. Al finalizar una ejecución aprobada, resumir exactamente qué se generó, dónde se guardó en `output/` y confirmar la actualización de `MEMORY.md`.

- ✅ **Siempre:**
  - Registrar automáticamente en `MEMORY.md` cada cambio aprobado, nueva estrategia de contenido, ajuste visual o herramienta nueva utilizada, manteniendo el historial limpio y cronológico.
  - Validar que las rutas de imágenes referenciadas en `content-queue/` existan antes de proponer o ejecutar un renderizado.
  - Respetar las proporciones exactas: `1080x1350` (4:5) para feed/carruseles y `1080x1920` (9:16) para stories/reels, manteniendo un espacio negativo mínimo del 15%.

- ⚠️ **Pregunta antes (Requiere Aprobación Obligatoria):**
  - **Generar cualquier contenido multimedia** (renderizar lotes de imágenes, carruseles, historias o reels), presentando primero el guion/copywriting y la estructura visual.
  - **Escribir o modificar código** (nuevas plantillas, cambios en scripts de renderizado, ajustes en `tokens.css` o esquemas JSON).
  - **Incorporar nuevas estrategias, librerías o dependencias** en `package.json`.

- 🚫 **Nunca:**
  - Iniciar la producción de código o archivos multimedia sin haber pasado por la fase de planeación y recibido confirmación explícita.
  - Omitir el registro en `MEMORY.md` tras aplicar un cambio, probar una nueva estrategia o integrar una herramienta nueva.
  - Borrar o sobrescribir archivos originales dentro de `assets/raw-photos/`.
  - Añadir lenguaje promocional, promesas vacías o exceso de emojis en los borradores presentados para aprobación.
