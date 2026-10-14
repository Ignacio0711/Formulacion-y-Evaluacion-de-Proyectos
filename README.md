# Parte B. Trabajo práctico: sistema de gestión de turnos

## Situación planteada

Un consultorio médico o profesional organiza actualmente sus turnos de manera manual en planillas de papel. La persona encargada necesita una solución informática sencilla para consultar los turnos asignados a cada día, evitar duplicados en el mismo horario y obtener una lista ordenada de atención.

Para cumplir con esta consigna, su equipo deberá formular una solución pequeña, crear un prototipo funcional asistido por inteligencia artificial y evaluar formalmente su viabilidad técnica y económica.

**Advertencia importante:** Bajo ninguna circunstancia debe construir un sistema clínico complejo ni utilizar datos reales de pacientes reales; toda la información manipulada debe ser absolutamente ficticia.

## Actividades y entregables obligatorios

| Paso | Qué debe hacer usted | Entregable correspondiente |
| --- | --- | --- |
| **1. Formular** | Definir el problema principal, los usuarios, el objetivo, el alcance exacto y los criterios de éxito. | Planilla 1 (Versión del equipo) |
| **2. Definir pruebas** | Elegir entre 3 y 5 funciones clave y describir detalladamente cómo comprobará su correcto funcionamiento. | Planilla 2 (Versión del equipo) |
| **3. Crear prototipo** | Utilizar IA para generar el código, registrar las solicitudes realizadas, los resultados obtenidos y el tiempo insumido. | Prototipo funcional y Planilla 3 |
| **4. Probar** | Ejecutar las pruebas planificadas, registrando explícitamente qué funciona, qué falla y qué es necesario corregir. | Resultados detallados de pruebas |
| **5. Estimar** | Estimar mediante la técnica PERT el esfuerzo de las actividades pendientes, justificando rigurosamente los valores O, M y P. | Planilla 4 (Cálculos PERT) |
| **6. Comparar** | Estimar el mismo alcance de desarrollo trabajando con asistencia de IA y sin ella, distinguiendo claramente los datos observados de los supuestos. | Planilla 5 (Comparación de escenarios) |
| **7. Evaluar** | Calcular los costos totales del proyecto, identificar los riesgos principales, proponer mitigaciones y emitir una recomendación fundamentada. | Planilla 6 e Informe final escrito |

### Funcionalidades posibles a seleccionar (Elija entre 3 y 5)

* Registrar un turno indicando fecha, hora y nombre de paciente ficticio.
* Consultar de forma rápida los turnos programados para un día específico.
* Cambiar o cancelar un turno existente en la agenda.
* Detectar y evitar turnos duplicados asignados para el mismo horario y profesional.
* Impedir obligatoriamente que se guarden registros con campos obligatorios vacíos.

### Pruebas sugeridas para su validación

| Prueba a ejecutar | Qué debe comprobar el alumno |
| --- | --- |
| **Registrar un turno válido** | El turno ingresado aparece correctamente reflejado en la agenda general. |
| **Consultar un día sin turnos** | El sistema informa de manera clara que no existen turnos programados para esa fecha. |
| **Omitir un dato obligatorio** | El sistema bloquea la acción y no permite guardar el registro incompleto. |
| **Intentar crear un turno duplicado** | El sistema aplica la regla de validación definida por el equipo para rechazar el traslape. |
| **Cancelar un turno** | El turno seleccionado deja de aparecer en el listado de turnos activos. |

**Criterio orientativo:** No incluya ninguna función dentro de su prototipo si no puede explicar con precisión matemática y lógica cómo comprobar su correcto funcionamiento mediante pruebas empíricas. Debe registrar siempre los resultados reales obtenidos.

---

## Plantillas vacías para completar por el equipo

### Planilla 1. Formulación y alcance

| Campo | Respuesta detallada del equipo |
| --- | --- |
| **Problema** | Cuesta organizar los turnos para paciente sin duplicado |
| **Usuario** | Secretaria/o recepcionnista |
| **Objetivo** | Registrar o asignar turnos a pacientes sin tener problemas de duplicados |
| **Funcionalidades incluidas** | Registrar un turno indicando fecha, hora y nombre de paciente ficticio.<br>Cambiar o cancelar un turno existente en la agenda.<br>Detectar y evitar turnos duplicados asignados para el mismo horario y profesional. |
| **Funcionalidades excluidas** | Historias clinicas, gestion de obras sociales y pagos. |
| **Criterio de éxito** | Rechazo al 100% de los intentos de duplicacion de horarios. |
| **Supuestos y restricciones** | odos los datos de pacientes seran estrictamente ficticios y las pruebas se realizan en el prototipo. |

### Planilla 2. Funcionalidades y pruebas

| Funcionalidad | Cómo se probará (Procedimiento) | Resultado esperado | Resultado observado (Real) |
| --- | --- | --- | --- |
| **1.** |  |  |  |
| **2.** |  |  |  |
| **3.** |  |  |  |
| **4.** |  |  |  |
| **5.** |  |  |  |

### Planilla 3. Registro de uso de IA

| Tarea de desarrollo | Solicitud o *prompt* enviado a la IA | Resultado obtenido y corrección requerida | Tiempo insumido (min) |
| --- | --- | --- | --- |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

### Planilla 4. Estimación de esfuerzo con PERT

| Actividad pendiente | $O$ (Optimista - h) | $M$ (Más probable - h) | $P$ (Pesimista - h) | Esfuerzo $E = \frac{O + 4M + P}{6}$ | Justificación técnica del equipo |
| --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
| **Total** |  |  |  |  | **Esfuerzo total estimado:** |

### Planilla 5. Comparación de escenarios de desarrollo

| Escenario de trabajo | $O$ (h) | $M$ (h) | $P$ (h) | $E$ PERT | Base de la estimación |
| --- | --- | --- | --- | --- | --- |
| **Sin asistencia de IA** |  |  |  |  |  |
| **Con asistencia de IA** |  |  |  |  |  |

* **Reducción o incremento estimado del esfuerzo:** _________ %
* **¿Qué datos observaron empíricamente y cuáles supusieron?:**
---



### Planilla 6. Costos, riesgos y decisión final

| Concepto económico / operativo | Valor calculado |
| --- | --- |
| **Esfuerzo total estimado ($E$ en h-persona)** |  |
| **Tarifa de referencia por hora-persona** |  |
| **Costo total del esfuerzo** |  |
| **Otros costos asociados (infraestructura, herramientas, etc.)** |  |
| **Costo total estimado del proyecto** |  |

| Riesgo identificado | Probabilidad (Baja/Media/Alta) | Impacto (Bajo/Medio/Alto) | Medida concreta de respuesta o mitigación |
| --- | --- | --- | --- |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

**Decisión final adoptada por el equipo:** (Seleccione o indique: *continuar / modificar el alcance / descartar el proyecto*)

**Justificación detallada:** ¿Qué evidencia empírica respalda la decisión tomada por ustedes y qué aspectos particulares faltan comprobar en el prototipo?

---

---

---

## Fórmulas matemáticas obligatorias que usted debe aplicar

* **Esfuerzo por actividad individual ($E_i$):**

$$E_i = \frac{O_i + 4M_i + P_i}{6}$$


* **Esfuerzo total del proyecto ($E_{\text{total}}$):**

$$E_{\text{total}} = \sum E_i$$


* **Costo monetario del esfuerzo:**

$$\text{Costo} = E_{\text{total}} \times \text{Tarifa por hora-persona}$$


* **Porcentaje de reducción del esfuerzo mediante el uso de IA:**

$$\text{Reducción (\%)} = \frac{E_{\text{sin IA}} - E_{\text{con IA}}}{E_{\text{sin IA}}} \times 100$$



*Nota aclaratoria:* Si el resultado de la comparación porcentual arroja un valor negativo, significa que la estimación realizada utilizando IA le insumió un esfuerzo mayor que haber desarrollado el proyecto sin ella.

---

## Criterios de evaluación

| Criterio de calificación | Ponderación porcentual |
| --- | --- |
| **Formulación del problema y claridad del alcance** | 20 % |
| **Uso crítico de las herramientas de IA y rigor en las pruebas** | 20 % |
| **Corrección en los cálculos matemáticos y justificación del método PERT** | 25 % |
| **Evaluación realista de costos, identificación de riesgos y solidez de la decisión** | 25 % |
| **Claridad, formalidad y prolijidad del informe final escrito** | 10 % |

**Aclaración importante:** Un prototipo funcional que falle o presente errores durante las pruebas **puede formar parte de un excelente trabajo práctico**, siempre y cuando el equipo presente evidencias claras de las pruebas realizadas, identifique con honestidad las limitaciones técnicas encontradas y fundamente con rigor qué acciones correctivas se deberían tomar. Tenga presente que un prototipo vistoso pero no probado rigurosamente no demuestra por sí solo que un proyecto de software sea viable.

---

## Estructura requerida para el informe final escrito

El informe escrito debe tener una extensión aproximada de **2 a 4 páginas**, redactado con rigor formal, donde usted y su equipo respondan de manera estructurada a las siguientes preguntas clave:

1. ¿Qué problema concreto busca resolver la solución informática desarrollada?
2. ¿Qué funcionalidades se incluyeron explícitamente en el alcance y qué quedó fuera del proyecto?
3. ¿Qué funcionó correctamente y qué falló de manera imprevista durante la ejecución de las pruebas empíricas?
4. ¿Cuál es el esfuerzo total en horas-persona, la duración estimada de calendario y el costo monetario calculado para el proyecto?
5. ¿Cuáles son los riesgos técnicos y operativos más importantes identificados por el equipo?
6. ¿Qué diferencias cuantitativas y cualitativas se estiman entre trabajar con asistencia de inteligencia artificial frente a hacerlo sin ella?
7. Desde el punto de vista técnico y económico, ¿conviene continuar con el desarrollo, modificar el alcance o descartar por completo el proyecto? Justifique su postura con los datos obtenidos.

**Conclusión conceptual:** Formular y evaluar un proyecto de software comienza siempre por comprender a fondo la naturaleza del problema que se pretende resolver. Las herramientas de inteligencia artificial pueden asistirlo con velocidad para generar prototipos de código mediante *vibe coding*, pero es responsabilidad ineludible del equipo técnico definir correctamente el alcance, probar rigurosamente los resultados obtenidos, estimar formalmente el trabajo pendiente utilizando métodos cuantitativos como PERT y justificar con argumentos sólidos cualquier decisión que se adopte en el ámbito profesional.