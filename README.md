# Actividad 5 - Gestión de Proyectos de Inteligencia Artificial

## Predicción de Riesgo de Clientes

Este proyecto desarrolla una solución de Machine Learning orientada a la clasificación del nivel de riesgo de clientes dentro de un escenario de gestión de cartera financiera. El objetivo es identificar patrones relacionados con comportamiento de pago, atrasos, disputas y comunicación con clientes para apoyar la toma de decisiones en procesos de cobranza.

El dataset utilizado fue generado mediante IA generativa con información simulada de reportes financieros históricos. Se trabajó con variables como monto de factura, días de atraso, historial de pago, frecuencia de disputas, sentimiento de correos y nivel de riesgo.

Para la solución se implementaron dos modelos de clasificación:
- Logistic Regression.
- Random Forest.

Los modelos fueron entrenados, evaluados y comparados utilizando métricas de clasificación como Accuracy, Precision, Recall, F1-score y ROC-AUC. Además, se aplicó validación cruzada y ajuste de hiperparámetros mediante Grid Search.

El seguimiento de experimentos se realizó mediante MLflow, registrando parámetros, métricas y modelos entrenados para mantener trazabilidad del proceso de Machine Learning.

El repositorio contiene los datos utilizados, notebooks y scripts necesarios para reproducir el entrenamiento y evaluación del proyecto.
