# Modelos matemáticos

## Propósito

Documentar las formulaciones matemáticas utilizadas para representar
sistemas electromecánicos dentro de la línea de investigación.

El objetivo es mantener una separación clara entre:

- Modelo matemático.
- Implementación computacional.
- Resultados experimentales.

---

# Representación general del sistema

Un sistema dinámico puede representarse como:

\[
\dot{x}=f(x,u,p,t)
\]

\[
y=g(x,u,p,t)
\]

donde:

## Estados

x:

Variables internas del sistema.

Ejemplos:

- Temperatura del rotor.
- Flujo magnético.
- Velocidad angular.

---

## Entradas

u:

Variables externas.

Ejemplos:

- Carga eléctrica.
- Velocidad mecánica.
- Condiciones de operación.

---

## Parámetros

p:

Características físicas del sistema.

Ejemplos:

- Resistencia eléctrica.
- Inductancias.
- Masa.
- Coeficientes térmicos.

---

## Salidas

y:

Variables observables.

Ejemplos:

- Voltaje.
- Corriente.
- Potencia.
- Temperatura estimada.

---

# Modelo eléctrico

Elementos considerados:

- Fuerza electromotriz.
- Corrientes de fase.
- Resistencias.
- Inductancias.

Aplicación:

Generador síncrono de imanes permanentes.

Estado:

En desarrollo.

---

# Modelo térmico

Objetivo:

Representar la evolución temporal de temperaturas internas.

Variables:

- Pérdidas eléctricas.
- Transferencia de calor.
- Temperatura del rotor.

Aplicación:

Sensor virtual térmico.

Estado:

En desarrollo.

---

# Modelo mecánico

Variables:

- Torque.
- Velocidad angular.
- Inercia.

Representación general:

\[
J\frac{d\omega}{dt}=T_e-T_L-B\omega
\]

donde:

J:

Momento de inercia.

Te:

Torque electromagnético.

TL:

Torque de carga.

B:

Coeficiente de fricción.

---

# Relación con Modelica

Las ecuaciones matemáticas se implementan mediante:

- Componentes físicos.
- Conectores.
- Relaciones acausales.

---

# Relación con el gemelo digital

Flujo:

Modelo matemático

↓

Modelo OpenModelica

↓

Datos sintéticos

↓

Modelo híbrido

↓

Sensor virtual

↓

Diagnóstico

---

# Trabajo futuro

- Modelo completo electromagnético-térmico-mecánico.
- Extensión a cinco fases.
- Extensión a siete fases.
- Análisis de observabilidad.
