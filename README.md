# Red Nacional de Gestión de Emergencias y Desastres Naturales

## 1. Problema
La desconexión y la falta de unificación en la información entre los distintos organismos de respuesta (Protección Civil, Cruz Roja, Bomberos y Hospitales) ante un desastre natural provoca retrasos críticos en la atención de rescate, duplicidad de esfuerzos y desinformación en la ciudadanía.

## 2. Objetivos
* **Objetivo General:** 
  Desarrollar una plataforma web centralizada a gran escala para coordinar la gestión de emergencias, asignación de recursos y difusión de alertas masivas geolocalizadas ante desastres naturales.
* **Objetivos Particulares:**
  1. **Diseñar** la arquitectura de datos para la recepción y clasificación en tiempo real de reportes de emergencia.
  2. **Construir** un panel de control (dashboard) con visualización geoespacial de zonas afectadas y disponibilidad de recursos de rescate.
  3. **Implementar** un algoritmo de priorización automatizada de incidentes según su nivel de severidad y criticidad.
  4. **Validar** el canal de comunicación ciudadana mediante un simulador de envío de alertas masivas de evacuación.

## 3. Alcance
* Dashboard web administrativo para operadores de Protección Civil.
* Mapa interactivo en tiempo real con incidentes geolocalizados.
* Módulo de gestión de inventario y asignación de unidades de respuesta/rescate.
* Módulo de simulación para envío de alertas públicas de evacuación.

## 4. Fuera de Alcance
* Integración física o comunicación en tiempo real con hardware IoT o sensores sísmicos reales.
* Aplicaciones móviles nativas (iOS y Android).
* Pasarelas de cobro o recaudación de donaciones monetarias.
* Trámites o convenios legales con dependencias gubernamentales reales.

## 5. MVP (Minimum Viable Product)
Un panel de control web donde un operador visualiza un mapa con incidentes reportados, filtra los eventos por prioridad de atención y asigna una unidad de rescate disponible, actualizando el estado de la atención de "Pendiente" a "En Ruta".
