# Roadmap de investigación

## Visión general

El objetivo de esta línea de investigación es desarrollar un marco reproducible para la creación de gemelos digitales de sistemas electromecánicos mediante modelado físico, simulación computacional y validación experimental.

---

# Etapa 1 — Fundamentos matemáticos y computacionales

## Objetivo

Construir las bases matemáticas para el análisis de señales y sistemas dinámicos.

## Actividades

- Transformada de Fourier.
- Transformada de Laplace.
- Análisis de circuitos.
- Simulación numérica.
- Programación científica con Python.

## Productos

- Libro:
  "Mi amigo Fourier y su compañero Laplace".
- Libro:
  "Análisis de circuitos con ngspice, Falstad y Python".

Estado:

🟡 En desarrollo / revisión.

---

# Etapa 2 — Modelo físico del generador axial

## Objetivo

Desarrollar un modelo reproducible de un generador síncrono de imanes permanentes de flujo axial.

## Actividades

- Modelado electromagnético.
- Modelado térmico.
- Generación de datos sintéticos.
- Validación experimental.

## Producto

Artículo:

"Hybrid Statistical Modeling of an Axial Flux PMSG Using Experimental and Physics-Informed Synthetic Data"

Estado:

🟡 En revisión.

---

# Etapa 3 — Gemelo digital y diagnóstico

## Objetivo

Utilizar el gemelo digital para detectar desviaciones del comportamiento esperado.

## Actividades

- Integración modelo-datos.
- Análisis estadístico.
- Detección de anomalías.
- Evaluación bajo cargas resistivas.

## Producto

Artículo:

"Digital Twin-Driven Anomaly Detection in Additively Manufactured Axial Flux Generators Under Purely Resistive Loads"

Estado:

🟡 En revisión.

---

# Etapa 4 — Orquestación computacional

## Objetivo

Desarrollar una arquitectura distribuida para simulación de alta fidelidad.

## Actividades

- Cinco computadoras heterogéneas.
- Orquestación mediante Python.
- Distribución de simulaciones.
- Evaluación del rendimiento.

## Producto esperado

Protocolo:

"Orquestación heterogénea Edge-to-Cloud para gemelos digitales de alta fidelidad en generadores de flujo axial"

Estado:

🟡 Desarrollo.

---

# Etapa 5 — Sensores virtuales

## Objetivo

Estimar variables internas no disponibles mediante medición directa.

## Variables objetivo

- Temperatura del rotor.
- Estados térmicos.
- Variables electromagnéticas.

Métodos:

- Modelos físicos.
- Estimación de estados.
- Modelos híbridos.

Estado:

⚪ Planeado.

---

# Etapa 6 — Sistemas multifásicos

## Objetivo

Generalizar la metodología hacia máquinas con mayor número de fases.

## Líneas futuras

- PMSG cinco fases.
- PMSG siete fases.
- Comparación con modelo trifásico.

Estado:

⚪ Planeado.

---

# Etapa 7 — Repositorio científico reproducible

## Objetivo

Construir un laboratorio digital abierto.

Componentes:

- Código.
- Modelos.
- Datos.
- Documentación.
- Resultados.

Principio:

Cada resultado debe poder ser reconstruido a partir de los elementos disponibles.
