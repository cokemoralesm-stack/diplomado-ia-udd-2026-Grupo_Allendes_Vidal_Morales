# Ficha de proyecto — [nombre de tu proyecto]

*Documento vivo. Se completa clase a clase — es tu model card en versión de borrador. Súbelo a tu repo como `docs/ficha_proyecto.md`.*

## 1. Nombre interno del proyecto

Clasificador y Analizador de Feedback para Proyectos de Diseño

## 2. Las agencias y equipos de diseño reciben grandes volúmenes de comentarios y reseñas de clientes sobre sus campañas visuales.
Clasificar manualmente si un comentario es positivo, negativo o neutro toma mucho tiempo y puede ser subjetivo. 
Esto dificulta detectar rápidamente qué propuestas necesitan ajustes urgentes antes de su publicación.

Heredado de la Unidad 2 — o inventado si no tienes uno (ver "¿Y si no tienes problema heredado?" en `Clase_22_contenido.md`).

## 3. Usuario / cliente objetivo

¿Para quién es esto? 
Directores creativos, diseñadores y gestores de proyectos (account managers) en agencias de publicidad o estudios de diseño.

¿Qué necesita?
Una herramienta que categorice automáticamente el nivel de satisfacción del cliente respecto a las entregas gráficas y conceptos visuales.

¿Por qué hoy no lo tiene resuelto?
Actualmente la revisión se realiza de forma manual leyendo texto por texto, lo cual ralentiza los tiempos de respuesta e impide priorizar los cambios críticos.


## 4. Tipo de modelo que vas a necesitar

- [ ] Generativo (crea contenido nuevo: texto, imagen, audio, video)
- [ ] Analítico (clasifica, predice, extrae)
- [ ] Ambos (pipeline combinado)

## 5. Modelos candidatos (2-3 concretos)

Midjourney (v6 / v7): Excelente para concept art, mockups, fotografía publicitaria y exploración estética de altísima calidad.

Adobe Firefly (Firefly Image 3): Integrado nativamente en Photoshop e Illustrator; ideal para generación comercial con derechos de uso seguros y gráficos vectoriales.

Stable Diffusion 3.5 (de Stability AI en Hugging Face): Modelo de código abierto muy versátil para generar imágenes, aplicar ControlNet (mantener poses/estructuras de diseño) y personalizar estilos con LoRAs.

DALL-E 3 / DALL-E 4 (OpenAI): Ideal para traducir instrucciones complejas en ilustraciones detalladas y diseño de empaques/packaging.

## 6. Roadmap del proyecto (se completa clase a clase)

- [ ] Clase 23 — Datasheet del dataset (`docs/datasheet_v1.md`)
- [ ] Clase 24 — Hallazgos NotebookLM (`docs/hallazgos_notebooklm.md`)
- [ ] Clase 25 — System prompt (`docs/system_prompt_v3.md`)
- [ ] Clase 26 — Modelos HF candidatos (`docs/modelos_hf_candidatos.md`)
- [ ] Clase 27 — Sistema visual (`docs/sistema_visual.md`)
- [ ] Clase 28 — Arquitectura del agente (`docs/arquitectura_agente.md`)
- [ ] Clase 29 — Video generativo (`docs/video_generativo.md`)
- [ ] Clase 30 — Casos de uso Hermes (`docs/hermes_casos_uso.md`)
- [ ] Clase 31 — Antigravity Loop + cierre (`docs/antigravity_loop.md`)

## 7. Notas para Mauricio (Unidad 4)

Qué necesita saber quien reciba este proyecto en la próxima unidad:
