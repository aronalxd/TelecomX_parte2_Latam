# 📊 Telecom X - Modelo Predictivo de Cancelación de Clientes

## 🎯 Objetivo del Proyecto

Desarrollar un modelo de Machine Learning capaz de predecir qué clientes
tienen mayor probabilidad de cancelar sus servicios (churn), permitiendo
implementar estrategias de retención basadas en datos.

------------------------------------------------------------------------

## 📁 Estructura del Proyecto

-   `datos_tratados.csv` → Dataset limpio y preparado para modelado\
-   `Informe_Ejecutivo_Telecom_X_Direccion.docx` → Informe ejecutivo
    final\
-   `README.md` → Documentación del proyecto

------------------------------------------------------------------------

## 🔎 Descripción del Problema

Telecom X presenta una tasa de cancelación del **26.5%**, lo que
representa una oportunidad estratégica para reducir pérdidas y aumentar
el valor de vida del cliente (LTV).

El objetivo es anticipar la cancelación utilizando modelos de
clasificación supervisada.

------------------------------------------------------------------------

## ⚙️ Metodología

1.  Limpieza y transformación de datos\
2.  Codificación de variables categóricas (One-Hot Encoding)\
3.  División de datos (80% entrenamiento / 20% prueba)\
4.  Entrenamiento de modelos:
    -   Regresión Logística
    -   SVM (lineal)
    -   KNN
    -   Random Forest
5.  Evaluación con métricas:
    -   Accuracy
    -   Precision
    -   Recall
    -   F1-score
    -   Matriz de confusión
6.  Análisis de importancia de variables

------------------------------------------------------------------------

## 🏆 Resultados

El modelo recomendado es **Regresión Logística**, debido a:

-   Mejor equilibrio general (F1-score)
-   Alta capacidad de detección de clientes en riesgo
-   Mayor interpretabilidad para toma de decisiones

------------------------------------------------------------------------

## 🔑 Principales Factores de Cancelación

### Factores de Riesgo

-   Contrato mensual
-   Baja antigüedad (tenure)
-   Servicio de fibra óptica
-   Pago mediante Electronic Check
-   Cargos mensuales elevados

### Factores Protectores

-   Contratos de 1 o 2 años
-   Mayor permanencia
-   Clientes con dependientes
-   Mayor gasto acumulado

------------------------------------------------------------------------

## 💡 Recomendaciones Estratégicas

-   Implementar sistema de scoring mensual
-   Enfocar retención en el top 15% de clientes en riesgo
-   Incentivar migración a contratos de largo plazo
-   Optimizar soporte técnico en clientes con fibra

------------------------------------------------------------------------

## 🚀 Impacto Esperado

-   Reducción de tasa de cancelación
-   Incremento del LTV
-   Optimización del presupuesto de retención
-   Mejora en la toma de decisiones basada en datos

------------------------------------------------------------------------

## 👨‍💻 Autor

Proyecto desarrollado como parte del análisis de Machine Learning
aplicado a churn prediction en Telecom X.
