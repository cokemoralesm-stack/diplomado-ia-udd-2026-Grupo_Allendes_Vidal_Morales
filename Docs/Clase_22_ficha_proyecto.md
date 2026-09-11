# Ficha de proyecto — Provocador Creativo Disruptivo 

## 1\. Nombre interno del proyecto

Director Creativo Disruptivo (IA como Asistente Iterativo) 

## 2\. Problema (2-3 frases)

En el día a día de una agencia publicitaria, la conceptualización de grandes campañas requiere un proceso largo y pesado de investigación y descarte inicial, cayendo frecuentemente en ideas cliché, predecibles ("workslop") y reuniones poco eficientes. Esto genera un gran cuello de botella y bloqueo de "página en blanco" para el equipo creativo, consumiendo horas de trabajo en etapas iniciales que podrían aprovecharse en pulir la estrategia final. 

## 3\. Usuario / cliente objetivo

El usuario principal es el **Director Creativo** (y los equipos de ideación de la agencia: redactores, diseñadores y directores de arte). Necesita una herramienta ágil que elimine la fricción de empezar desde cero y filtre de inmediato las propuestas obvias. Hoy no lo tiene resuelto porque las herramientas de IA estándar suelen entregar respuestas lógicas, planas y predecibles. 

## 4\. Tipo de modelo que vas a necesitar

- [x] Generativo (crea contenido nuevo: texto, imagen, audio, video)  
- [ ] Analítico (clasifica, predice, extrae)  
- [ ] Ambos (pipeline combinado)

## 5\. Modelos candidatos (2-3 concretos)

**1- Gemini 1.5 Pro / Flash (vía Google AI Studio):** Elegido por su amplia ventana de contexto,      flexibilidad en el ajuste del sistema (system prompt) y capacidad para manejar parámetros clave como la temperatura creativa para forzar respuestas divergentes.

**2- GPT-4o (OpenAI):** Como alternativa para pruebas comparativas en generación de texto creativo y razonamiento conceptual.

**3-Claude 3.5 Sonnet (Anthropic):** Candidato para evaluación por su buen desempeño en redacción de manifiestos y tono de voz con matices creativos.

## 6\. Roadmap del proyecto (se completa clase a clase)

- [x] Clase 23 — Datasheet del dataset (`docs/datasheet_v1.md`)  
- [x] Clase 24 — Hallazgos NotebookLM (`docs/hallazgos_notebooklm.md`)  
- [x] Clase 25 — System prompt (`docs/system_prompt_v3.md`)  
- [x] Clase 26 — Modelos HF candidatos (`docs/modelos_hf_candidatos.md`)  
- [x] Clase 27 — Sistema visual (`docs/sistema_visual.md`)  
- [x] Clase 28 — Arquitectura del agente (`docs/arquitectura_agente.md`)  
- [ ] Clase 29 — Video generativo (`docs/video_generativo.md`)  
- [ ] Clase 30 — Casos de uso Hermes (`docs/hermes_casos_uso.md`)  
- [x] Clase 31 — Antigravity Loop \+ cierre (`docs/antigravity_loop.md`)

## 7\. Notas para Mauricio (Unidad 4\)

**Filosofía del proyecto ("Human x Machine"):** La aplicación está pensada para actuar como un provocador conceptual y un compañero de pensamiento iterativo, no para entregar la campaña terminada. La IA aporta el 20% divergente para romper moldes y el creativo humano aporta el juicio crítico, empatía y sentido de negocio final.

**Manejo de la Creatividad/Temperatura:** La disruptividad se controla mediante un deslizador visual de "Temperatura Disruptiva (°C)" en la app, que simula el nivel de riesgo creativo del concepto generado.

**Estructura del Output esperada:** Cada propuesta entrega 3 conceptos de ruptura (Ángulo Inusual, Manifiesto Visceral de 3 líneas y Activación Disruptiva en el mundo real) junto a una Matriz de Provocación con dilemas e interrogantes para que el equipo debata.

**Ajustes visuales/UX pendientes:** En la interfaz de Google AI Studio se implementó un flujo tipo dashboard creativo con presets de briefing precargados (Fintech, Movilidad, Citas, SaaS, etc.). Se recomienda mantener el tono publicitario de la interfaz y cuidar siempre que las propuestas se alineen con la identidad y guías de la marca sobre la cual se trabaje

