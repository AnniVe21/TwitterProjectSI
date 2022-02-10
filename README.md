# TWEEPY API (Tendencias Colombia) 
Data scrapping with twitter (API TWEEPY) about hashtag trending in Colombia.<br>

## Introducción 
El uso de las redes sociales ha ido evolucionando a medida que nos vamos adaptando a los medios tecnológicos en la cotidianidad, por esto actualmente se han convertido en el medio de comunicación más usado a nivel global. Desde hace un par de años se han estado creando distintas redes sociales que responden a las necesidades e intereses de las cadenas de prensa e incluso de distintos usuarios. En este caso, nos enfocaremos en Twitter la cual es una plataforma digital que permite compartir contenido en textos cortos e incluso se puede agregar material audiovisual. Es una red que facilita el intercambio de información de diversos temas y la interacción entre miles de usuarios de todas partes del mundo, y en este caso unos más influyentes que otros. Esta influencia se viene midiendo en la cantidad de seguidores, tweets que son replicados por otros usuarios y la interacción que tienen con estas cuentas. Los anteriores elementos son propios de la red social con los cuales se pueden extraer datos de distintas cuentas y hacer análisis sobre las dinámicas de esta. Como es bien sabido, Twitter se ha vuelto una herramienta de marketing, negocios e incluso como generador de polémicas y discusiones de interés, y es por esto que en este proyecto se quieren analizar las dinámicas que diariamente las cuentas de periodismo de Colombia tienen para generar visualizaciones, imponer temas que sean tendencia e incluso ganar más seguidores.

Para este análisis, se utilizarán las cuentas más influyentes de Colombia que han sido seleccionadas en un estudio realizado por la plataforma Quantico. Las 30 cuentas por analizar hacen parte de las categorías: Noticias, Radio y Periodismo. Con el fin de tener resultados certeros sobre cómo se mueven las noticias a lo largo y ancho del país y si son estas cuentas quienes más influencia tienen en los resultados para los usuarios de este territorio geográfico. Además, se consolidarán los resultados del análisis en una aplicación en la cual se puedan visualizar los datos a partir del software Tableau.

## Objetivos
#### General:
* Analizar las dinámicas de las cuentas de prensa más influyentes en Colombia.
#### Específicos:
* Extraer información a partir de una API creada en esta red social.
* Evidenciar los resultados graficamente desde la plataforma Tableau con interpretaciones lógicas.
* Realizar análisis de lenguaje natural y relevar las temáticas más relevantes en la plataforma.


## Red social
#### Twitter

## Hashtags más utilizados
<img src="https://github.com/AnniVe21/TwitterProjectSI/blob/main/WordCloud%20hashtag.png" width="48">
![alt text](https://github.com/AnniVe21/TwitterProjectSI/blob/main/WordCloud%20hashtag.png)
 #laesperanzaempiezaenelsenado
37 #lomásleído
28 #oigolafm
26 #felizviernes
26 #noticiasuno|
24 #pelaezdefranciscoenlaw
20 #vocesysonidos
20 #lagranencuesta
19 #elpaísenvivo
18 #suciocomochar
18 #losdanieles
16 #laesperanzaempiezaenelsenado
16 #elreportecoronell
16 #deportes
16 #borrachonovale
16 #chariluminado
15 #mañanasblu
12 #animedel1
12 #raspandolaolla
12 #estoescambio
12 #códigocaracol

## Análisis de lenguaje natural

# Embedding:
word2vec 2D plot
![alt text](https://github.com/AnniVe21/TwitterProjectSI/blob/main/2D%20word2Vec%20Tweets.png)
word2vec 3D plot
![alt text](https://github.com/AnniVe21/TwitterProjectSI/blob/main/3D%20Word2Vec%20Tweets.png)
## Visualización de datos (Tableau)
* TEMAS
https://public.tableau.com/views/Palabras_16444586883680/Palabras?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link
* LIKES DE TWEETS POR USUARIO
https://public.tableau.com/views/Tweets-likes/likes-tweets?:language=es-ES&:display_count=n&:origin=viz_share_link
* TWEETS Y RETWEETS POR USUARIO 
https://public.tableau.com/views/TweetsyRetweets/Dashboard3?:language=es-ES&:display_count=n&:origin=viz_share_link
* ANALISIS DE SENTIMIENTO 
https://public.tableau.com/views/Tweets_16444448010910/Sentimiento?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link
