# Modelos OpenModelica

## Propósito

Esta sección contiene la documentación de los modelos físicos desarrollados
para la simulación de sistemas electromecánicos mediante Modelica/OpenModelica.

---

# Filosofía de modelado

Los modelos se desarrollan utilizando un enfoque acausal basado en:

- Componentes físicos.
- Relaciones de conservación.
- Ecuaciones diferenciales algebraicas (DAE).
- Interacción entre dominios físicos.

---

# Sistema principal

## Generador síncrono de imanes permanentes de flujo axial (AF-PMSG)

Dominios considerados:

- Electromagnético.
- Térmico.
- Mecánico.

---

# Modelos previstos

## Modelo eléctrico

Incluye:

- Variables de fase.
- Voltajes.
- Corrientes.
- Potencia generada.

---

## Modelo térmico

Incluye:

- Pérdidas.
- Transferencia de calor.
- Temperatura del rotor.
- Estados térmicos internos.

---

## Modelo mecánico

Incluye:

- Velocidad.
- Torque.
- Dinámica rotacional.

---

# Gemelo digital

El modelo OpenModelica representa el núcleo físico del gemelo digital.

Flujo:

Modelo físico

↓

Simulación

↓

Datos sintéticos

↓

Estimación de estados

↓

Sensor virtual

↓

Diagnóstico

---

# Extensiones futuras

- Generadores de cinco fases.
- Generadores de siete fases.
- Modelos multifísicos de mayor fidelidad.

---

# Reproducibilidad

Cada modelo debe incluir:

- Descripción física.
- Parámetros.
- Unidades.
- Versión.
- Ejemplo de ejecución.
