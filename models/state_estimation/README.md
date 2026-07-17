# Sensores virtuales y estimación de estados

## Propósito

Documentar los métodos utilizados para estimar variables internas de sistemas
electromecánicos que no pueden medirse directamente.

---

# Concepto

Un sensor virtual combina:

- Modelo matemático.
- Mediciones disponibles.
- Algoritmo de estimación.

Representación general:

\[
\dot{x}=f(x,u)
\]

\[
y=h(x)
\]

donde:

x:

Estado interno.

u:

Entrada conocida.

y:

Salida medida.

---

# Objetivo principal

Estimar variables como:

- Temperatura interna del rotor.
- Estados térmicos.
- Variables electromagnéticas.

utilizando información disponible del sistema.

---

# Arquitectura

Sistema físico

  |

Sensores reales

  |

Datos medidos

  |

Estimador

  |

Estado estimado

  |

Sensor virtual


---

# Métodos considerados

## Modelo basado en física

Utiliza:

- Ecuaciones térmicas.
- Parámetros del generador.
- Condiciones de operación.

---

## Observadores

Métodos posibles:

- Observador de Luenberger.
- Filtro de Kalman.
- Estimadores basados en modelos.

---

## Modelo híbrido

Combina:

- Modelo físico.
- Datos experimentales.
- Métodos estadísticos.

---

# Aplicación al AF-PMSG

Variable objetivo:

Temperatura del rotor.

Entradas posibles:

- Corriente.
- Voltaje.
- Velocidad.
- Carga.
- Condiciones ambientales.

---

# Validación

La estimación será evaluada mediante:

- Error absoluto.
- Error cuadrático medio.
- Comparación modelo-experimento.

---

# Relación con el gemelo digital

Flujo:

Datos reales

↓

Modelo físico

↓

Estimador

↓

Estado interno

↓

Actualización del gemelo digital

↓

Diagnóstico

---

# Trabajo futuro

- Observabilidad del sistema.
- Estimación térmica en tiempo real.
- Extensión a máquinas multifásicas.
- Integración edge-to-cloud.
