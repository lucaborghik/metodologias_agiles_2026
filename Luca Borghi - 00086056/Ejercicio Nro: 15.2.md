# Ejercicio Nro: 15.2

## Enunciado

### Ejercicio 1: Identificación de Roles

**Objetivo:** Reconocer los roles de Scrum y sus responsabilidades.

**Consigna:** Para cada una de las siguientes situaciones, identificar qué rol de Scrum debería actuar y justificar la respuesta.

### Ejercicio 2: Artefactos de Scrum

**Objetivo:** Comprender el propósito y contenido de cada artefacto.

**Consigna:** Completar la tabla indicando qué información contiene y qué información no debería contener cada artefacto.

### Ejercicio 3: Eventos de Scrum

**Objetivo:** Identificar las características correctas de los eventos Scrum mediante preguntas de Verdadero o Falso.

### Ejercicio 4: Creación de Product Backlog

**Objetivo:** Practicar la redacción y priorización de User Stories para una aplicación móvil de delivery.

### Ejercicio 5: Planning Poker Simulation

**Objetivo:** Practicar la estimación colaborativa utilizando Story Points.

### Ejercicio 6: Sprint Planning Práctico

**Objetivo:** Planificar un Sprint completo seleccionando historias de usuario, definiendo tareas, Sprint Goal e identificando riesgos.

### Ejercicio 7: Simulación de Daily Scrum

**Objetivo:** Practicar la dinámica de la reunión diaria.

### Ejercicio 8: Sprint Review y Sprint Retrospective

**Objetivo:** Practicar la inspección y adaptación del trabajo realizado.

### Ejercicio 9: Manejo de Impedimentos

**Objetivo:** Identificar y proponer soluciones para impedimentos frecuentes en Scrum.

### Ejercicio 10: Definition of Done

**Objetivo:** Crear una Definition of Done para un equipo que desarrolla una aplicación web de e-commerce.

---

## Resolución

### Ejercicio 1 – Identificación de Roles

**a) Un stakeholder quiere agregar una nueva funcionalidad urgente durante el Sprint.**

**Rol:** Product Owner.

**Justificación:**

El Product Owner es el responsable de administrar y priorizar el Product Backlog. Debe analizar la solicitud del stakeholder y decidir si la nueva funcionalidad aporta suficiente valor como para incorporarla en un Sprint futuro o evaluar, junto con el equipo, si es necesario modificar la planificación.

**b) El equipo no entiende claramente un requisito del Product Backlog.**

**Rol:** Product Owner.

**Justificación:**

El Product Owner debe aclarar los requisitos y responder las dudas del equipo para que todos comprendan correctamente las historias de usuario antes de comenzar el desarrollo.

**c) Hay conflictos entre desarrolladores sobre la implementación técnica.**

**Rol:** Development Team.

**Justificación:**

El Equipo de Desarrollo es autoorganizado y decide cómo implementar técnicamente las funcionalidades. Si el conflicto afecta el trabajo del equipo, el Scrum Master puede facilitar el diálogo, pero la decisión técnica corresponde a los desarrolladores.

**d) Se necesita decidir el orden de prioridad de las User Stories.**

**Rol:** Product Owner.

**Justificación:**

El Product Owner es quien establece las prioridades del Product Backlog según el valor que cada historia aporta al negocio y a los usuarios.

**e) El equipo está teniendo problemas para cumplir con la Definition of Done.**

**Rol:** Scrum Master.

**Justificación:**

El Scrum Master ayuda al equipo a aplicar correctamente Scrum, identifica impedimentos y promueve la mejora continua para que puedan cumplir con la Definition of Done en cada Sprint.

**Conclusión**

Cada rol en Scrum tiene responsabilidades específicas. El Product Owner se enfoca en maximizar el valor del producto y gestionar las prioridades, el Scrum Master facilita el proceso y elimina impedimentos, mientras que el Development Team desarrolla las funcionalidades y toma las decisiones técnicas necesarias para cumplir los objetivos del Sprint.

---

### Ejercicio 2 – Artefactos de Scrum

| Artefacto | ¿Qué SÍ contiene? | ¿Qué NO debería contener? |
|-----------|-------------------|---------------------------|
| **Product Backlog** | Lista priorizada de funcionalidades, historias de usuario, mejoras y requisitos del producto. | Tareas técnicas detalladas de un Sprint específico o actividades ya finalizadas. |
| **Sprint Backlog** | Historias de usuario seleccionadas para el Sprint y las tareas necesarias para completarlas. | Historias que no fueron seleccionadas para el Sprint o tareas de futuros Sprints. |
| **Increment** | Funcionalidades terminadas, probadas y que cumplen con la Definition of Done. | Funcionalidades incompletas, código sin probar o trabajo pendiente. |

---

### Ejercicio 3 – Eventos de Scrum (Verdadero o Falso)

**a) La Sprint Planning puede durar hasta 8 horas para un Sprint de 4 semanas.**

**Verdadero (V).**

Es la duración máxima recomendada para un Sprint de cuatro semanas.

**b) En la Daily Scrum cada miembro debe reportar al Scrum Master.**

**Falso (F).**

**Justificación:** La Daily Scrum no es una reunión para reportarle al Scrum Master. Es una reunión del Equipo de Desarrollo para coordinar el trabajo y planificar las próximas 24 horas.

**c) La Sprint Review es solo para demostrar el producto al Product Owner.**

**Falso (F).**

**Justificación:** En la Sprint Review participan el Product Owner, el Equipo Scrum y los stakeholders. El objetivo es revisar el incremento y obtener retroalimentación.

**d) En la Sprint Retrospective se puede modificar el Sprint Backlog.**

**Falso (F).**

**Justificación:** La Retrospective sirve para analizar cómo trabajó el equipo y definir mejoras para el próximo Sprint. El Sprint Backlog pertenece al Sprint en curso y no se modifica en esta reunión.

**e) El Sprint puede cancelarse solo por decisión del Development Team.**

**Falso (F).**

**Justificación:** El único que puede cancelar un Sprint es el Product Owner cuando el objetivo del Sprint deja de tener sentido.

---

### Ejercicio 4 – Creación de Product Backlog

| Prioridad | Historia de Usuario | Story Points |
|-----------|---------------------|--------------|
| 1 | Como usuario, quiero registrarme en la aplicación para poder realizar pedidos. | 5 |
| 2 | Como usuario, quiero iniciar sesión para acceder a mi cuenta de forma segura. | 3 |
| 3 | Como usuario, quiero buscar restaurantes para encontrar opciones cercanas. | 8 |
| 4 | Como usuario, quiero agregar productos al carrito para realizar un pedido. | 8 |
| 5 | Como usuario, quiero pagar con tarjeta de crédito para completar mi compra. | 13 |
| 6 | Como usuario, quiero ver el estado de mi pedido para saber cuándo llegará. | 5 |
| 7 | Como repartidor, quiero recibir notificaciones de nuevos pedidos para aceptarlos rápidamente. | 8 |
| 8 | Como administrador, quiero generar reportes de ventas para analizar el desempeño del negocio. | 13 |

**Criterios de aceptación**

**Historia 1 – Registro de usuario**

- El usuario debe ingresar nombre, correo electrónico y contraseña.
- El correo no puede estar registrado previamente.
- El sistema debe confirmar el registro exitoso.

**Historia 2 – Inicio de sesión**

- El usuario debe ingresar correo y contraseña.
- El sistema debe validar las credenciales.
- Si son correctas, debe permitir el acceso; si no, mostrar un mensaje de error.

**Historia 3 – Búsqueda de restaurantes**

- El usuario puede buscar por nombre o ubicación.
- El sistema muestra una lista de restaurantes disponibles.
- Se deben visualizar datos básicos como nombre, calificación y tiempo estimado de entrega.

---

### Ejercicio 5 – Planning Poker Simulation

| User Story | Estimación (Story Points) | Justificación |
|------------|---------------------------|---------------|
| Como usuario, quiero registrarme con email y contraseña. | 5 | Funcionalidad básica que requiere validaciones y almacenamiento de datos. |
| Como usuario, quiero recuperar mi contraseña olvidada. | 8 | Requiere validación de identidad, envío de correo y cambio de contraseña. |
| Como administrador, quiero generar reportes de ventas mensuales. | 13 | Implica consultar información, procesarla y generar reportes con distintos filtros. |
| Como usuario, quiero pagar con tarjeta de crédito de forma segura. | 21 | Es la funcionalidad más compleja porque integra una pasarela de pagos y requiere medidas de seguridad. |

**Proceso seguido**

- Cada integrante realizó una estimación de forma individual.
- Se mostraron todas las estimaciones al mismo tiempo.
- Se discutieron las diferencias de criterio.
- Se llegó a un consenso para asignar la estimación definitiva.

---

### Ejercicio 6 – Sprint Planning Práctico

**Selección del Sprint Backlog**

El equipo tiene una velocidad promedio de 40 Story Points.

Se seleccionan las siguientes historias:

| Historia | Story Points |
|----------|--------------|
| Historia A | 8 |
| Historia B | 13 |
| Historia C | 5 |
| Historia D | 8 |
| Historia E | 3 |

**Total:** 37 Story Points.

La Historia F (21 puntos) queda para un Sprint futuro porque superaría la capacidad del equipo.

**Descomposición de la Historia B (13 puntos)**

Historia: Desarrollo del módulo principal.

**Tareas**

- Analizar requisitos.
- Diseñar la interfaz.
- Desarrollar la funcionalidad.
- Realizar pruebas unitarias.
- Integrar con el resto del sistema.
- Corregir errores detectados.
- Documentar la funcionalidad.

**Sprint Goal**

Desarrollar las funcionalidades prioritarias del sistema para entregar un incremento funcional y probado al finalizar las dos semanas del Sprint.

**Posibles impedimentos**

- Cambios inesperados en los requisitos.
- Ausencia de algún integrante del equipo.
- Problemas técnicos con herramientas o servidores.
- Errores durante la integración del código.

---

### Ejercicio 7 – Simulación de Daily Scrum

**Día 5 del Sprint**

**Desarrollador 1**

**¿Qué hice ayer?**

Terminé la funcionalidad de inicio de sesión.

**¿Qué haré hoy?**

Comenzaré el desarrollo del registro de usuarios.

**¿Tengo impedimentos?**

No.

**Desarrollador 2**

**¿Qué hice ayer?**

Trabajé en la conexión con la base de datos.

**¿Qué haré hoy?**

Resolveré algunos errores detectados en las consultas.

**¿Tengo impedimentos?**

Sí. Necesito ayuda para optimizar una consulta SQL.

**Desarrollador 3**

**¿Qué hice ayer?**

Finalicé las pruebas unitarias.

**¿Qué haré hoy?**

Comenzaré las pruebas de integración.

**¿Tengo impedimentos?**

No.

**Desarrollador 4**

**¿Qué hice ayer?**

Avancé con la integración del sistema de pagos.

**¿Qué haré hoy?**

Continuaré esperando la disponibilidad de la API externa.

**¿Tengo impedimentos?**

Sí. La API del proveedor aún no está disponible.

**Scrum Master**

Durante la reunión registra los impedimentos detectados y coordina las acciones necesarias para resolverlos, permitiendo que el equipo continúe avanzando con el Sprint.

---

### Ejercicio 8 – Sprint Review y Sprint Retrospective

**Parte A – Sprint Review**

**Agenda de la reunión (Duración: 2 horas)**

- Bienvenida y presentación del Sprint.
- Demostración de las funcionalidades desarrolladas.
- Comparación entre el Sprint Goal y los resultados obtenidos.
- Presentación de métricas del Sprint.
- Recepción de comentarios y sugerencias de los stakeholders.
- Definición de los próximos pasos.

**Métricas a presentar**

- Story Points comprometidos: 40.
- Story Points completados: 35.
- Funcionalidades terminadas: 5.
- Funcionalidades pendientes: 1.
- Cantidad de errores detectados y corregidos.
- Velocidad del equipo durante el Sprint.

**Preguntas para los stakeholders**

- ¿Las funcionalidades desarrolladas cumplen con sus expectativas?
- ¿Consideran necesario realizar algún cambio o mejora?
- ¿Existe alguna nueva necesidad que deba incorporarse al Product Backlog?
- ¿Qué funcionalidades consideran prioritarias para el próximo Sprint?

**Plan para las historias no completadas**

Las historias pendientes regresarán al Product Backlog, donde el Product Owner evaluará su prioridad para incluirlas en un Sprint futuro.

**Parte B – Sprint Retrospective**

**Start (Empezar)**

- Mejorar la comunicación entre los integrantes del equipo.
- Refinar las historias de usuario antes del Sprint Planning.
- Realizar revisiones de código más frecuentes.

**Stop (Dejar de hacer)**

- Aceptar cambios de último momento sin analizarlos.
- Subestimar el tiempo de las tareas complejas.
- Esperar hasta el final del Sprint para integrar el código.

**Continue (Continuar)**

- Mantener las reuniones diarias.
- Colaborar entre los desarrolladores.
- Realizar pruebas durante todo el Sprint.

**Análisis de las situaciones**

- Algunas tareas tomaron más tiempo del estimado: mejorar las estimaciones utilizando la experiencia de Sprints anteriores.
- Un integrante estuvo enfermo: redistribuir temporalmente las tareas para no afectar el Sprint.
- Hubo cambios en los requisitos: incorporarlos al Product Backlog y analizarlos para un Sprint futuro.
- Mejoró la colaboración entre Front-end y Back-end: mantener esta práctica para futuros desarrollos.

---

### Ejercicio 9 – Manejo de Impedimentos

**Situación 1**

**Problema:** El Product Owner no está disponible para aclarar dudas.

**Tipo de impedimento:** Comunicación.

**Estrategias**

- Programar reuniones de refinamiento del Backlog.
- Documentar las dudas pendientes.
- Definir un reemplazo temporal si fuera necesario.

**Responsable:** Scrum Master.

**Seguimiento:** Verificar que las dudas sean resueltas antes del próximo Sprint Planning.

**Situación 2**

**Problema:** Un desarrollador senior está sobrecargado.

**Tipo de impedimento:** Distribución del trabajo.

**Estrategias**

- Redistribuir tareas.
- Fomentar la programación en pareja.
- Compartir conocimientos con el resto del equipo.

**Responsable:** Scrum Master junto al Equipo de Desarrollo.

**Seguimiento:** Revisar periódicamente la carga de trabajo.

**Situación 3**

**Problema:** Las herramientas de desarrollo fallan constantemente.

**Tipo de impedimento:** Técnico.

**Estrategias**

- Actualizar las herramientas.
- Revisar la infraestructura.
- Mantener herramientas de respaldo.

**Responsable:** Equipo técnico y Scrum Master.

**Seguimiento:** Controlar la estabilidad de las herramientas.

**Situación 4**

**Problema:** Conflictos entre integrantes del equipo.

**Tipo de impedimento:** Interpersonal.

**Estrategias**

- Realizar reuniones para resolver diferencias.
- Promover una comunicación abierta.
- Recordar los valores de Scrum.

**Responsable:** Scrum Master.

**Seguimiento:** Evaluar el clima de trabajo en cada Retrospective.

**Situación 5**

**Problema:** Un stakeholder quiere agregar funcionalidades durante el Sprint.

**Tipo de impedimento:** Cambios de alcance.

**Estrategias**

- Explicar el funcionamiento de Scrum.
- Registrar la solicitud en el Product Backlog.
- Evaluar su prioridad para el próximo Sprint.

**Responsable:** Product Owner.

**Seguimiento:** Revisar la prioridad de la nueva historia en el siguiente Sprint Planning.

---

### Ejercicio 10 – Definition of Done

**Criterios técnicos**

- Código compilado sin errores.
- Código revisado por otro integrante del equipo.
- Integración realizada correctamente.

**Criterios de calidad**

- Todas las pruebas unitarias aprobadas.
- Sin errores críticos.
- Cumplimiento de los estándares de codificación.

**Criterios de documentación**

- Código comentado cuando sea necesario.
- Documentación técnica actualizada.
- Manual de usuario actualizado si corresponde.

**Criterios de validación**

- Funcionalidad aprobada por el Product Owner.
- Desplegada correctamente en el ambiente de testing.
- Cumplimiento de los criterios de aceptación de la historia de usuario.
- Cumplimiento de criterios de rendimiento (performance).
- Validación de accesibilidad.
- Verificación de medidas básicas de seguridad.
- Preparación para su despliegue en producción.

---

## Preguntas de Cierre

**1. ¿Cuáles fueron los principales desafíos al aplicar Scrum en estos ejercicios?**

El mayor desafío fue organizar correctamente las tareas, priorizar las historias de usuario y realizar estimaciones realistas del esfuerzo requerido para cada funcionalidad.

**2. ¿Qué beneficios observaste en el trabajo colaborativo?**

El trabajo colaborativo permitió compartir conocimientos, resolver problemas de forma más rápida y obtener mejores resultados gracias a la participación de todos los integrantes del equipo.

**3. ¿Cómo adaptarías Scrum para un proyecto real en tu área de trabajo?**

Aplicaría Sprints de dos semanas, reuniones diarias, revisiones periódicas con el cliente y retrospectivas para mejorar continuamente el proceso de desarrollo.

**4. ¿Qué aspectos de Scrum consideras más difíciles de implementar?**

Los aspectos más desafiantes son realizar estimaciones precisas, adaptarse a cambios frecuentes sin afectar los objetivos del Sprint y mantener una comunicación constante entre todos los integrantes del equipo.
