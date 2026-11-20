# MEMORY.md — Motor de Contenido Social Media
Memoria persistente entre sesiones. **Regla estricta: Máximo 50 líneas.** Resume o purga lo obsoleto al actualizar.

## Estado actual
- Fase 0 (Arquitectura): Definición de identidad visual (*Quiet Luxury* + disciplina estoica) y reglas de flujo en `SKILL.md`.
- Pendiente inicializar estructura de carpetas (`assets/raw-photos`, `templates`, `content-queue`, `output`) y stack ligero tras aprobación.

## Aprendizajes y errores a evitar
- Evitar sobrecarga de texto en slides (máx. 25-35 palabras) y respetar safe zones en 9:16 (15% superior, 20% inferior).
- Trampa habitual: el modelo tiende a incluir emojis o CTAs comerciales ("link en bio", "compra"). Prohibido; el objetivo es autoridad pura sin venta.
- Las fotos crudas locales varían en luz; aplicar siempre tratamiento sutil de contraste/desaturación para cohesión con la paleta.

## Decisiones (y por qué)
- **Paleta fija de 3 tonos (`#121212`, `#F4F2ED`, `#A68A64`):** Proyecta sobriedad, lujo silencioso y rigor mental sin ruido visual.
- **Arquitectura desacoplada (HTML/CSS + JSON/MD):** Permite iterar plantillas sin tocar los guiones ni depender de herramientas externas pesadas.
- **Protocolo de Gatekeeping obligatorio:** Todo código, estrategia o renderizado multimedia requiere planeación previa (por qué, cómo, beneficio) y aprobación explícita antes de ejecutarse.
- **Protección de activos:** Nunca modificar `assets/raw-photos/`; exportar todo a `output/` (ignorado en Git).

## Próximos pasos
- Presentar propuesta inicial de árbol de directorios y stack ligero (Node.js + Playwright/Sharp + FFmpeg) para aprobación del usuario.
- Crear `tokens.css` y la primera plantilla base (`carousel-base.html`).
- Ejecutar prueba de renderizado (`npm run test:render`) con fotos locales de muestra.
