# Informe de Análisis Comparativo de Modelos de Inteligencia Artificial

**Integrantes (Grupo de Estudiantes):**
* Vidal
* Allendes
* Morales

---

## 1. Resumen Ejecutivo

En este informe analizamos tres modelos de Inteligencia Artificial bastante distintos entre sí que nos llamaron la atención por la variedad de tareas que realizan: **LTX-Video** (enfocado en generación de video), **qwen2.5-0.5b-byomtest** (un modelo de texto o LLM muy liviano) y **MOSS-SoundEffect-v2.0** (diseñado exclusivamente para crear efectos de sonido).

A continuación, presentamos nuestro análisis detallado sobre cómo se comporta cada uno, sus pros, sus contras y las limitaciones que detectamos al utilizarlos.

---

## 2. Análisis Individual de los Modelos

### 🎥 Modelo 01: LTX-Video (Lightricks)

* **¿Qué es?:** Es un modelo pensado para crear secuencias de video a partir de texto o instrucciones.
* **Tamaño:** Tiene cerca de 2 mil millones de parámetros (2B), lo que lo hace un modelo mediano dentro del mundo de la generación de video.
* **Licencia:** Utiliza una licencia propia permisiva (*Open Weights*), lo que significa que el código y los pesos están disponibles para probar y usar.
* **Nuestro Análisis y Experiencia:**
  * **Lo bueno:** Es increíble lo rápido que crea movimientos visuales y secuencias de video directamente desde una instrucción de texto.
  * **Puntos débiles / Limitaciones:** Como se indica en su documentación, el video viene totalmente "mudo" (sin audio integrado). Además, notamos que le cuesta mucho dibujar detalles pequeños como manos, caras lejanas o texto que sea legible en pantalla. Se nota que la IA a veces "inventa" o deforma los dedos y rostros pequeños.

---

### 📝 Modelo 02: collagen/qwen2.5-0.5b-byomtest

* **¿Qué es?:** Es un modelo de lenguaje (LLM) miniaturizado, diseñado para procesar y responder texto.
* **Tamaño:** Es muy pequeño, de solo 0.5B de parámetros (unos 490 millones).
* **Licencia:** Apache-2.0 (completamente libre y de código abierto).
* **Nuestro Análisis y Experiencia:**
  * **Lo bueno:** Al ser un modelo tan compacto, corre súper rápido y no requiere una computadora ultrapotente o con una tarjeta gráfica gigante para funcionar.
  * **Puntos débiles / Limitaciones:** Exige tener las librerías del código bien actualizadas (como `transformers` en Python superior a la versión 4.37.0), porque si no, arroja errores de compatibilidad de inmediato (`KeyError: 'qwen2'`). Además, al ser tan pequeño, sus respuestas pueden ser un poco más simples comparadas con IAs más grandes.

---

### 🔊 Modelo 03: MOSS-SoundEffect-v2.0 (OpenMOSS-Team)

* **¿Qué es?:** Un modelo especializado únicamente en generar efectos de sonido (foley, ruidos ambientales, explosiones, pasos, etc.).
* **Tamaño:** 1.3 mil millones de parámetros (1.3B).
* **Licencia:** Apache-2.0.
* **Nuestro Análisis y Experiencia:**
  * **Lo bueno:** Cumple súper bien su función específica. Es ideal si estás editando un video o juego y necesitas un sonido de fondo rápido que no tenga derechos de autor.
  * **Puntos débiles / Limitaciones:** Está hiperespecializado. No sirve para crear música completa, ni para hacer hablar a personajes (voz humana/locución), ni mucho menos para entender o responder preguntas de texto.

---

## 3. Tabla Comparativa de Resumen

| Criterio | Modelo 01 (LTX-Video) | Modelo 02 (Qwen2.5 BYOM) | Modelo 03 (MOSS SoundEffect) |
| :--- | :--- | :--- | :--- |
| **Área principal** | Generación de Video | Texto / Lenguaje (LLM) | Efectos de Audio / Sonido |
| **Desarrollador** | Lightricks | collagen | OpenMOSS-Team |
| **Tamaño (Parámetros)** | ~2B (Mediano) | 0.5B (Muy pequeño) | 1.3B (Mediano) |
| **Licencia** | LTX-Video License | Apache 2.0 | Apache 2.0 |
| **Principal Traba** | Detalle en manos y rostros / Sin audio | Errores de compatibilidad de código | Solo hace efectos de sonido |

---

## 4. Conclusión del Grupo

Como grupo de estudiantes, nos dimos cuenta de que hoy en día no existe una "IA que lo haga todo perfecta", sino que cada herramienta se especializa en un nicho super específico. 

Mientras que **LTX-Video** te resuelve la parte visual pero sufre con los detalles finos y requiere que busques el audio por otro lado, **MOSS-SoundEffect** es el complemento perfecto para ponerle ambiente y sonidos a esos videos. Por otro lado, un modelo de texto tan ligero como **Qwen2.5** nos demuestra que se pueden tener IAs funcionales en computadores normales sin gastar una fortuna, siempre y cuando mantengamos los programas actualizados.

En resumen, el verdadero truco al trabajar con Inteligencia Artificial no es buscar una sola herramienta milagrosa, sino aprender a combinar varias IAs especializadas para armar un proyecto completo (video, sonido y guion de texto).
