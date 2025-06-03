# Evaluación de Modelos Supervisados – Dataset de Parkinson

Este proyecto compara varios modelos de aprendizaje supervisado aplicados al diagnóstico de Parkinson a partir de características acústicas.



##  Modelos Evaluados

- Regresión Logística
- Random Forest
- Multi-layer Perceptron (MLP)
- XGBoost

Se evaluaron utilizando validación cruzada y métricas como accuracy, precision, recall y F1-score.



##  Resultados

Se graficaron:
- Curvas ROC
- Comparativas de métricas por modelo
- Matrices de confusión

Disponibles en `./results/`


##  Dataset

El dataset se compone de grabaciones de voz con diversas características numéricas y una variable binaria `status` que indica la presencia o no de Parkinson.


##  Cómo ejecutar

```bash
pip install -r requirements.txt
```

Luego abrir y ejecutar `parkinson-learning-models.ipynb`.



##  Nota

Este proyecto se realizó con fines educativos de análisis comparativo en aprendizaje supervisado.
