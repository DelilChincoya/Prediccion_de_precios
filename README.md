# Predicción de Precios de Casas

En este proyecto se desarrolló un modelo predictivo para estimar precios de casas con base en diversas características de las propiedades. Se utilizaron técnicas de análisis de datos, visualización y aprendizaje automático para predecir el valor de las propiedades.

## Conjunto de Datos
El conjunto de datos utilizado está disponible en [Kaggle: House Prices - Advanced Regression Techniques.](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data) Contiene información de propiedades inmobiliarias, con un total de 79 variables predictoras que reflejan diferentes aspectos, tales como:

**Métricas de calidad:** Materiales de construcción, acabados interiores, estado general de la casa.  
**Áreas:** Tamaño de los lotes, tamaño del garage.  
**Características de las propiedades:** Número de habitaciones, tipo de vivienda.  
**Antigüedad:** Año de construcción, renovaciones.

## Objetivo
El propósito del proyecto es construir un modelo de aprendizaje automático que prediga los precios de casas, lo cual puede ser útil para:

Determinar el valor estimado de propiedades.
Asistir en la toma de decisiones para inversiones inmobiliarias.
Explorar factores clave que afectan los precios de las propiedades.

## Metodología
**Análisis exploratorio y preprocesamiento de datos:**  
1. Exploración inicial para detectar valores atípicos y datos faltantes.
2. Visualización de variables clave utilizando histogramas, gráficos de dispersión y mapas de calor de correlación.
3. Codificación de variables categóricas.
4. Imputación de datos faltantes.
5. Transformación logarítmica y escalado de variables.

**Algoritmos de regresión utilizados:**  
1. ElasticNet
2. Árboles de decisión
3. Random Forest
4. XGBoost

**Evaluación:**  
Comparación del desempeño de los modelos mediante las metricas RMSE (Root Mean Squared Error) y R² (Coeficiente de determinación)

## Resultados
El modelo de XGBoost obtuvo el mejor desempeño, con un RMSE más bajo y una mayor capacidad de predicción en comparación con otros modelos. 

Las variables clave en la determinación del precio están relacionadas con la calidad de la propiedad, el espacio habitable y las funcionalidades adicionales. En particular, para el modelo XGBoost`las cinco variables más importantes fueron:

1. Calidad de los acabados exteriores.
2. Número de baños completos.
3. Número de carros que caben en el garage.
4. Calidad general de la propiedad.
5. La presencia o ausencia de aire acondicionado central. 
