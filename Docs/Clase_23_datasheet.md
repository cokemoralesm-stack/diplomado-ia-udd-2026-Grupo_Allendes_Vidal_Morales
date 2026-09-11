# **Datasheet — Provocador Creativo Disruptivo** 

## **1\. Motivación**

* ¿Para qué usarás este dataset en tu proyecto?

Usaremos este dataset para alimentar y afinar el pensamiento de nuestro asistente conceptual. La idea es que la IA reconozca cuáles han sido las estructuras de campañas anteriores, entienda los patrones de retroalimentación de nuestros clientes (lo que les gusta, lo que aprueban y lo que descartan) y pueda usar esta información como base para proponer ángulos inusuales sin perder de vista los objetivos reales de negocio. 

* ¿Quién lo creó originalmente? 

Fue recopilado e integrado por nuestro propio equipo de proyecto, pero principalmente Marco Vidal quien tiene acceso a la empresa y al histórico de proyectos. 

## **2\. Composición**

* Tipo de datos:

Mezcla de datos cualitativos y estructurados (texto de briefings, propuestas conceptuales, minutas de retroalimentación de clientes, reportes de desempeño de campañas y notas internas de evaluación). 

* Cantidad de instancias:

Un registro histórico compuesto por aproximadamente 80 a 100 casos completos de campañas anteriores junto con sus respectivas evaluaciones y algunos con comentarios de clientes.

* ¿Hay subgrupos identificables? (edad, género, región, otro):

Sí, las instancias se organizan principalmente por **industrias o sectores de clientes** (Fintech, Movilidad, Tecnología/SaaS, Consumo Masivo) y por **tipo de resultado de propuesta** (campañas aprobadas a la primera, propuestas iteradas y conceptos rechazados por el cliente). 

## **3\. Recolección**

* ¿Cómo se recolectaron? 

A través de la extracción interna desde la base de datos de campañas pasadas de la agencia (briefs, propuestas presentadas) e integrando directamente el histórico de *feedback* y evaluaciones consolidadas que se recibieron de los clientes tras las reuniones de presentación. 

* ¿Cuándo?:

Se recopiló la información correspondiente a los proyectos ejecutados por la agencia durante los últimos 24 meses. 

* ¿Se pidió consentimiento?:

Sí. La información proviene de la relación comercial habitual de los clientes con la agencia, utilizando únicamente datos internos de trabajo creativo y omitiendo información financiera confidencial o nombres de personas específicas para respetar la privacidad contractual. 

## **4\. Sesgos identificados (mínimo 2\)**

* Sesgo 1:

Como el *feedback* tradicional del cliente suele ser conservador o buscar soluciones más convencionales, el dataset contiene una tendencia a favorecer ideas "seguras". Si la IA aprende únicamente de lo que el cliente aceptó en el pasado, podría volverse predecible y generar respuestas cliché.

* Sesgo 2:

Tenemos mayor concentración de datos en ciertos sectores donde la agencia ha trabajado más (como consumo masivo o servicios), lo que podría restar frescura al intentar conceptualizar para industrias no tradicionales o emergentes. 

## **5\. Estrategias de mitigación (mínimo 2\)**

* Estrategia 1:

En el diseño del sistema prompt y la interfaz, incorporamos la instrucción explícita de descartar las primeras ideas lógicas o habituales que aparezcan en el dataset. Usamos la información histórica para saber qué es lo "obvio" y forzar al modelo a explorar el 20% divergente. 

* Estrategia 2:

Para evitar caer en la zona de confort de cada industria, obligamos a la IA a cruzar los datos del brief con tensiones culturales globales y disciplinas ajenas al marketing, asegurando que la referencia histórica no limite la originalidad. 

## **6\. Uso recomendado / desaconsejado**

* Para qué SÍ debería usarse:

- Para destrabar la etapa de ideación inicial y superar el bloqueo.  
- Para entender qué errores conceptuales o enfoques trillados ya se han intentado antes en ciertas categorías. 


* Para qué NO debería usarse:

- Para automatizar de forma 100% autónoma el envío de propuestas finales al cliente sin revisión humana.  
- Como fuente única de verdad para decisiones.

## **7\. Notas para Mauricio (Unidad 4\)**

* El foco de este dataset no es ser gigante, sino relevante para el flujo creativo publicitario. 

* Quien lea este dataset debe recordar que el *feedback* del cliente sirve para entender los límites del contexto, pero no debe frenar la capacidad del modelo para proponer ideas de ruptura. La base de datos orienta; la IA provoca; el creativo decide. 