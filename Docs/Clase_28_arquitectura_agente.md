# Reflexión de Aprendizaje — Ejercicios de Accesibilidad Web

**Nombre del estudiante:** _(completar)_
**Tema:** Análisis y documentación de mejoras de accesibilidad en contenido visual

---

## Introducción

En esta actividad realicé dos ejercicios relacionados con la accesibilidad web, aplicados sobre una imagen publicitaria (una botella de Coca-Cola con splash y hielo). El objetivo fue identificar problemas de accesibilidad en contenido visual y luego documentarlos de forma clara y estructurada, tal como se haría en un entorno profesional de diseño o desarrollo web.

---

## Ejercicio 1: Análisis de accesibilidad de una imagen

En este primer ejercicio, se me pidió analizar una imagen y proponer tres mejoras de accesibilidad. Para esto, evalué la imagen pensando en distintos tipos de usuarios y situaciones, no solo en cómo se ve visualmente, sino en cómo la percibiría alguien con una discapacidad visual, cognitiva o motriz, o alguien que use tecnologías de asistencia.

Los tres puntos que identifiqué fueron:

1. **Texto alternativo (alt text):** Aprendí que las imágenes con contenido informativo (no solo decorativo) necesitan una descripción textual que un lector de pantalla pueda comunicar a personas con discapacidad visual. Esto me hizo entender la diferencia entre una imagen decorativa (`alt=""`) y una imagen informativa, que requiere una descripción concreta y útil.

2. **Contraste de texto superpuesto:** Analicé que si esta imagen se usa como fondo con texto encima (como en un banner publicitario), el contraste entre el texto y las distintas zonas de la imagen (clara arriba, oscura abajo) podría no cumplir con los estándares de accesibilidad (WCAG). Esto me permitió aplicar el concepto de la relación de contraste mínima (4.5:1) que había visto de forma teórica, ahora en un caso práctico.

3. **Movimiento y animación:** Consideré qué pasaría si esta imagen se convirtiera en una animación o video (por ejemplo, mostrando el splash en movimiento). Aquí reforcé conceptos sobre epilepsia fotosensible y la importancia de respetar las preferencias del sistema del usuario, como `prefers-reduced-motion`, algo que no había aplicado antes en un ejemplo real.

**Lo que aprendí:** Que la accesibilidad no es solo "agregar un texto alternativo", sino un análisis integral que contempla distintos tipos de discapacidad y distintos contextos de uso (imagen estática, imagen con texto, imagen animada).

---

## Ejercicio 2: Documentación en formato Markdown

En el segundo ejercicio, se me pidió transformar el análisis anterior en un archivo `.md` (Markdown) descargable. Esto implicó:

- Organizar la información en secciones claras con títulos y subtítulos.
- Usar bloques de código para mostrar ejemplos concretos (el alt text sugerido y el snippet de CSS con `prefers-reduced-motion`).
- Aplicar buenas prácticas de estructura de documentación técnica, pensando en que otra persona (un diseñador, un desarrollador o un profesor) pudiera leer el archivo y entender rápidamente las recomendaciones sin necesidad de contexto adicional.

**Lo que aprendí:** La importancia de documentar el trabajo de forma ordenada y reutilizable. No es lo mismo dar una respuesta oral o en un chat, que dejar un documento formal que pueda ser consultado, compartido o entregado como evidencia de un análisis técnico. Markdown resultó ser una herramienta simple pero efectiva para esto, ya que permite estructurar contenido técnico (código, listas, títulos) de forma legible tanto en texto plano como cuando se renderiza.

---

## Conclusión general

Estos dos ejercicios me permitieron conectar la teoría de accesibilidad web (como las pautas WCAG) con un caso práctico y visual, algo mucho más fácil de recordar que solo leer definiciones. Además, el proceso de pasar de un análisis conversacional a un documento formal en Markdown me hizo valorar la importancia de comunicar hallazgos técnicos de manera clara, ordenada y profesional.

En resumen, esta actividad no solo reforzó conceptos de accesibilidad (alt text, contraste, animaciones), sino también una habilidad transversal importante: **documentar el trabajo propio de forma que sea útil para otros**, algo que sin duda me servirá en futuros proyectos de diseño, desarrollo web o cualquier entrega académica o profesional.

---

*Documento elaborado como reflexión personal de aprendizaje sobre accesibilidad web (WCAG 2.1).*
