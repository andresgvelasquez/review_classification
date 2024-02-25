# Film Junky Union ¿Reseñas positivas o negativas?

## Descripción
Film Junky Union, una nueva comunidad vanguardista para los aficionados de las películas clásicas, está desarrollando un sistema para filtrar y categorizar reseñas de películas. Tu objetivo es entrenar un modelo para detectar las críticas negativas de forma automática. Para lograrlo, utilizarás un conjunto de datos de reseñas de películas de IMDB con leyendas de polaridad para construir un modelo para clasificar las reseñas positivas y negativas. Este deberá alcanzar un valor F1 de al menos 0.85

## Dependencias
matplotlib
nltk
numpy
pandas
seaborn
sklearn
lightgbm import LGBMClassifier
nltk
tqdm
spacy

## Plan de trabajo
- Se realiza un EDA de las reviews.
- Se define la función de evaluación, la cual tomara F1, ROC Y PRC como métricas.
- El texto se normaliza, es decir se transforma en minúsculas y solo letras y apostrofes.
- Se divide el conjunto en entrenamiento y prueba.
- Se prueban distintos modelos (uno dummy), Regresión lineal (con nltk y con spacy), con LGBMClassifier.