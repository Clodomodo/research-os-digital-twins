# Arquitectura Edge-to-Cloud para Gemelos Digitales

## Propósito

Diseñar una arquitectura computacional heterogénea para ejecutar simulaciones
de alta fidelidad asociadas a gemelos digitales de sistemas electromecánicos.

---

# Motivación

Los modelos multifísicos de alta fidelidad pueden requerir tiempos de cálculo
elevados.

Esta investigación estudia la posibilidad de utilizar infraestructura
accesible formada por múltiples equipos con diferentes capacidades
computacionales.

---

# Arquitectura propuesta
                Gemelo digital

                     |

                     v

             Orquestador Python

                     |

    +----------------+----------------+

    |                |                |

    v                v                v

  Nodo 1           Nodo 2          Nodo N
    |                |                |

    +----------------+----------------+

                     |

                     v

          Integración de resultados

          
---

# Componentes

## Capa física

Incluye:

- Generador axial de imanes permanentes.
- Modelo electromagnético.
- Modelo térmico.
- Modelo mecánico.

---

## Capa de simulación

Herramienta:

- OpenModelica.

Características:

- Modelado acausal.
- Sistemas multifísicos.
- Ecuaciones diferenciales algebraicas.

---

## Capa de orquestación

Herramienta:

- Python.

Funciones:

- Gestión de tareas.
- Comunicación con nodos.
- Configuración de parámetros.
- Recolección de resultados.

---

## Capa computacional

Infraestructura:

- Cinco computadoras heterogéneas.

Cada nodo puede presentar:

- Diferente procesador.
- Diferente memoria.
- Diferente capacidad de cálculo.

---

# Problema de investigación

¿Cómo distribuir eficientemente simulaciones de gemelos digitales entre
recursos computacionales heterogéneos manteniendo reproducibilidad y
precisión científica?

---

# Líneas de evaluación

## Rendimiento

Métricas:

- Tiempo total de simulación.
- Tiempo por tarea.
- Utilización de recursos.

---

## Escalabilidad

Evaluación:

- Número de simulaciones.
- Complejidad del modelo.
- Número de nodos.

---

## Reproducibilidad

Registro:

- Hardware.
- Software.
- Parámetros.
- Resultados.

---

# Trabajo futuro

- Balanceo dinámico de carga.
- Optimización del reparto de tareas.
- Integración con sensores virtuales.
- Ejecución de modelos multifásicos.
