# MachineLearning_price_prediction

# Predicción de precios de Airbnb

## Descripción

Este proyecto tiene como objetivo predecir los precios de los alojamientos de Airbnb utilizando técnicas de Machine Learning. Se exploran diferentes modelos, incluyendo XGBoost, Random Forest y LightGBM, para encontrar el que mejor se ajuste a los datos.

## Datos

Los datos utilizados provienen de un dataset público de Airbnb. Se realiza un preprocesamiento exhaustivo de los datos, incluyendo:

- Limpieza de datos.
- Ingeniería de características.
- Codificación de variables categóricas.
- Análisis de texto con NLP.

## Modelo

Se entrena un modelo XGBoost con hiperparámetros optimizados. Además, se experimenta con otros modelos como Random Forest y LightGBM. Finalmente, se crea un modelo ensemble que combina las predicciones de los diferentes modelos para mejorar la precisión.

## Resultados

El modelo final logra un error absoluto medio (MAE) de 4.07, lo que indica una buena capacidad predictiva. Se analizan los errores del modelo para identificar posibles mejoras.

## Uso

Para ejecutar el proyecto, sigue estos pasos:

1. Clona el repositorio: `git clone <URL del repositorio>`
2. Instala las dependencias: `pip install -r requirements.txt`
3. Ejecuta el notebook de Colab: `airbnb_price_prediction.ipynb`

## Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún error o tienes alguna sugerencia, por favor crea un issue o un pull request.

## Autor

**Fernando Beneytez**

