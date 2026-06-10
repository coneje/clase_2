# Resumen Ejecutivo: Ingeniería de Requerimientos y Metodologías Ágiles

## 1. ¿Qué es un Requerimiento?
Es una propiedad **documentada** y **verificable** que un sistema debe cumplir para resolver un problema. Se divide en tres niveles de abstracción:
* **Necesidad del usuario:** El problema informal (*lo que le duele al usuario*).
* **Requerimiento del sistema:** La traducción formal (*lo que debe hacer la app*).
* **Especificación técnica:** El detalle para el programador (*cómo se hace a nivel de código*).

---

## 2. Tipos de Requerimientos: RF vs. RNF
* **Requerimientos Funcionales (RF - El QUÉ):** Las acciones y tareas concretas que el sistema debe realizar (ej: calcular, guardar, enviar).
* **Requerimientos No Funcionales (RNF - El CÓMO):** Las características de calidad y restricciones del sistema (ej: velocidad, seguridad, estabilidad). **Regla de oro:** Todo RNF debe ser medible.

---

## 3. Atributos de Calidad (Norma ISO/IEC 25010)
Son las categorías generales que determinan la calidad del software. La norma define 8 pilares:
1. **Adecuación funcional** (si hace lo que debe).
2. **Eficiencia de desempeño** (velocidad y recursos).
3. **Compatibilidad** (interacción con otros sistemas).
4. **Usabilidad** (facilidad de uso).
5. **Confiabilidad** (que no se caiga).
6. **Seguridad** (protección de datos).
7. **Mantenibilidad** (facilidad para mejorar el código).
8. **Portabilidad** (funcionar en distintos dispositivos).

---

## 4. Aplicación Práctica: Caso "SchoolEats"
Para diseñar una app que solucione las filas y el desorden en la cafetería de un colegio, el proceso de análisis sigue tres pasos:
* **Identificar Stakeholders:** Definir los actores clave (Estudiantes, Cocineros, Rector, Padres).
* **Elicitación:** Aplicar técnicas para levantar información (encuestas para grupos grandes, entrevistas para decisores, observación para procesos de cocina).
* **Descubrir Necesidades:** Entender los dolores de cada actor (los estudiantes quieren pagar y reservar desde el celular; los cocineros necesitan ver los pedidos en una pantalla; el rector necesita reportes).

---

## 5. Historias de Usuario (Metodologías Ágiles)
Es la forma ágil de redactar requerimientos desde la perspectiva del usuario enfocado en el beneficio.
* **Fórmula:** **Como** [usuario], **quiero** [acción], **para** [beneficio].
* **Calidad (INVEST):** Deben ser Independientes, Negociables, Valiosas, Estimables, Pequeñas (*Small*) y Testeables.
* **Criterios de Aceptación:** Condiciones para dar la tarea por terminada, redactadas en formato **Dado que / Cuando / Entonces** (ej: qué pasa si el usuario se queda sin internet).