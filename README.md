# Covid-19Thailand

I trained models to predict future Covid-19 cases in Thailand, using machine learning and deep neural networks -- both univariate and multivariate. For the univariate, the predictor was either confirmed cases or confirmed deaths.
I set inputs to be the previous 14-days data. For the multivariate, besides the Covid-19 cases, I used Google and Apple mobilities as additional predictors. 

The main files of the predictions are ML univariate cases + deaths, ML multivariate cases + deaths, DNN univariate cases + deaths, DNN multivariate cases, DNN multivariate deaths

The predicting files were to see how variables besides confirmed cases and confirmed deaths can predict the Covid-19 cases. Only features with accurate predictions were used in the multivaraite DNNs.

The Covid_python files were experimented of having other variables predicting future values of themselves. This information was later used in DNN_multivariate files.
