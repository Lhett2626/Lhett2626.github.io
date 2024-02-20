# Lhett2626.github.io <br>
A portfolio showing my data science capabilities. This repository is designed to demonstrate my capabilities as a data Scientist. <br>

Predicting Bicycle Traffic <br>
<br>
This project uses <a href="https://www.ncdc.noaa.gov/cdo-web/search"> NOAA weather data </a> and <a href="https://data.seattle.gov"> Seattle public data </a>. The goal is to predict Fremont Bridge, Seattle, Washington bike traffic using weather, holiday, day of week, and seasonality independent variables. The project data was aquired through the Seattle public data and NOAA weather API. <br>

A pipeline is used to encode categorical and scale continous variable during the feature cleaning process. A ridge regression (L2 regularization) was trained on a training sample date before 2020. The model preformed well on the testing data taken before 2020. However, the model did not perform well on the post covid test set suggesting the model may not be sufficient for predicting bike traffic in a Covid-less world. The model was used to predict bike traffic during the 2020 year impacted by covid with an understanding of the models limitations.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Predicting%20Bicycle%20Traffic.ipynb"> Predicting Bicycle Traffic </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Predicting%20Bicycle%20Traffic.ipynb" target="_blank"> Predicting Bicycle Traffic </a>

Kenpom NCAA Basketball Predicter <br>

Kenpom college basketball statistics is aquired using webscraping and uses it to predict college basketball games. Kenpom has updated its website and this code will not work anymore. To update this project, I would have to use a package such as selenium or playwright to parse Kenpom's updated webpage. <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Kenpom_Scraper.ipynb"> Kenpom NCAA Basketball Predicter </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Kenpom_Scraper.ipynb" target="_blank"> Kenpom NCAA Basketball Predicter NB </a>

Yelp and Google Reviews <br>

Google and Yelp review date was used to train a niave bayes model to predict a star rating above or below 3. The review data was aquired through Google and Yelps respective APIs. The countvectorizer was used to transform the data. The model was 84% accurate on predicting reviews rating from the review text.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Review%20Project/Google_reviews.ipynb"> Google Reviews </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Review%20Project/Google_reviews.ipynb" target="_blank"> Google Reviews NB </a> <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Review%20Project/Yelp_API.ipynb"> Yelp Reviews </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Review%20Project/Yelp_API.ipynb" target="_blank"> Yelp Reviews NB </a> <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Review%20Project/Analyze.ipynb"> Analyze </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Review%20Project/Analyze.ipynb" target="_blank"> Analyze NB </a> <br>

Email spam detector <br>

This project uses email bodies with a spam/not spam indicator to train a niave bayes model and a logistic regression model. A countvectorizer is used to transform the data into matrix of token counts. The matrix is used to train the dataset and test the datasets results. The niave bayes model had a accuracy rate of 97%. The niave bayes model outperformed the logistic regression model regression model which only had a 96% accuracy rate.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Building%20s%20SMS%20spam%20detector.ipynb"> Email spam detector </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Building%20s%20SMS%20spam%20detector.ipynb" target="_blank"> Email spam detector NB </a>

Customer Churn Rate <br>

A random forest classification model and a extreme gradient boost classification model are used to predict whether a customer churned or not. The random forest classification model had a slightly better preformance.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Churn_Risk.ipynb"> Customer Churn Rate </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Building%20s%20SMS%20spam%20detector.ipynb" target="_blank"> Customer Churn Rate NB </a>

Credit scoring (Non-payment) <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Credit_Score.ipynb"> Credit scoring (Non-payment) </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Credit_Score.ipynb" target="_blank"> Credit scoring (Non-payment) NB </a>

Diabetes Prediction <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Forest_Cover_Classification.ipynb"> Diabetes Prediction </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Diabetes%20Prediction.ipynb" target="_blank"> Diabetes Prediction NB </a>

Forest cover <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Diabetes%20Prediction.ipynb"> Forest cover </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Forest_Cover_Classification.ipynb" target="_blank"> Forest cover NB </a>

Metro Interstate Traffic Volume <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Metro%20Traffic.ipynb"> Metro Interstate Traffic Volume </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Metro%20Traffic.ipynb" target="_blank"> Metro Interstate Traffic Volume NB </a>

Predicting Heart Failure <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Predicting%20Heart%20Failure.ipynb"> Predicting Heart Failure </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Predicting%20Heart%20Failure.ipynb" target="_blank"> Predicting Heart Failure NB </a>

Titanic Classification <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Sale%20prediction.ipynb"> Titanic Classification </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Sale%20prediction.ipynb" target="_blank"> Titanic Classification NB </a>

NYC Temp V Energy <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/NYC%20Temp%20V%20Energy.ipynb"> NYC Temp V Energy </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/NYC%20Temp%20V%20Energy.ipynb" target="_blank"> NYC Temp V Energy NB </a>

NYC Weather V Energy <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/NYC%20Weather%20V%20Energy.ipynb"> NYC Weather V Energy </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/NYC%20Weather%20V%20Energy.ipynb" target="_blank"> NYC Weather V Energy NB </a>

News prediction <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/News%20prediction.ipynb"> News prediction </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/News%20prediction.ipynb" target="_blank"> News prediction NB </a>

Bird Baths <br>

This projects goal is to predict which birds are more likely to be seen in an urban enviroment or a rural enviroment. The independent variables urban_rural, bird_type and bioregions were used to predict birds perfered habitat. A logistic regression and Extreme Gradient Boost classification model's performance were compared. Ultimately, the XGB classification model preformed better.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Bird%20Baths.ipynb"> Bird Baths </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Bird%20Baths.ipynb" target="_blank"> Bird Baths NB </a>

Craiglist Car Search <br>

This project shows my ability to scrape webpages and aquire data. For this project, I scraped craiglist for used car information and created a tabular dataset of car data.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Craiglist%20Scraper.ipynb"> Google Reviews </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Craiglist%20Scraper.ipynb" target="_blank"> Google Reviews NB </a> <br>

Spelling Bee Solver <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Spelling_Bee_Solver.ipynb"> Spelling Bee Solver </a> <br>
<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Spelling_Bee_Solver.ipynb" target="_blank"> Spelling Bee Solver NB </a>











