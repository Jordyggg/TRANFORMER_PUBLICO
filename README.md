# CMAPPSTURBOFANUSFQML


Predicción de la Vida Útil Remanente (VRR) de Motores Turbofán Basada en Ciencia de Datos y Aprendizaje Automático.

Este estudio aborda la predicción de la Vida Útil Remanente (VRR) de motores de turbofán de aeronaves utilizando el conjunto de datos C-MAPSS, con el objetivo de contribuir al mantenimiento predictivo en sistemas críticos. Se implementa un flujo de trabajo en dos fases: una etapa inicial con modelos de referencia (Ridge, Random Forest, XGBoost) y una etapa avanzada con redes neuronales profundas (LSTM y Transformers). Se propone una arquitectura basada en Transformers con atención a los sensores. El modelo propuesto captura dinámicas complejas y relaciones multivariables entre sensores a lo largo del tiempo, mejorando la interpretabilidad y la precisión de la predicción. Los resultados se compararon con modelos tradicionales y arquitecturas profundas previamente reportadas en el estado del arte, logrando mejores métricas de rendimiento (RMSE y R²) incluso en comparación con diseños más complejos. Estos hallazgos refuerzan el potencial de los Transformers como herramientas efectivas y escalables para el mantenimiento predictivo y el análisis de series temporales en aplicaciones industriales.

Este proyecto consta de seis archivos de cuaderno que registran todos los experimentos realizados, en el siguiente orden:

This project consists of six notebook files that record all the experiments performed, in the following order:

1.Predicting_Remaining_Useful_Life(RUL).ipynb (EDA)

2.PREDICTION_RUL_RidgeLR.ipynb

3.PREDICTION_RUL_Random_Forest cliprul.ipynb

4.PREDICTION_RUL_XGBOOST.ipynb

5.LSTM.ipynb

6.SETRANSFORMER.ipynb
