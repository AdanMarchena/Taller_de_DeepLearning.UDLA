# Planificación inicial del proyecto

## Fase 1
**Estado del arte**
Definir
* problema
* hipótesis
* objetivo general
* objetivos específicos
* pregunta de investigación

## Fase 2
**Diseño**
Diseñar arquitectura del proyecto antes de escribir código

## Fase 3
**Conbstruccióin del dataset**

Se debe analizar:
* iluminación
* distintas distancias
* distintos ángulos
* pallets completos
* pallets incompletos
* distintos SKU's
* distintos racks
* distinos niveles de ocupación

## Fase 4
**entrenamiento**

El modelo puede entrenarse con YOLO

## Fase 5
**Evaluación**

Métricas:
* Precision
* Recall
* F1
* mAP

Medición a nivel de empresa
* ¿Cúantos pallets completos identifica correctamente?
* ¿Cuántos pallets incompletos identifica correctamente?
* ¿Cuál es el error medio en la estimación del inventario?

## Fase 6
**Demostración**

Flujo completo del proyecto

```
      Foto
       ↓
    Detección
       ↓
     Conteo
       ↓
    Estimación
       ↓
Comparación con inventario
       ↓
    Alerta
```

