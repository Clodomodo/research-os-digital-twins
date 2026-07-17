# Arquitectura de una propuesta doctoral

## Título provisional

**Metodología matemática y computacional para el desarrollo de gemelos digitales reproducibles de sistemas electromecánicos multifísicos mediante modelado acausal, datos sintéticos y computación distribuida.**

---

# Hipótesis central

Es posible desarrollar una metodología general, reproducible y escalable para la construcción de gemelos digitales de alta fidelidad utilizando:

- modelos físicos,
- modelado acausal,
- datos sintéticos informados por física,
- sensores virtuales,
- computación distribuida de bajo costo.

---

# Problema científico

Actualmente muchos gemelos digitales:

- dependen excesivamente de datos,
- utilizan modelos difíciles de reproducir,
- requieren infraestructura costosa,
- carecen de una metodología unificada.

La investigación propone un marco matemático y computacional que reduzca estas limitaciones.

---

# Pregunta doctoral

¿Cómo desarrollar una metodología matemática reproducible para construir gemelos digitales multifísicos capaces de estimar estados internos y ejecutarse eficientemente sobre infraestructura computacional heterogénea?

---

# Objetivo general

Diseñar, implementar y validar una metodología para el desarrollo de gemelos digitales reproducibles de sistemas electromecánicos basada en modelos físicos, simulación multifísica, datos sintéticos y sensores virtuales.

---

# Objetivos específicos

1. Formular modelos matemáticos del sistema electromecánico.

2. Implementar modelos acausales en OpenModelica.

3. Generar datasets sintéticos informados por física.

4. Integrar datos experimentales mediante modelos híbridos.

5. Diseñar sensores virtuales para variables no medibles.

6. Implementar una arquitectura distribuida Edge-to-Cloud utilizando Python.

7. Validar experimentalmente el gemelo digital.

8. Generalizar la metodología hacia máquinas multifásicas.

---

# Núcleo matemático

La tesis gira alrededor de cuatro problemas:

## Modelado

Representación matemática del sistema dinámico.

---

## Observabilidad

¿Qué estados internos pueden reconstruirse?

---

## Estimación

¿Cómo obtener variables que no pueden medirse?

---

## Validación

¿Cómo demostrar que el gemelo digital representa adecuadamente al sistema físico?

---

# Contribuciones esperadas

## Teóricas

- Metodología general.
- Arquitectura matemática.
- Marco reproducible.

---

## Computacionales

- Framework OpenModelica + Python.
- Orquestación distribuida.
- Infraestructura heterogénea.

---

## Experimentales

- Validación del AF-PMSG.
- Dataset reproducible.
- Sensores virtuales.

---

## Extensiones

- Cinco fases.
- Siete fases.
- Otros sistemas electromecánicos.

---

# Productos científicos asociados

| Producto | Función dentro de la tesis |
|----------|----------------------------|
| Libro Fourier-Laplace | Fundamentos matemáticos |
| Libro ngspice | Simulación reproducible |
| Artículo 1 | Modelo híbrido |
| Artículo 2 | Gemelo digital |
| Protocolo Edge-to-Cloud | Computación distribuida |
| Dataset | Validación |
| Framework GitHub | Ciencia abierta |

---

# Visión de largo plazo

Construir un marco abierto para el desarrollo de gemelos digitales reproducibles que pueda aplicarse no solo a generadores de flujo axial, sino también a otros sistemas eléctricos y electromecánicos.
