# Ejercicio Nro: 18

## Enunciado

Una empresa de desarrollo de software ha decidido adoptar la metodología Scrum para mejorar la eficiencia y calidad de sus proyectos. Tu equipo ha sido seleccionado para liderar la implementación de Scrum en un nuevo proyecto de desarrollo de una aplicación web para una empresa de logística.

**Consigna:**

Construir una serie de prompts que simulen las diferentes etapas y actividades de Scrum.

Cada prompt debe utilizar como entrada la salida del prompt anterior, formando una secuencia lógica de ejecución.

Los prompts a desarrollar son:

- Prompt 1: Definición del Product Backlog.
- Prompt 2: Planificación del Sprint.
- Prompt 3: Ejecución del Sprint.
- Prompt 4: Revisión del Sprint.
- Prompt 5: Retrospectiva del Sprint.

Cada prompt debe describir claramente la actividad Scrum, indicar la entrada y salida esperadas y solicitar la generación de la información correspondiente.

---

# Resolución

## 🤖 Agente 1: Definición del Product Backlog

### 1. Prompt Desarrollado

**Contexto:**

Actúas como un Product Owner experimentado trabajando en una empresa de desarrollo de software. Tu objetivo es transformar las necesidades del negocio en historias de usuario claras y priorizadas.

**Instrucción:**

Analiza los requerimientos proporcionados por el cliente para la aplicación web de gestión de envíos logísticos y redacta el Product Backlog inicial.

**Input:**

Requerimientos iniciales del cliente:

- Registro y autenticación de usuarios.
- Creación y seguimiento de envíos.
- Generación de reportes de estado de envíos.
- Integración con sistemas de terceros para rastreo de envíos.

### 2. Resultados de la Aplicación

**Output:**

Product Backlog inicial con las siguientes historias de usuario prioritarias:

- Como usuario, puedo registrarme e iniciar sesión en la aplicación.
- Como usuario, puedo crear un nuevo envío y seguir su estado.
- Como usuario, puedo generar reportes de estado de mis envíos.

### 3. Técnicas Utilizadas

- Role-playing (Asignación de Rol): Se le asigna a la IA la personalidad de un Product Owner experimentado para condicionar el tono y el enfoque hacia el negocio.
- Formateo Específico (Historias de Usuario): Se induce a la IA a redactar los requerimientos utilizando la estructura ágil estándar ("Como [rol], quiero/puedo [acción]...").
- Clasificación y Priorización: Se le pide transformar requerimientos en elementos de valor priorizados.

### 4. Razonamiento Scrum

En Scrum, el Product Owner es el responsable exclusivo de analizar, definir y priorizar qué es lo más importante para desarrollar primero. Se utiliza el formato de Historias de Usuario porque las metodologías ágiles se enfocan en las necesidades del cliente y el valor que aportan.

---

## 🤖 Agente 2: Planificación del Sprint

### 1. Prompt Desarrollado

**Contexto:**

Actúas como Scrum Master y facilitador técnico. Tu rol es ayudar al equipo de desarrolladores a tomar los ítems del Product Backlog y desglosarlos en tareas asignables para el Sprint.

**Instrucción:**

Toma las historias de usuario prioritarias del Product Backlog y crea un Plan del Sprint definiendo tareas técnicas específicas y asignando responsables.

**Input:**

Product Backlog (Salida del Agente 1).

### 2. Resultados de la Aplicación

**Output:**

Plan del Sprint con las siguientes tareas y responsables:

- Tarea 1: Desarrollar la funcionalidad de registro e inicio de sesión. (Desarrollador A).
- Tarea 2: Implementar la funcionalidad de creación y seguimiento de envíos. (Desarrollador B).
- Tarea 3: Diseñar e implementar la generación de reportes de estado de envíos. (Desarrollador C).
- Tarea 4: Integrar la aplicación con los sistemas de terceros para rastreo de envíos. (Desarrollador D).

### 3. Técnicas Utilizadas

- Encadenamiento de Prompts (Prompt Chaining): Utiliza la salida del Agente 1 como entrada.
- Role-playing: Adopta el rol de Scrum Master y facilitador técnico.
- Desglose de Tareas (Task Breakdown): Convierte historias de usuario en tareas técnicas.

### 4. Razonamiento Scrum

Durante la Sprint Planning el equipo selecciona las historias que puede completar durante el Sprint y las transforma en tareas concretas. El Equipo de Desarrollo decide la mejor forma técnica de implementarlas.

---

## 🤖 Agente 3: Ejecución del Sprint

### 1. Prompt Desarrollado

**Contexto:**

Actúas como el Development Team. Tu objetivo es desarrollar, probar e integrar las funcionalidades planificadas para generar un incremento de software funcional.

**Instrucción:**

Simula la ejecución técnica del Sprint e informa qué funcionalidades fueron completadas.

**Input:**

Plan del Sprint (Salida del Agente 2).

### 2. Resultados de la Aplicación

**Output:**

Incremento de software funcional con las siguientes funcionalidades implementadas:

- Registro e inicio de sesión de usuarios.
- Creación y seguimiento de envíos.
- Generación de reportes de estado de envíos.
- Integración con sistemas de terceros para rastreo de envíos.

### 3. Técnicas Utilizadas

- Encadenamiento de Prompts.
- Simulación de Escenarios.
- Role-playing como Development Team.

### 4. Razonamiento Scrum

Al finalizar cada Sprint debe existir un incremento funcional del producto que pueda ser mostrado al cliente. El incremento representa el valor generado durante la iteración.

---

## 🤖 Agente 4: Revisión del Sprint

### 1. Prompt Desarrollado

**Contexto:**

Actúas simulando la dinámica entre el Cliente y el Equipo Scrum durante la Sprint Review.

**Instrucción:**

Evalúa el incremento desarrollado, genera retroalimentación del cliente e identifica las lecciones aprendidas por el equipo.

**Input:**

Incremento de software funcional (Salida del Agente 3).

### 2. Resultados de la Aplicación

**Output:**

**Retroalimentación del cliente**

El cliente está satisfecho con las funcionalidades implementadas y sugiere incorporar una opción para enviar notificaciones sobre el estado de los envíos.

**Lecciones aprendidas**

- Mejorar la comunicación con el cliente para comprender mejor los requerimientos.
- Implementar pruebas más exhaustivas antes de cada entrega.

### 3. Técnicas Utilizadas

- Role-playing múltiple.
- Generación de Feedback Sintético.
- Encadenamiento de Prompts.

### 4. Razonamiento Scrum

La Sprint Review permite mostrar el incremento al cliente y obtener retroalimentación para adaptar el Product Backlog. Esto refleja uno de los principios fundamentales de Scrum: la colaboración continua con el cliente.

---

## 🤖 Agente 5: Retrospectiva del Sprint

### 1. Prompt Desarrollado

**Contexto:**

Actúas como Scrum Master guiando al equipo en un proceso de mejora continua.

**Instrucción:**

Analiza la retroalimentación obtenida durante la Sprint Review y redacta un plan de mejora para el siguiente Sprint.

**Input:**

Retroalimentación del cliente y lecciones aprendidas (Salida del Agente 4).

### 2. Resultados de la Aplicación

**Output:**

Plan de mejora para el siguiente Sprint:

- Mejorar la coordinación entre los miembros del equipo.
- Implementar un proceso más eficiente para la estimación y asignación de tareas.
- Incorporar la funcionalidad de notificaciones sobre el estado de los envíos en el próximo Sprint.

### 3. Técnicas Utilizadas

- Cierre de Ciclo (Loop Methodology).
- Role-playing como Scrum Master.
- Encadenamiento de Prompts.

### 4. Razonamiento Scrum

La Sprint Retrospective permite que el equipo reflexione sobre su forma de trabajar y defina acciones concretas para mejorar en el siguiente Sprint. De esta manera se aplica el principio de inspección y adaptación continua que caracteriza a Scrum.
