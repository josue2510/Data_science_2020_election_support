# Nivel de apoyo a los candidatos en las elecciones de USA  2020, según los tweets

## Abstract

El objetivo del presente proyecto es determinar el grado de apoyo que obtuvieron los candidatos a la presidencia de Estados Unidos con relación a los tweets para las elecciones del 3 de noviembre de 2020.
Para ello, se realizará unsupervised learning de 3 clusters, para encontrar el número de tweets neutros y tweets que apoyan a los candidatos republicanos (Joe Biden) y conservadores (Donald Trump).
Además de ver estadísticamente las palabras más utilizadas y frecuentes de los tweets, para analizar que tweets son considerados neutros.
Una vez realizado el clustering con DBSCAN, se procederá a sacar un sampling con muestras aleatorias del 10% del total de tweets para realizar el sentimental analysis que califique a los tweets como positivos, negativos y neutros.
Para ello, se hará uso de tres datasets, los cuales tendrán información de los tweets previos del día de la eleccion. Por lo tanto, la motivacion, es poder ver los datos para predecir al ganador de las elecciones de Estados Unidos del 2020.

# Research questions
A list of research questions you would like to address during the project. 

- ¿Cómo son percibidos los tweets para cada uno de los partidos políticos?

- ¿Segun los tweets, cual fue el candidato que obtuvo más apoyo?

- ¿Cuáles fueron las palabras que se usaron con mayor frecuencia en los tweets?

# Dataset

![elec](https://c.tenor.com/-TPrzN8pfJQAAAAM/good-twitter.gif)

1.  [US Election 2020 Tweets](https://www.kaggle.com/manchunhui/us-election-2020-tweets) (865 MB)
1.  [2020 US election Tweets](https://www.kaggle.com/sripaadsrinivasan/tweets-about-the-upcoming-us-electionaugtooct?select=us_election-edit.csv) (272 MB)
1.  [2020 US election Tweets - Unlabeled](https://www.kaggle.com/bauyrjanj/2020-us-election-tweets-unlabeled) (3 GB)

Primero limpiar los datos, eliminando los signos de puntuación y caracteres especiales, para obtener solamente los datos previos a las elecciones del 3 de noviembre de 2020, luego realizar un procesamiento de texto de cada tweet.
Descartaremos todas las columnas que no tengan relacion con los tweets, likes, pais, ciudad y fecha.


# A list of internal milestones up until project milestone 2

Para el segundo milestone, se plantea realizar la adquisición y procesamiento de datos.

# Questions you need help with 

- ¿Es correcto mezclar los tres datasets para procesarlos como uno solo?

- ¿El preprocesamiento de los datos es suficiente?

- ¿Que tanta certeza se puede tener de los tweets?
