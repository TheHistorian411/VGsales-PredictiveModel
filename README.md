# VGsales-PredictiveModel
Description: Video game sales predictive model that uses a data set of 16,000+ entries of games including their genre, publisher, platform, etc, as well as their sales in different regions and globally. The "GradientBoostingRegressor" model was used.

Conclusions: Overall, across different inputs of genres; publishers and platforms, there was no strong correlation between these factors and the games' global sales. The model had a mean absolute error of ~50% across over 100 tests, and was only about ~15% better at predicting results than simply taking an average of the total data set according to the R^2 test. Other regressive models were used, such as tree and linear models, however they had similar if not significantly worse prediction results than the gradient boosting regressor. Because of such high inaccuracy, the specific results of the model's predictions will not be discussed or mentioned.

Despite the fact that the predictive model is often inaccurate in its predictions for video games and their sales, there are still meaningful conclusions that can be drawn. We can conclude that a video game(s)'s success, in terms of global sales, cannot be reliably drawn from its context of genre, publisher, and platform. However, this does not mean that we cannot predict a video game's sales at all. For one, the dataset I pulled may not represent all aspects and features that determine a video game's success, such as review scores, graded qualities (like graphics, sound, gameplay...), and type of game (Like a live service  game, or a single-player story game; Independent of the video game's genre). There are likely many more factors that I have not mentioned nor could be easily quantified. Should data like this be accurately collected and documented into this data set, results for a predictive model could be different.

To recap, video games’ success, measured in sales, cannot be accurately predicted using a predictive model using data such as "genre," "publisher," and "platform." This most likely means that there are other factors or features that have a greater effect on a game's success. Future steps forward in a project like this would be to broaden data types that are collected about video games and recompile them into a new data set, excluding the aforementioned ones. Training a new model and reading its predictions should at least provide more insight into predicting video game sales, but hopefully enable accurate predictions all together.

I will not continue this project any further for now because the future steps mentioned above are far beyond my current bandwidth and availability of time.

-  Magnus Vournas, "TheHistorian411"

  Important supplemental notes:
Open-source Python Libraries used: Pandas, SkLearn, & NumPy.
Dataset Source: https://www.kaggle.com/datasets/gregorut/videogamesales/data
Programmed on Jupyter Notebook

