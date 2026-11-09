# Asignación de unidades de respuesta

## 1. Objetivo

Permitir que RENAGE asigne unidades de respuesta a los incidentes registrados, tomando en cuenta la disponibilidad de los recursos y la prioridad de cada emergencia. El objetivo principal es agilizar la atención y reducir los riesgos para la población.

## 2. Descripción del proceso

Cuando se registra un incidente, el sistema consulta las unidades de respuesta disponibles. Si existe una unidad adecuada, se realiza la asignación y se actualiza el estado del incidente a «En Ruta».

Si no existen unidades disponibles, el incidente se agrega a una fila de espera organizada por prioridad. Cuando una unidad queda libre, el sistema revisa los incidentes pendientes y asigna el recurso al que requiera atención más urgente y sea compatible con sus capacidades.

## 3. Reglas de funcionamiento

1. Solo se asignan unidades disponibles y adecuadas para atender el incidente.
2. Cada incidente debe contar con información suficiente para determinar su prioridad.
3. Si no hay unidades disponibles, el incidente se registra en la fila de espera.
4. Los incidentes se organizan según su gravedad y nivel de riesgo.
5. Cuando una unidad queda libre, se revisa la fila de espera y se selecciona el incidente de mayor prioridad que pueda atender.
6. Una unidad no puede tener dos asignaciones incompatibles al mismo tiempo.
7. Toda asignación debe quedar registrada.
8. El estado cambia a «En Ruta» cuando la unidad inicia su desplazamiento.
9. Los cambios de estado se conservan en el historial.

## 4. Criterios de prioridad

- **Crítica:** existe riesgo inmediato para la vida de las personas.
- **Alta:** emergencia grave que requiere atención urgente.
- **Media:** situación que necesita atención, pero sin peligro inmediato.
- **Baja:** incidente que puede esperar mientras se atienden emergencias más graves.

También se considera el tiempo de espera, la cantidad de personas en riesgo y el tipo de emergencia.

## 5. Entidades relacionadas

- **INCIDENTE:** almacena la información del reporte.
- **UNIDAD:** contiene los recursos de respuesta y su disponibilidad.
- **ASIGNACIÓN:** registra qué unidad atiende cada incidente.
- **HISTORIAL:** conserva los cambios realizados.
- **FILA_ESPERA:** propuesta para almacenar incidentes pendientes, prioridad, fecha de ingreso y estado.

## 6. Resultado esperado

La funcionalidad permitirá organizar mejor los recursos disponibles, atender primero las emergencias de mayor gravedad y agilizar la respuesta ante desastres naturales o provocados.

## 7. Diagrama de flujo

Consultar el archivo `Asignacion_Unidades_Respuesta.png` para visualizar el proceso de asignación y atención de incidentes.
