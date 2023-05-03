# Newspapers-comparison

## About the project

The goal of this project was to perform a **comparison between two Spanish journals with an opposite ideological line**, _Público_ and _La Razón_, through Natural Language Processing and Text Mining techniques, in order to discern the main differences in terms of language usage. Our primary hypothesis was based on the notion that the left-right division clearly influences the way articles are written, as well as the political context: therefore, we expected _La Razón_ to display a more critic and more negative language than _Público_, as the last years have been marked by a left-wing government.

Regarding the **results**, by analyzing word frequencies and bigrams, performing Sentiment Analysis and TF-IDF, we were able to conclude that the proportion of articles with an overall negative lexicon is almost 20% higher on news from _La Razón_ and that the pandemic was a very important point from where the conservative publication made emphasis when critizing the government's legislative and executive measures. Additionally, we found that _La Razón_ tends to mention leftist political leaders more often and that _Público_ sets the scope regarding economic articles in the global and transnational level, while the former does it on a local basis (hostelry and small businesses, mainly). 

Further approaches could use more journals to answer the hypothesis and using other set of techniques, such as correlation analysis, Topic Modelling or Supervised Machine Learning to classify news as critic or not. 

## Used data and requirements

All data used was collected from public sources, through a dataset offered by Muñiz Peña (2021) in [Kaggle](https://www.kaggle.com/datasets/josemamuiz/noticias-laraznpblico). This dataset contains a total of 58424 articles from _La Razón_ (31477) and _Público_ (26948). Due to the large file size, it was not included on the repository, so it's necessary to download it and place it correctly in the Project's folder in order for the code to run properly. 
