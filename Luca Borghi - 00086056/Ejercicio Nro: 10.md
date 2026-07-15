# Ejercicio Nro: 10

## Enunciado

Ejecuta pruebas de integración para la funcionalidad de **"Agregar un nuevo producto"** en la aplicación web del ejercicio 1.

## Resolución

### Objetivo

Comprobar que los distintos componentes del sistema trabajen correctamente en conjunto.

### Casos de prueba

#### Prueba 1

**Acción:**

El usuario completa el formulario con datos válidos y presiona **Guardar**.

**Resultado esperado:**

- El formulario envía los datos.
- La lógica de negocio valida la información.
- El producto se guarda en la base de datos.
- Se muestra el mensaje **"Producto agregado correctamente"**.

---

#### Prueba 2

**Acción:**

El usuario ingresa un precio negativo.

**Resultado esperado:**

- La lógica de negocio detecta el error.
- No se guarda el producto.
- Se muestra el mensaje correspondiente.

---

#### Prueba 3

**Acción:**

El usuario intenta registrar un producto repetido.

**Resultado esperado:**

- El sistema detecta que el producto ya existe.
- No lo almacena nuevamente.
- Informa el motivo al usuario.

---

### Resultado esperado

Las pruebas de integración demuestran que la interfaz, la lógica de negocio y la base de datos funcionan correctamente como un único sistema, garantizando que el proceso de registrar un producto se realice sin inconvenientes.
