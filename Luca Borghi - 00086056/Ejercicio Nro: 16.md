# Ejercicio Nro: 16

## Enunciado

Utilizar el método Delphi para llegar a un consenso sobre la tecnología y la arquitectura más adecuadas para el desarrollo de una billetera virtual segura, escalable y confiable.

## Resolución

### 1. Definición del problema

El objetivo es seleccionar la tecnología y la arquitectura más adecuadas para desarrollar una billetera virtual que sea segura, escalable y confiable.

Para tomar esta decisión se tendrán en cuenta los siguientes factores:

- Seguridad de la información.
- Escalabilidad del sistema.
- Confiabilidad y disponibilidad.
- Facilidad de uso.
- Costos de desarrollo y mantenimiento.
- Compatibilidad con dispositivos móviles y web.

---

### 2. Selección del panel de expertos

Se conformará un panel integrado por especialistas de distintas áreas para obtener diferentes puntos de vista.

| Experto | Especialidad |
|----------|--------------|
| Experto 1 | Ciberseguridad |
| Experto 2 | Desarrollo Backend |
| Experto 3 | Arquitectura de Software |
| Experto 4 | Bases de Datos |
| Experto 5 | Infraestructura Cloud |
| Experto 6 | Experiencia de Usuario (UX/UI) |

Todos los participantes responderán de forma anónima para evitar influencias entre ellos y favorecer respuestas objetivas.

---

### 3. Elaboración del cuestionario

El cuestionario incluirá preguntas que permitan evaluar distintas alternativas tecnológicas.

**Preguntas**

**¿Qué arquitectura considera más adecuada para una billetera virtual?**

- Monolítica
- Microservicios
- Serverless

**¿Qué base de datos utilizaría?**

- PostgreSQL
- MySQL
- MongoDB

**¿Qué lenguaje considera más conveniente para el Backend?**

- Java
- C#
- Python
- Node.js

**¿Qué aspecto considera más importante?**

- Seguridad
- Escalabilidad
- Rendimiento
- Facilidad de mantenimiento

**¿Qué mecanismo de autenticación recomienda?**

- Usuario y contraseña
- OAuth 2.0
- Autenticación multifactor (MFA)

---

### 4. Aplicación del Método Delphi

#### Primera ronda

Cada experto responde el cuestionario de forma independiente.

Los resultados obtenidos muestran que la mayoría recomienda:

- Arquitectura de Microservicios.
- PostgreSQL como base de datos.
- Java o C# para el Backend.
- Autenticación multifactor (MFA).
- Infraestructura en la nube.

#### Segunda ronda

Se presentan los resultados de forma anónima para que los expertos puedan revisar sus respuestas considerando la opinión general del grupo.

Luego de esta instancia se alcanza un mayor consenso respecto de la arquitectura y las tecnologías recomendadas.

---

### 5. Selección de la tecnología y la arquitectura

Luego del análisis de las respuestas se decide implementar:

| Componente | Tecnología |
|------------|------------|
| Arquitectura | Microservicios |
| Backend | Java con Spring Boot |
| Base de Datos | PostgreSQL |
| Frontend | React |
| Infraestructura | AWS |
| Seguridad | OAuth 2.0, Autenticación Multifactor (MFA), Cifrado HTTPS/TLS, Encriptación de datos sensibles |

#### Justificación

La arquitectura de microservicios facilita el crecimiento del sistema y permite desarrollar, desplegar y mantener cada componente de forma independiente.

PostgreSQL ofrece un excelente rendimiento y confiabilidad para operaciones financieras.

Spring Boot proporciona una estructura robusta para aplicaciones empresariales, mientras que React permite desarrollar una interfaz moderna y fácil de usar.

El uso de AWS aporta alta disponibilidad y escalabilidad, y la incorporación de OAuth 2.0 junto con la autenticación multifactor mejora significativamente la seguridad de la billetera virtual.

---

### 6. Documentación y comunicación

Una vez tomada la decisión, se documentará todo el proceso realizado mediante el Método Delphi.

La documentación incluirá:

- Objetivo del estudio.
- Integrantes del panel de expertos.
- Cuestionario utilizado.
- Resultados de cada ronda.
- Tecnologías evaluadas.
- Justificación de la decisión final.

Finalmente, los resultados serán comunicados al equipo de desarrollo, al Product Owner y a los demás interesados para comenzar la planificación del proyecto.

---

## Conclusión

La aplicación del Método Delphi permitió analizar distintas alternativas de manera estructurada y alcanzar un consenso entre especialistas. Gracias a este proceso fue posible seleccionar una arquitectura basada en microservicios y tecnologías que priorizan la seguridad, la escalabilidad y la confiabilidad, características fundamentales para el desarrollo de una billetera virtual.
