# Reproducibilidad científica

## Propósito

Establecer una metodología que permita reconstruir, verificar y extender
los resultados obtenidos en investigaciones relacionadas con gemelos
digitales de sistemas electromecánicos.

La reproducibilidad es un principio central del proyecto.

---

# Principio general

Un resultado científico debe estar asociado con:

- Modelo.
- Código.
- Datos.
- Parámetros.
- Configuración.
- Documentación.
- Procedimiento experimental.

---

# Arquitectura reproducible

## 1. Modelo

Incluye:

- Ecuaciones físicas.
- Parámetros del sistema.
- Supuestos utilizados.
- Versiones del modelo.

Ejemplos:

- Modelos Modelica.
- Modelos térmicos.
- Modelos electromagnéticos.

---

## 2. Código

Lenguajes principales:

- Python.
- Modelica.

Buenas prácticas:

- Control de versiones con Git.
- Código documentado.
- Ejemplos mínimos reproducibles.

---

## 3. Datos

Tipos de datos:

### Datos experimentales

Obtenidos mediante pruebas físicas.

### Datos sintéticos

Generados mediante modelos informados por física.

Ambos deben conservar:

- Formato.
- Unidades.
- Parámetros de generación.
- Fecha.
- Versión.

---

## 4. Entorno computacional

Registrar:

- Sistema operativo.
- Versión de Python.
- Librerías utilizadas.
- Versión de OpenModelica.
- Hardware utilizado.

---

## 5. Experimentos

Cada experimento debe contener:

Experimento
|
+-- Objetivo
|
+-- Configuración
|
+-- Parámetros
|
+-- Ejecución
|
+-- Resultados
|
+-- Análisis


---

# Estrategia de publicación

Los resultados pueden distribuirse mediante:

- GitHub para código.
- Zenodo para versiones con DOI.
- Documentación Markdown.
- Datasets públicos cuando sea posible.

---

# Infraestructura experimental

La plataforma computacional considera:

- Cinco computadoras heterogéneas.
- Diferentes capacidades de procesamiento.
- Orquestación mediante Python.

Objetivo:

Evaluar la viabilidad de simulaciones distribuidas para gemelos digitales
de alta fidelidad utilizando infraestructura accesible.

---

# Criterios de validación

Un resultado será considerado reproducible cuando:

- El modelo pueda ejecutarse nuevamente.
- Los parámetros estén disponibles.
- Los datos puedan ser regenerados o consultados.
- El procedimiento esté documentado.
- Los resultados sean comparables.

---

# Filosofía

La reproducibilidad no depende únicamente de publicar código.

Implica comunicar claramente:

- Qué se hizo.
- Por qué se hizo.
- Cómo se puede repetir.
- Cómo se puede mejorar.
