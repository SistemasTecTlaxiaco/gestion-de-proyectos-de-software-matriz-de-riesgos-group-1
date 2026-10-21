# MATRIZ DE RIESGOS DEL PROYECTO — SPRINT 3

**TECNOLÓGICO NACIONAL DE MÉXICO**  
**INSTITUTO TECNOLÓGICO DE TLAXIACO**

**Carrera:** Ingeniería en Sistemas Computacionales  
**Asignatura:** Gestión de Proyectos de Software (SCG-1009)  
**Unidad:** 3. Planificación del Proyecto  
**Trabajo 3:** Matriz de Riesgos  
**Proyecto:** Sistema de Control y Comercialización de la Producción de Miel  
**Organización beneficiaria:** Unión de Productores de Miel de San Juan Ñumí, Oaxaca  
**Equipo:** UMIZOOMI  
**Metodología:** eduScrum  

**Integrantes:**

- Félix Ángel García García
- Diego Fidel Sosa Cruz
- Daniel Alejandro López Camarillo
- Luis Alexis Morales José

---

## 1. Introducción

La gestión de riesgos es un proceso fundamental en la planificación de proyectos de software, ya que permite identificar posibles situaciones que pueden afectar el cumplimiento de los objetivos, el presupuesto, los tiempos de desarrollo y la calidad del producto final.

En el proyecto Sistema de Control y Comercialización de la Producción de Miel se busca desarrollar una herramienta informática que permita administrar la información de productores, registrar cosechas, controlar el inventario y organizar los registros de comercialización.

Debido a que la organización beneficiaria se encuentra en San Juan Ñumí, Oaxaca, es necesario considerar aspectos técnicos, sociales, operativos y financieros relacionados con las condiciones de la región Mixteca.

Asimismo, se contemplan los posibles riesgos asociados con mecanismos de financiamiento Web3, como Stellar Community Fund y Drips Protocol, analizados durante el Sprint 2.

## 2. Objetivo general

Identificar, analizar, clasificar y priorizar los riesgos que pueden presentarse durante el desarrollo del Sistema de Control y Comercialización de la Producción de Miel, estableciendo estrategias de prevención, mitigación y contingencia que favorezcan el cumplimiento de los objetivos del proyecto mediante la metodología eduScrum.

## 3. Clasificación de riesgos

Se consideran tres dimensiones principales:

**Riesgos técnicos:** relacionados con errores en el software, almacenamiento de información, integridad de los registros, controles de seguridad y funcionamiento de los módulos.

**Riesgos sociales y operativos:** relacionados con las condiciones de conectividad de San Juan Ñumí, la participación de los productores, la adaptación tecnológica y la organización del equipo.

**Riesgos financieros y Web3:** relacionados con el presupuesto, los costos de infraestructura y la posibilidad de utilizar Stellar Community Fund o Drips como mecanismos de apoyo financiero.

## 4. Metodología de evaluación

Para evaluar cada riesgo se utiliza una escala de tres niveles de probabilidad e impacto.

| Valor | Probabilidad | Impacto |
|---|---|---|
| 1 | Baja | Bajo |
| 2 | Media | Medio |
| 3 | Alta | Alto |

La puntuación se obtiene mediante:

**Exposición del riesgo = Probabilidad × Impacto**

| Resultado | Nivel de riesgo |
|---|---|
| 1–2 | Bajo |
| 3–4 | Medio |
| 6–9 | Alto |

Esta escala permite establecer prioridades mediante un análisis semicuantitativo. Los valores asignados son estimaciones preliminares del equipo y no probabilidades estadísticas medidas.

## 5. Matriz de identificación y evaluación de riesgos

| ID | Riesgo identificado | Clasificación | Probabilidad | Impacto | Exposición | Nivel |
|---|---|---|---:|---:|---:|---|
| R-01 | Pérdida de registros de productores y cosechas | Técnico | 2 | 3 | 6 | Alto |
| R-02 | Inconsistencias entre inventario y ventas | Técnico | 3 | 3 | 9 | Alto |
| R-03 | Interrupciones de conectividad a Internet | Social y técnico | 3 | 2 | 6 | Alto |
| R-04 | Acceso no autorizado a datos de productores | Técnico y seguridad | 2 | 3 | 6 | Alto |
| R-05 | Dificultades de adaptación de los productores | Social | 2 | 2 | 4 | Medio |
| R-06 | Retrasos por disponibilidad limitada del equipo | Operativo | 2 | 2 | 4 | Medio |
| R-07 | Costos mayores a los estimados | Financiero | 2 | 3 | 6 | Alto |
| R-08 | Captura incorrecta de cantidades y precios | Técnico y operativo | 3 | 2 | 6 | Alto |
| R-09 | Cambios no controlados de requisitos | Gestión | 2 | 2 | 4 | Medio |
| R-10 | No obtener financiamiento mediante Stellar o Drips | Financiero y Web3 | 3 | 3 | 9 | Alto |
| R-11 | Integración blockchain compleja o innecesaria | Técnico y Web3 | 2 | 3 | 6 | Alto |
| R-12 | Exposición de información financiera en blockchain | Ético y Web3 | 2 | 3 | 6 | Alto |

## 6. Justificación de la evaluación

| Riesgo | Justificación |
|---|---|
| R-01 | La pérdida de información puede afectar el historial de cosechas y la identificación de los productores. |
| R-02 | Los registros de ventas modifican las existencias; una actualización incorrecta puede ocasionar inventarios negativos o cantidades inconsistentes. |
| R-03 | La conectividad limitada e intermitente de la región Mixteca puede dificultar la consulta de información y el funcionamiento de servicios en línea. |
| R-04 | El sistema administrará información de productores y operaciones comerciales que requiere controles de acceso y protección. |
| R-05 | Los productores podrían tener diferentes niveles de experiencia con herramientas digitales, dificultando la adopción inicial. |
| R-06 | La disponibilidad de los cuatro integrantes puede verse afectada por otras obligaciones académicas y las fechas de entrega. |
| R-07 | Los gastos de infraestructura y operación todavía no están completamente confirmados. |
| R-08 | Los errores al capturar cantidades y precios pueden afectar el inventario, los reportes y el seguimiento comercial. |
| R-09 | Las modificaciones posteriores a los criterios de aceptación pueden incrementar el tiempo de desarrollo. |
| R-10 | Stellar Community Fund y Drips no representan financiamiento aprobado; depender de recursos no confirmados podría comprometer el proyecto. |
| R-11 | La incorporación de tecnologías Web3 sin un beneficio funcional claro podría elevar los costos y la complejidad técnica. |
| R-12 | La publicación de información financiera identificable en redes blockchain públicas puede afectar la privacidad de los productores. |

Las calificaciones se establecen según las consecuencias posibles de cada situación y deberán actualizarse cuando existan resultados de pruebas, incidentes documentados o nueva información.

## 7. Estrategias de respuesta y responsables

| ID | Estrategia | Responsable propuesto | Medida preventiva | Plan de contingencia |
|---|---|---|---|---|
| R-01 | Mitigar | Daniel Alejandro | Validaciones y respaldos | Recuperar copia disponible y verificar la integridad de los datos |
| R-02 | Mitigar | Diego Fidel y Daniel Alejandro | Pruebas de movimientos y ventas | Detener operaciones afectadas, corregir existencias y repetir pruebas |
| R-03 | Mitigar | Luis Alexis | Pruebas con conexión limitada | Informar al usuario y recuperar operaciones pendientes si la arquitectura lo permite |
| R-04 | Mitigar | Diego Fidel | Controles de acceso y protección de información | Restringir accesos, investigar el incidente y documentar las acciones |
| R-05 | Mitigar | Félix Ángel | Capacitación y pruebas de usabilidad | Simplificar la interfaz y brindar acompañamiento |
| R-06 | Mitigar | Félix Ángel | Organización del calendario y seguimiento de tareas | Redistribuir actividades y reajustar fechas |
| R-07 | Mitigar | Félix Ángel | Revisión periódica del presupuesto | Priorizar funcionalidades esenciales y reevaluar los gastos |
| R-08 | Mitigar | Daniel Alejandro y Diego Fidel | Validación de campos y cantidades | Corregir registros inconsistentes y verificar los cálculos |
| R-09 | Evitar | Félix Ángel | Definir criterios de aceptación y controlar cambios | Registrar la solicitud y evaluar su impacto antes de incorporarla |
| R-10 | Evitar dependencia | Félix Ángel | Elaborar un escenario sin financiamiento externo | Ajustar el alcance a los recursos realmente disponibles |
| R-11 | Evitar | Luis Alexis y Félix Ángel | Evaluar si Web3 es técnicamente necesario | Mantener el sistema administrativo independiente de blockchain |
| R-12 | Mitigar | Diego Fidel | Evitar publicar datos personales o comerciales identificables | Detener nuevas publicaciones y aplicar medidas de respuesta ante la exposición |

La asignación de responsables se presenta como propuesta y deberá confirmarse por los integrantes del equipo eduScrum.

## 8. Riesgos prioritarios

### R-02. Inconsistencias entre inventario y ventas

Este riesgo alcanza una exposición de 9 puntos y se considera prioritario porque afecta directamente las funciones principales del sistema.

La auditoría del Sprint 1 identificó la necesidad de impedir ventas superiores al inventario disponible.

Por ello, deben realizarse pruebas de actualización de existencias, validaciones de cantidades y verificación de los movimientos registrados.

### R-10. Ausencia de financiamiento externo

El proyecto ha considerado Stellar Community Fund y Drips como posibles mecanismos de financiamiento. Sin embargo, no se dispone de evidencia de que se hayan obtenido estos recursos.

El equipo debe mantener una planeación que permita desarrollar el alcance académico mínimo sin depender de fondos externos.

### R-03. Conectividad limitada

Debido a las condiciones de conectividad de la región, se recomienda realizar pruebas con conexiones intermitentes y verificar qué funcionalidades requieren Internet.

El funcionamiento offline solamente podrá considerarse implementado cuando existan las pruebas correspondientes.

## 9. Trazabilidad con los sprints anteriores

| Riesgo | Sprint 1: Historias de usuario | Sprint 2: Calidad | Sprint 3: Planificación |
|---|---|---|---|
| R-01 | Registro de productores y cosechas | Prevención de defectos y validación de datos | Estimación de esfuerzo y pruebas |
| R-02 | HU-P1-003 Inventario y HU-P1-004 Ventas | Auditoría de requisitos y criterios de aceptación | Estimación del inventario: 38 horas |
| R-03 | Necesidades de operación en la Mixteca | OQ-03, conectividad limitada | Planificación de pruebas y recursos técnicos |
| R-04 | Información de productores | Revisiones de calidad y seguridad | Controles de acceso y responsables |
| R-05 | Necesidades de los productores | Validación de funcionalidades | Actividades de capacitación y seguimiento |
| R-06 | Backlog y responsabilidades | Plan de revisiones | Distribución propuesta de 144 horas |
| R-07 | Alcance funcional | Costo de la Calidad | Estimación académica de $21,600 MXN de esfuerzo humano |
| R-08 | HU-P1-004 Ventas | Auditoría de criterios de aceptación | Validaciones y pruebas de comercialización |
| R-09 | Historias de usuario | Auditoría de requisitos | Seguimiento de cambios mediante eduScrum |
| R-10 | Necesidades y viabilidad del proyecto | Informe Stellar/Drips | Evaluación financiera preliminar |
| R-11 | Funcionalidades del sistema | Análisis de estándares Web3 | Evaluación de integración técnica |
| R-12 | Datos comerciales | Consideraciones de privacidad | Medidas preventivas y contingencias |

Las cifras de 144 horas y $21,600 MXN son estimaciones propuestas en el Trabajo 2 y deberán ser confirmadas por el equipo.

## 10. Seguimiento mediante GitHub Projects

Para dar seguimiento a los riesgos se utilizará el tablero:

**Sprint 3 - Planificación - UMIZOOMI**

Repositorio de referencia:

https://github.com/SistemasTecTlaxiaco/gestion-de-proyectos-de-software-tablero-group-9

Los riesgos prioritarios podrán registrarse como Issues relacionadas con las historias del sistema.

Cada registro deberá contar con responsable, nivel de riesgo, estrategia, evidencia y estado.

Los cambios se revisarán durante las reuniones de planificación, seguimiento y revisión del Sprint 3.

## 11. Relación con el análisis de viabilidad

La matriz de riesgos complementa el documento Objetivo SMART y Análisis de Viabilidad Multidimensional.

**Viabilidad técnica:** deberá comprobarse con pruebas funcionales, validación de registros y revisión de la infraestructura.

**Viabilidad operativa:** dependerá de la disponibilidad del equipo, la organización de tareas y la participación de los productores.

**Viabilidad financiera:** requerirá confirmar los costos no laborales y los recursos realmente disponibles.

**Dictamen preliminar: SUJETO A VALIDACIÓN.**

No se considera conveniente emitir un GO definitivo hasta contar con las evidencias necesarias.

## 12. Conclusión

La matriz de riesgos del Sistema de Control y Comercialización de la Producción de Miel permite identificar y evaluar doce situaciones que podrían afectar su desarrollo.

Entre los riesgos de mayor importancia destacan las inconsistencias de inventario, las dificultades de conectividad, la protección de información y la disponibilidad de recursos económicos.

La utilización de una escala de probabilidad e impacto permite establecer prioridades, mientras que las estrategias de respuesta y la asignación de responsables facilitan la organización del trabajo.

La relación entre las historias de usuario del Sprint 1, el Plan de Calidad del Sprint 2 y las estimaciones del Sprint 3 fortalece la coherencia de la planificación y permite dar seguimiento a los riesgos mediante eduScrum.

---

## 13. Referencias

- Equipo UMIZOOMI. (2026). *Plan de Calidad Open Hub Tec, versión 1.0*. Documento de trabajo de la asignatura.
- Equipo UMIZOOMI. (2026). *Documento detallado: Objetivo SMART y Análisis de Viabilidad Multidimensional*. Documento del Sprint 3.
- Equipo UMIZOOMI. (2026). *Informe de estándares Stellar/Drips*. Documento del Sprint 2.
- Equipo UMIZOOMI. (2026). *Auditoría con IA de historias de usuario*. Repositorio GitHub de Open Hub Tec.
