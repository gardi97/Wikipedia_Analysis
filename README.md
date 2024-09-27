# Wikipedia Analysis with Pyspark

## Intoduction
The aim of this project was to analyze the content of Wikepia and to train a model to classify articles in 15 categories. Considering the great amount of data, this project was implemented on Databricks using Pyspark to parallelise computation.

## Project workflow
- EDA of Wikipedia dataset
- Training of two models (Naive-Bayes), one using the entire article and one using only the summary
- Evualuation and comparison of the models

## Conclusions
In this project the content of Wikipedia was analysed using Pyspark on Databricks. Moreover, two models using the entire articles and only the summary respectively were trained and evaluated. Both models showed good performances, being similar in terms of F1-score on the Test Set (0.86). Hyperparameters optimization was conducted on the model train with the summary resulting in a slight in the F1-score obtained on Test Set (0.87).

## Contributors
[Francesco Gardini](https://github.com/gardi97)
