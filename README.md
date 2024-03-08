# Fake News detection using BERT
In this project, I analyze a Kaggle dataset containing over 70,000 records of news classified as either false or true. The goal is to train a Machine Learning model that accurately predicts the category of each news item. The result is very positive: using Google's BERT language model, we achieve an accuracy of 99%. The process is divided into the following phases, separated into different notebooks:
1. Exploratory Data Analysis: We analyze the polarity and sentiment of the news whether they are false or not, finding certain bias in fake news. Additionally, we remove useless data such as news without text.
2. Machine Learning model training with scikit-learn: We vectorize our dataframe and convert it into a sparse matrix. Then, we apply a dimensionality reduction technique and obtain our training and validation sets. Finally, we train several models seeking their best parameters, achieving an accuracy of 90% in the RandomForestClassifier.
3. BERT model training: Using various versions of BERT varying in size and supported character count, we define functions to train them and achieve accuracies above 98% in several of them.
4. Comparison of BERT models: Using Pandas, we create a dataframe that compares the results of all models. As expected, the best one is the model with the highest parameter input, achieving an accuracy of 99.1%.



# Detección de noticias falsas usando BERT
En este proyecto analizo un conjunto de datos de Kaggle que contiene sobre 70000 registros de noticias clasificadas según sean falsas o verdaderas. El objetivo es entrenar un modelo de Machine Learning que consiga predecir con exactitud la categoría de cada noticia. El resultado es muy positivo: utilizando el modelo del lenguaje BERT de Google, conseguimos una precisión del 99%. El proceso se divide en las siguientes fases, separadas en diferentes _notebooks_:

1. Análisis explotatorio de los datos: analizamos la polaridad y sentimentalismo de las noticias según sean falsas o no, encontrando cierto sesgo en las noticias falsas. Además, eliminamos datos inservibles como noticias sin texto.
2. Entrenamiento de modelos de Machine Learning con scikit-learn: vectorizamos nuestro dataframe y lo pasamos a una matriz dispersa. Después aplicamos una técnica de reducción de dimensionalidad y obtenemos nuestro conjunto de entrenamiento y comprobación. Por último, entrenamos varios modelos buscando sus mejores parámetros, obteniendo una precisión del 90% en el RandomForestClassifier.
3. Entrenamiento de modelos BERT: utilizando varias versiones de BERT que varían en tamaño y cantidad de caracteres admitidos, definimos funciones que los entrenen y conseguimos precisiones por encima del 98% en varios de ellos.
4. Comparación de los modelos BERT: mediante Pandas, creamos un _dataframe_ que compare los resultados de todos los modelos. Como era de esperar, el mejor es el que mayor entrada de parámetros tiene, y consigue una precisión del 99,1%.
