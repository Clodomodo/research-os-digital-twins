# Marco metodológico

## Propósito

Desarrollar una metodología reproducible para la construcción de gemelos digitales de sistemas electromecánicos mediante modelos físicos, simulación computacional, datos sintéticos y validación experimental.

---

# Arquitectura general de investigación

La metodología se organiza en capas:

Sistema físico
|
v
Modelo matemático
|
v
Modelo acausal
|
v
Simulación multifísica
|
v
Datos sintéticos informados por física
|
v
Datos experimentales
|
v
Modelo híbrido
|
v
Sensor virtual
|
v
Gemelo digital
|
v
Diagnóstico y predicción


---

# Capa 1: Modelado físico

Representación matemática del sistema electromecánico considerando:

- Variables eléctricas.
- Variables magnéticas.
- Variables térmicas.
- Variables mecánicas.

El sistema principal de estudio son generadores síncronos de imanes permanentes de flujo axial.

---

# Capa 2: Modelado acausal

Uso de modelos basados en componentes físicos donde las relaciones entre variables son definidas por ecuaciones de conservación.

Características:

- Modelos reutilizables.
- Interacción entre dominios físicos.
- Representación mediante ecuaciones diferenciales algebraicas (DAE).

Herramienta principal:

- OpenModelica / Modelica.

---

# Capa 3: Generación de datos

Se combinan:

- Datos experimentales.
- Datos sintéticos generados por modelos físicos.

Objetivo:

Crear datasets reproducibles para análisis estadístico y aprendizaje basado en física.

---

# Capa 4: Modelo híbrido

Integración de:

- Modelos físicos.
- Métodos estadísticos.
- Análisis de señales.

Objetivo:

Mejorar la representación del sistema cuando existen incertidumbres o información incompleta.

---

# Capa 5: Sensores virtuales

Estimación de variables no disponibles mediante modelos matemáticos.

Ejemplos:

- Temperatura interna del rotor.
- Estados térmicos.
- Variables electromagnéticas.

---

# Capa 6: Computación distribuida

Implementación de una arquitectura heterogénea:

- Cinco computadoras con diferentes capacidades.
- Orquestación mediante Python.
- Distribución de simulaciones.
- Evaluación del desempeño computacional.

Objetivo:

Analizar la viabilidad de gemelos digitales de alta fidelidad con infraestructura accesible.

---

# Capa 7: Validación

La validación considera:

- Comparación modelo-experimento.
- Error de predicción.
- Reproducibilidad.
- Documentación completa.

---

# Principios de investigación

## Reproducibilidad

Cada resultado debe poder ser reconstruido mediante:

- Código.
- Datos.
- Parámetros.
- Documentación.

## Ciencia abierta

Se prioriza:

- Software abierto.
- Herramientas accesibles.
- Compartición responsable de resultados.

## Modularidad

Cada componente puede evolucionar de forma independiente:

- Modelo físico.
- Dataset.
- Algoritmo.
- Infraestructura computacional.
