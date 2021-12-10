# Nivel de apoyo a los candidatos en las elecciones de USA  2020, según los tweets

-Carla Barrientos
-Josue Cardozo
-Andrea Villarroel

## Abstract

El objetivo del presente proyecto es determinar el grado de apoyo que obtuvieron los candidatos a la presidencia de Estados Unidos con relación a los tweets para las elecciones del 3 de noviembre de 2020. Para ello, se realizará unsupervised learning  con la finalidad de poder encontrar cuáles fueron las tendencias de los diferentes tweets, si apoyaban a los candidatos republicanos (Joe Biden) o a los conservadores (Donald Trump) y qué factores influían en su posición. Una vez realizado el clustering con DBSCAN, se procederá a sacar un sampling con muestras aleatorias del top 50 del total de tweets ordenados por el número de likes y retweets para realizar el sentimental analysis que nos ayude a identificar cuáles fueron las palabras más frecuentes que hicieron que los tweets sean más virales. Para ello, se hará uso de tres datasets, los cuales tendrán información de los tweets previos del día de la elección.

## Research questions

- ¿Cómo son percibidos los tweets para cada uno de los partidos políticos?

- ¿Segun los tweets, cual fue el candidato que obtuvo más apoyo?

- ¿Cuáles fueron las palabras que se usaron con mayor frecuencia en los tweets?

- ¿Qué palabras tienen los tweets mas virales y Cuales son los sentimientos que transmiten?

## Dataset

![elec](https://c.tenor.com/-TPrzN8pfJQAAAAM/good-twitter.gif)

1.  [US Election 2020 Tweets](https://www.kaggle.com/manchunhui/us-election-2020-tweets) (865 MB)
1.  [2020 US election Tweets](https://www.kaggle.com/sripaadsrinivasan/tweets-about-the-upcoming-us-electionaugtooct?select=us_election-edit.csv) (272 MB)
1.  [2020 US election Tweets - Unlabeled](https://www.kaggle.com/bauyrjanj/2020-us-election-tweets-unlabeled) (3 GB)

Primero limpiar los datos, eliminando los signos de puntuación y caracteres especiales, para obtener solamente los datos previos a las elecciones del 3 de noviembre de 2020, luego realizar un procesamiento de texto de cada tweet.
Descartaremos todas las columnas que no tengan relacion con los tweets, likes, pais, ciudad, retweets y fecha.


## A list of internal milestones up until project milestone 2

Para el segundo milestone, se plantea realizar la adquisición y procesamiento de datos.

## Questions you need help with 

- ¿Es correcto mezclar los tres datasets para procesarlos como uno solo?

- ¿El preprocesamiento de los datos es suficiente?

- ¿Que tanta certeza se puede tener de los tweets?
