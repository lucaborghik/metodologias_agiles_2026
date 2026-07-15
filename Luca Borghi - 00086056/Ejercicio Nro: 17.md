# Ejercicio Nro: 17

## Enunciado

Aplicar el método COSMIC para estimar el tamaño funcional, el costo y la duración de un proyecto de desarrollo de una aplicación para la gestión de finanzas personales.


## Resolución

# Aplicación

Aplicación para la gestión de finanzas personales.

La aplicación permitirá:

- Gestionar cuentas bancarias.
- Registrar ingresos y gastos.
- Administrar deudas.
- Visualizar reportes y gráficos.
- Exportar información en PDF y CSV.

---

## 1. Identificación de las interacciones funcionales

### Gestión de cuentas bancarias

| Funcionalidad | Movimientos COSMIC |
|---------------|-------------------:|
| Crear cuenta | 4 |
| Consultar saldo | 3 |
| Consultar movimientos | 3 |
| Transferencia entre cuentas | 5 |
| Exportar movimientos | 2 |

**Total: 17 CFP**

---

### Gestión de ingresos y gastos

| Funcionalidad | Movimientos COSMIC |
|---------------|-------------------:|
| Registrar ingreso | 4 |
| Registrar gasto | 4 |
| Editar ingreso o gasto | 4 |
| Consultar por categoría | 3 |
| Mostrar gráficos | 3 |
| Crear presupuesto | 4 |

**Total: 22 CFP**

---

### Gestión de deudas

| Funcionalidad | Movimientos COSMIC |
|---------------|-------------------:|
| Crear deuda | 4 |
| Consultar deuda | 3 |
| Registrar pago | 5 |
| Simular pagos | 4 |
| Generar informe | 3 |

**Total: 19 CFP**

---

### Tamaño funcional

| Módulo | CFP |
|---------|----:|
| Gestión de cuentas | 17 |
| Gestión de ingresos y gastos | 22 |
| Gestión de deudas | 19 |

**Total del proyecto**

17 + 22 + 19 = **58 Puntos de Función COSMIC (CFP).**

---

## 2. Cálculo del costo por punto de función

Tomando como referencia el ejemplo visto en clase y considerando un proyecto de complejidad media, se estima un costo de:

**Costo por Punto de Función (CPCF):**

**900 USD por CFP.**

---

## 3. Productividad del equipo

Se considera un equipo de **7 desarrolladores**.

Según la experiencia del equipo se estima una productividad de:

**30 Puntos COSMIC por mes.**

---

## 4. Duración del proyecto

**Fórmula:**

Duración = CFP Totales / CFP por mes

58 / 30 = **1,93 meses**

**Duración estimada:** aproximadamente **2 meses.**

---

## 5. Costo del proyecto

**Fórmula:**

Costo = CFP Totales × Costo por Punto de Función

58 × 900 USD =

**52.200 USD**

---

## Resultado Final

| Concepto | Valor |
|----------|-------|
| Tamaño funcional | 58 CFP |
| Costo por CFP | 900 USD |
| Productividad del equipo | 30 CFP/mes |
| Duración estimada | 1,93 meses (≈ 2 meses) |
| Costo total del proyecto | 52.200 USD |

---

## Conclusión

Mediante el método COSMIC fue posible estimar el tamaño funcional de la aplicación a partir de sus funcionalidades principales. Con esa información se calculó el tiempo aproximado de desarrollo y el costo del proyecto, obteniendo una estimación de **58 Puntos de Función COSMIC**, una duración cercana a **2 meses** y un costo estimado de **52.200 USD**. Este tipo de estimación resulta útil para planificar recursos, tiempos y presupuesto antes de comenzar el desarrollo del software.
