# Ejercicio Nro: 8

## Enunciado

Ejercicios sobre Metodologías de
Desarrollo en Cascada
1. Análisis de Requerimientos:
● Ejercicio 1: Un cliente te solicita una aplicación web para gestionar su
inventario. Define los requisitos funcionales y no funcionales del sistema.
● Ejercicio 2: Redacta un caso de uso para la funcionalidad de "Agregar un nuevo
producto" en la aplicación web del ejercicio 1.
2. Diseño del Sistema:
● Ejercicio 3: Elabora un diagrama de flujo de datos para la aplicación web del
ejercicio 1.
● Ejercicio 4: Diseña la interfaz de usuario para la pantalla de "Inicio" de la
aplicación web del ejercicio 1.
3. Diseño del Programa:
● Ejercicio 5: Elige una arquitectura adecuada para la aplicación web del ejercicio
1 y justifica tu elección.
● Ejercicio 6: Diseña la base de datos para la aplicación web del ejercicio 1.
4. Diseño:
Utilizando los siguientes diagrama resuelva los casos de usos de los
ejercicios 7 y 8:
1. Diagrama de Dominio: Identifica las entidades, atributos y relaciones del sistema.
2. Diagrama de Robustez: Analiza cómo el sistema responde a diferentes escenarios
de uso.
3. Prototipo: Crea una versión simplificada del sistema para probar la usabilidad y
funcionalidad.
4. Diagrama de Secuencia: Describe la interacción entre los diferentes objetos del
sistema.
5. Diagrama de Clases: Define las clases, sus atributos, métodos y relaciones
● Ejercicio 7: Implementa la funcionalidad de "Agregar un nuevo producto" en la
aplicación web del ejercicio 1 utilizando el lenguaje de programación de tu
preferencia.
● Ejercicio 8: Implementa la lógica de negocio para la funcionalidad de "Agregar
un nuevo producto" en la aplicación web del ejercicio 1.
5. Pruebas:
● Ejercicio 9: Define un conjunto de pruebas unitarias para la funcionalidad de
"Agregar un nuevo producto" en la aplicación web del ejercicio 1.
● Ejercicio 10: Ejecuta pruebas de integración para la funcionalidad de "Agregar
un nuevo producto" en la aplicación web del ejercicio 1.
6. Despliegue del Programa:
● Ejercicio 11: Definir un plan de despliegue para la aplicación web del ejercicio 1.
● Ejercicio 12: Despliega la aplicación web del ejercicio 1 en un servidor de
producción.
7. Mantenimiento:
● Ejercicio 13: Definir un plan de mantenimiento para la aplicación web del
ejercicio 1.
● Ejercicio 14: Implementa una corrección de errores para un problema detectado
en la aplicación web del ejercicio 1.
8. Nos preparamos para nuevos retos
- Ejercicio 15: Arme un equipo de trabajo y defina los roles para realizar los
ejercicios anteriores para un futuro dominio de aplicación relacionado con
inteligencia artificial generatica

## Resolución

Práctica 1 - Metodologías de Desarrollo
en Cascada
Ejercicio 1 - Requisitos del Sistema
Requisitos Funcionales (RF)
RF1. El sistema debe permitir iniciar sesión mediante usuario y contraseña.
RF2. El sistema debe permitir agregar nuevos productos.
RF3. El sistema debe permitir modificar la información de un producto existente.
RF4. El sistema debe permitir eliminar productos del inventario.
RF5. El sistema debe mostrar un listado con todos los productos registrados.
RF6. El sistema debe permitir buscar productos por nombre o categoría.
RF7. El sistema debe controlar automáticamente el stock disponible de cada producto.
RF8. El sistema debe guardar toda la información en una base de datos.
Requisitos No Funcionales (RNF)
RNF1. La aplicación deberá ser accesible desde cualquier navegador web moderno.
RNF2. El tiempo de respuesta para consultar productos no deberá superar los 2 segundos.
RNF3. Los datos almacenados deberán mantenerse seguros mediante autenticación de
usuarios.
RNF4. La interfaz deberá ser simple e intuitiva para facilitar su uso.
RNF5. La información del inventario deberá almacenarse de forma permanente en una base
de datos.
RNF6. El sistema deberá permitir futuras ampliaciones sin necesidad de modificar toda la
aplicación.
Breve descripción del sistema
Se desarrollará una aplicación web para gestionar el inventario de una empresa. El sistema
permitirá registrar, consultar, modificar y eliminar productos, además de controlar el stock
disponible y facilitar la búsqueda de información. El acceso estará protegido mediante un
inicio de sesión para garantizar la seguridad de los datos.
Ejercicio 2 – Caso de Uso: Agregar un
Nuevo Producto
Caso de Uso: Agregar un nuevo producto
Nombre
Agregar un nuevo producto.
Actor principal
Administrador del sistema.
Objetivo
Registrar un nuevo producto en el inventario para que pueda ser administrado y consultado
posteriormente.
Precondiciones
● El usuario debe haber iniciado sesión.
● Debe contar con permisos para administrar el inventario.
Flujo principal
1. El administrador accede al módulo Inventario.
2. Selecciona la opción Agregar producto.
3. El sistema muestra un formulario para ingresar los datos del producto.
4. El administrador completa los siguientes campos:
○ Nombre
○ Descripción
○ Precio
○ Stock
○ Categoría
5. Presiona el botón Guardar.
6. El sistema valida que los datos ingresados sean correctos.
7. Si la información es válida, el sistema registra el producto en la base de datos.
8. El sistema muestra el mensaje "Producto agregado correctamente".
Flujos alternativos
A1. Campos obligatorios vacíos
● Si alguno de los campos obligatorios no fue completado, el sistema muestra un
mensaje indicando qué información falta y solicita completarla.
A2. Precio o stock inválidos
● Si el precio o el stock ingresados son menores a cero, el sistema informa el error y
no permite guardar el producto.
A3. Producto duplicado
● Si ya existe un producto con el mismo nombre y categoría, el sistema informa la
situación y evita registrarlo nuevamente.
Postcondiciones
● El nuevo producto queda almacenado en la base de datos.
● El inventario se actualiza mostrando el nuevo producto.
● El administrador puede consultar, modificar o eliminar ese producto cuando lo
necesite.
Ejercicio 3 – Diagrama de Flujo de Datos (DFD)
Explicación
El proceso comienza cuando el administrador ingresa los datos del nuevo producto. El
sistema verifica que la información sea válida (por ejemplo, que el nombre no esté vacío y
que el precio y el stock sean correctos). Si encuentra algún error, informa al usuario para
que lo corrija. Si los datos son válidos, el producto se almacena en la base de datos y el
sistema confirma que el registro fue realizado correctamente.
Ejercicio 4 – Diseño de la Interfaz de Usuario
Descripción
La pantalla principal permitirá al administrador acceder rápidamente a las funciones más
importantes del sistema de inventario.
La interfaz contará con:
● Un encabezado con el nombre del sistema.
● Un menú lateral con las opciones principales.
● Un panel central donde se visualizarán los productos.
● Botones para agregar, editar y eliminar productos.
● Una barra de búsqueda.
Lo que verá el usuario:
---------------------------------------------------------
Sistema de Gestión de Inventario
---------------------------------------------------------
Menú Productos
Inicio Buscar: [_____________] 🔍
Inventario +-----------------------------+
| Nombre | Precio | Stock |
Productos | Mouse | $12000 | 15 |
| Teclado| $35000 | 8 |
Reportes | Monitor| $95000 | 4 |
+-----------------------------+
Usuarios
---------------------------------------------------------
[+ Agregar] [Editar] [Eliminar]
---------------------------------------------------------
Explicación
Esta pantalla fue diseñada para que el usuario pueda acceder rápidamente a las funciones
principales del sistema. La información del inventario se presenta de forma organizada y las
acciones más utilizadas se encuentran siempre visibles.
Ejercicio 5 – Arquitectura del Sistema
Arquitectura elegida: MVC (Modelo – Vista –
Controlador)
Para el desarrollo de la aplicación web de gestión de inventario se eligió la arquitectura
MVC (Modelo – Vista – Controlador), ya que permite organizar el sistema en tres
componentes bien diferenciados, facilitando el desarrollo, el mantenimiento y futuras
ampliaciones.
Componentes
Modelo (Model)
Se encarga de administrar los datos del sistema y de interactuar con la base de datos.
Ejemplo:
● Producto
● Usuario
● Inventario
Vista (View)
Es la interfaz que utiliza el usuario para interactuar con el sistema.
Ejemplo:
● Pantalla de inicio.
● Lista de productos.
● Formulario "Agregar Producto".
Controlador (Controller)
Recibe las acciones del usuario, valida la información y coordina la comunicación entre la
Vista y el Modelo.
Ejemplo:
● Registrar un producto.
● Modificar un producto.
● Eliminar un producto.
¿Por qué elegimos MVC?
Esta arquitectura presenta varias ventajas:
● Separa la lógica del negocio de la interfaz gráfica.
● Facilita el mantenimiento del código.
● Permite trabajar en equipo de forma más organizada.
● Hace más sencillo incorporar nuevas funcionalidades.
● Es una de las arquitecturas más utilizadas en aplicaciones web.
Por estas razones, MVC resulta una excelente opción para el desarrollo del sistema de
gestión de inventario.
Ejercicio 6 – Diseño de la Base de Datos
Descripción
La base de datos permitirá almacenar la información de los usuarios, los productos y las
categorías del inventario. De esta manera, el sistema podrá registrar nuevos productos,
consultarlos, modificarlos y eliminarlos.
Tabla: Usuario
Campo Tipo Descripción
id_usuario INT Identificador del usuario
nombre VARCHAR(100) Nombre del usuario
email VARCHAR(100) Correo electrónico
contraseñ
a
VARCHAR(255) Contraseña
Tabla: Categoria
Campo Tipo Descripción
id_categoria INT Identificador de la categoría
nombre VARCHAR(100) Nombre de la categoría
Tabla: Producto
Campo Tipo Descripción
id_producto INT Identificador del producto
nombre VARCHAR(100) Nombre del producto
descripción VARCHAR(255) Descripción
precio DECIMAL(10,2) Precio
stock INT Cantidad disponible
id_categoria INT Categoría del producto
Relaciones
● Una categoría puede tener muchos productos.
● Un producto pertenece a una sola categoría.
● Un usuario administra el inventario mediante la aplicación.
Explicación
Esta base de datos permite organizar la información de manera sencilla y evita repetir datos
innecesarios. Separar las categorías de los productos facilita la administración del inventario
y hace que el sistema sea más escalable.
Ejercicio 7 – Implementación de "Agregar un Nuevo Producto"
¿Qué hace este programa?
1. Crea una clase llamada Producto.
2. Solicita al usuario los datos del producto.
3. Crea un objeto con esa información.
4. Lo guarda en una lista que representa el inventario.
5. Muestra un mensaje indicando que el producto fue agregado correctamente.
Explicación
Esta implementación representa de manera sencilla la funcionalidad de agregar un
producto. El usuario ingresa la información solicitada y el sistema crea un nuevo producto
que se almacena en el inventario. En una aplicación real, estos datos se guardarían en una
base de datos en lugar de una lista en memoria.
Ejercicio 9 – Pruebas Unitarias
Objetivo
Verificar que la función Agregar Producto funcione correctamente en distintas situaciones,
tanto cuando los datos son válidos como cuando presentan errores.
Casos de prueba
Cas
o
Datos de entrada Resultado esperado
1 Nombre: Mouse, Precio: 25000,
Stock: 15
El producto se agrega correctamente.
2 Nombre vacío El sistema muestra "El nombre es obligatorio".
3 Precio = -100 El sistema informa que el precio debe ser
mayor que cero.
4 Stock = -5 El sistema informa que el stock no puede ser
negativo.
5 Producto ya existente El sistema informa que el producto ya existe y
no lo registra.
Resultado esperado
Si todas las pruebas son satisfactorias, el sistema valida correctamente los datos y solo
permite registrar productos con información válida.
Ejercicio 10 – Pruebas de Integración
Objetivo
Comprobar que los distintos componentes del sistema trabajen correctamente en conjunto.
Casos de prueba
Prueba 1
Acción:
El usuario completa el formulario con datos válidos y presiona Guardar.
Resultado esperado:
● El formulario envía los datos.
● La lógica de negocio valida la información.
● El producto se guarda en la base de datos.
● Se muestra el mensaje "Producto agregado correctamente".
Prueba 2
Acción:
El usuario ingresa un precio negativo.
Resultado esperado:
● La lógica de negocio detecta el error.
● No se guarda el producto.
● Se muestra el mensaje correspondiente.
Prueba 3
Acción:
El usuario intenta registrar un producto repetido.
Resultado esperado:
● El sistema detecta que el producto ya existe.
● No lo almacena nuevamente.
● Informa el motivo al usuario.
Resultado esperado
Las pruebas de integración demuestran que la interfaz, la lógica de negocio y la base de
datos funcionan correctamente como un único sistema, garantizando que el proceso de
registrar un producto se realice sin inconvenientes.
Ejercicio 11 – Plan de Despliegue
Objetivo
Implementar la aplicación en un entorno de producción de forma segura, asegurando que el
sistema funcione correctamente y minimizando el riesgo de errores.
Plan de Despliegue
1. Preparación
● Verificar que todas las pruebas unitarias y de integración hayan sido aprobadas.
● Realizar una copia de seguridad de la base de datos.
● Confirmar que el servidor cumpla con los requisitos del sistema.
2. Instalación
● Subir la aplicación al servidor de producción.
● Configurar la conexión con la base de datos.
● Instalar las dependencias necesarias para el funcionamiento del sistema.
3. Verificación
● Comprobar que el sistema inicie correctamente.
● Verificar el funcionamiento del inicio de sesión.
● Comprobar que sea posible agregar, modificar, eliminar y consultar productos.
4. Puesta en producción
● Habilitar el acceso a los usuarios.
● Supervisar el funcionamiento durante las primeras horas.
● Registrar cualquier inconveniente detectado.
5. Monitoreo
● Controlar el rendimiento del sistema.
● Verificar el uso de la base de datos.
● Realizar copias de seguridad periódicas.
Explicación
El plan de despliegue permite organizar todas las actividades necesarias para poner en
funcionamiento la aplicación de forma segura, reduciendo la posibilidad de errores durante
la instalación.
Ejercicio 12 – Despliegue de la
Aplicación
Descripción
Para desplegar la aplicación web de gestión de inventario se seguirá el siguiente
procedimiento:
1. Preparación del servidor
Se configura un servidor con los recursos necesarios para ejecutar la aplicación y alojar la
base de datos.
2. Instalación de la aplicación
Se copian los archivos del proyecto al servidor y se instalan todas las dependencias
necesarias para su funcionamiento.
3. Configuración
Se establece la conexión entre la aplicación y la base de datos, verificando que los
parámetros de acceso sean correctos.
4. Pruebas
Antes de habilitar el sistema para los usuarios, se realizan pruebas para comprobar que
todas las funcionalidades principales funcionan correctamente, como:
● Inicio de sesión.
● Agregar productos.
● Modificar productos.
● Eliminar productos.
● Consultar el inventario.
5. Publicación
Una vez verificadas las pruebas, la aplicación queda disponible para que los usuarios
puedan acceder desde un navegador web.
6. Monitoreo
Durante los primeros días de funcionamiento se supervisa el rendimiento del sistema y se
registran posibles errores para corregirlos rápidamente.
Conclusión
Este procedimiento permite poner en funcionamiento la aplicación de forma ordenada y
segura, asegurando que los usuarios puedan utilizar el sistema correctamente desde el
primer momento.
Ejercicio 13 – Plan de Mantenimiento
Objetivo
Garantizar que la aplicación web continúe funcionando correctamente después de su
implementación, realizando tareas de actualización, corrección y mejora de manera
periódica.
Plan de mantenimiento
1. Mantenimiento Correctivo
Consiste en corregir errores que puedan aparecer durante el uso de la aplicación.
Ejemplos:
● Solucionar errores al agregar productos.
● Corregir fallas en la búsqueda del inventario.
● Reparar problemas de conexión con la base de datos.
2. Mantenimiento Preventivo
Se realizan tareas para evitar futuros inconvenientes.
Ejemplos:
● Actualizar las dependencias del sistema.
● Optimizar la base de datos.
● Realizar copias de seguridad periódicas.
● Revisar el rendimiento del servidor.
3. Mantenimiento Adaptativo
Permite que la aplicación continúe funcionando cuando cambian las necesidades del
entorno.
Ejemplos:
● Adaptar el sistema a una nueva versión del sistema operativo.
● Actualizar la aplicación para que sea compatible con nuevos navegadores.
● Incorporar cambios solicitados por la empresa.
4. Mantenimiento Evolutivo
Consiste en agregar nuevas funcionalidades para mejorar el sistema.
Ejemplos:
● Incorporar un módulo de reportes.
● Agregar un sistema de códigos de barras.
● Implementar notificaciones de bajo stock.
● Permitir exportar el inventario a Excel o PDF.
Conclusión
Un plan de mantenimiento permite mantener la aplicación actualizada, segura y funcionando
correctamente a lo largo del tiempo. Además, facilita la incorporación de mejoras y reduce el
riesgo de fallas que puedan afectar a los usuarios.
Ejercicio 14 – Corrección de Errores
Problema detectado
Durante las pruebas del sistema se observó que era posible registrar un producto con un
stock negativo. Esto generaba información incorrecta en el inventario.
Solución implementada
Se agregó una validación antes de guardar el producto para verificar que el valor del stock
sea mayor o igual a cero. Si el usuario ingresa un número negativo, el sistema muestra un
mensaje de error y no permite registrar el producto.
Código de la corrección
if stock < 0:
print("Error: El stock no puede ser negativo.")
return
Resultado
Después de incorporar esta validación:
● No es posible registrar productos con stock negativo.
● Se evita almacenar información incorrecta en la base de datos.
● Se mejora la confiabilidad del sistema.
Conclusión
La corrección implementada mejora la calidad de la aplicación al evitar errores en la
información almacenada. Además, contribuye a que el inventario sea más confiable y
consistente para los usuarios.
Ejercicio 15 – Equipo de Trabajo para un
Proyecto de Inteligencia Artificial
Generativa
Proyecto
Se propone desarrollar una aplicación web que utilice Inteligencia Artificial Generativa
para asistir a los usuarios en la creación automática de documentos, informes y respuestas
a consultas.
Equipo de trabajo
Product Owner (PO)
Es el responsable de definir los objetivos del proyecto, priorizar las funcionalidades y
representar las necesidades del cliente.
Scrum Master
Coordina el trabajo del equipo, organiza las reuniones y ayuda a eliminar los obstáculos que
puedan afectar el desarrollo.
Desarrollador Backend
Se encarga de desarrollar la lógica de negocio, implementar las funcionalidades del sistema
y gestionar la comunicación con la base de datos y los servicios de inteligencia artificial.
Desarrollador Frontend
Diseña e implementa la interfaz gráfica para que los usuarios puedan interactuar con la
aplicación de manera sencilla e intuitiva.
Especialista en Inteligencia Artificial
Integra y configura los modelos de IA generativa, ajustando su funcionamiento para obtener
respuestas útiles y de calidad.
Tester (QA)
Realiza pruebas para detectar errores, validar el correcto funcionamiento del sistema y
asegurar la calidad del producto antes de su entrega.
Diseñador UX/UI
Diseña la experiencia del usuario y la apariencia visual de la aplicación, buscando que sea
clara, moderna y fácil de utilizar.
Organización del trabajo
El equipo trabajará utilizando la metodología Scrum, organizando el desarrollo en Sprints
de dos semanas. Al finalizar cada Sprint se realizará una revisión del trabajo realizado y
una retrospectiva para identificar oportunidades de mejora. Además, se llevarán a cabo
reuniones diarias (Daily Scrum) para hacer seguimiento del avance y resolver posibles
inconvenientes.
Conclusión
La correcta definición de los roles permite distribuir las responsabilidades de manera
organizada, mejorar la comunicación entre los integrantes del equipo y desarrollar un
producto de mayor calidad. En proyectos relacionados con inteligencia artificial generativa,
