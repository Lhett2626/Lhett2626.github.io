# Liam Hettinger's Data Science Portfolio <br>
A portfolio showing my data science capabilities. This repository is designed to demonstrate my capabilities as a data Scientist. <br>

<b> NCAA Basketball Prediction Model </b> <br>

The project's goal is to determine if a statistical model is better than intuition at predicting NCAA Division 1 Basketball March Madness scores. Before each round of the 2022 March Madness tournament, I intuitively guessed March Madness team scores using my previous basketball knowledge. The intuitive predictions were then compared to a statistical model to determine accuracy. <br>

The statistical model used was a light gradient boosted model. The features included historical averages of advanced and basic box score statistics for the given team, the given team's opponent, and the given team's previous opponents. The model was trained on NCAA Division 1 regular season and post-season data from 2015 to 2022, excluding the 2022 post-season tournament.<br>

Ultimately, the light gradient boosted model outperformed my intuition. My intuition's mean absolute percentage error was 18.95 percent. The mean absolute error for the light gradient boosted model was 14.9 percent. The model predicted games with over 5 percent greater accuracy. <br>

<a href="https://github.com/Lhett2626/Capstone/tree/main"> GitHub Repository </a>

<a href="https://github.com/Lhett2626/Capstone/blob/main/Liam%20Hettinger%20Capstone%20Final.pdf"> PDF writing </a>

<b> Predicting Bicycle Traffic </b> <br>
<br>
This project uses <a href="https://www.ncdc.noaa.gov/cdo-web/search"> NOAA weather data </a> and <a href="https://data.seattle.gov"> Seattle public data </a>. The goal is to predict Fremont Bridge, Seattle, Washington bike traffic using weather, holiday, day of week, and seasonality independent variables. The project data was aquired through the Seattle public data and NOAA weather API. <br>

A pipeline is used to encode categorical and scale continous variable during the feature cleaning process. A ridge regression (L2 regularization) was trained on a training sample date before 2020. The model preformed well on the testing data taken before 2020. However, the model did not perform well on the post covid test set suggesting the model may not be sufficient for predicting bike traffic in a Covid-less world. The model was used to predict bike traffic during the 2020 year impacted by covid with an understanding of the models limitations.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Predicting%20Bicycle%20Traffic.ipynb"> Predicting Bicycle Traffic </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Predicting%20Bicycle%20Traffic.ipynb" target="_blank"> Predicting Bicycle Traffic </a>

<b> Kenpom NCAA Basketball Predicter </b> <br>

Kenpom college basketball statistics is aquired using webscraping and uses it to predict college basketball games. Kenpom has updated its website and this code will not work anymore. To update this project, I would have to use a package such as selenium or playwright to parse Kenpom's updated webpage. <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Kenpom_Scraper.ipynb"> Kenpom NCAA Basketball Predicter </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Kenpom_Scraper.ipynb" target="_blank"> Kenpom NCAA Basketball Predicter NB </a>

<b> Yelp and Google Reviews </b> <br>

Google and Yelp review date was used to train a niave bayes model to predict a star rating above or below 3. The review data was aquired through Google and Yelps respective APIs. The countvectorizer was used to transform the data. The model was 84% accurate on predicting reviews rating from the review text.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Review%20Project/Google_reviews.ipynb"> Google Reviews </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Review%20Project/Google_reviews.ipynb" target="_blank"> Google Reviews NB </a> <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Review%20Project/Yelp_API.ipynb"> Yelp Reviews </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Review%20Project/Yelp_API.ipynb" target="_blank"> Yelp Reviews NB </a> <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Review%20Project/Analyze.ipynb"> Analyze </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Review%20Project/Analyze.ipynb" target="_blank"> Analyze NB </a> <br>

<b> Email spam detector </b> <br>

This project uses email bodies with a spam/not spam indicator to train a niave bayes model and a logistic regression model. A countvectorizer is used to transform the data into matrix of token counts. The matrix is used to train the dataset and test the datasets results. The niave bayes model had a accuracy rate of 97%. The niave bayes model outperformed the logistic regression model regression model which only had a 96% accuracy rate.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Building%20s%20SMS%20spam%20detector.ipynb"> Email spam detector </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Building%20s%20SMS%20spam%20detector.ipynb" target="_blank"> Email spam detector NB </a>

<b> Titanic Classification </b> <br>

The goal is to create a classification model that predicts Titanic passenger survival. A k-nearest neighbors clustering algorithm and an extreme gradient boost model are both trained on passenger information. The extreme graident boost model had a 85% accuracy rate.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Sale%20prediction.ipynb"> Titanic Classification </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Sale%20prediction.ipynb" target="_blank"> Titanic Classification NB </a>

<b> Customer Churn Rate </b> <br>

A random forest classification model and a extreme gradient boost classification model are used to predict whether a customer churned or not. The random forest classification model had a slightly better preformance.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Churn_Risk.ipynb"> Customer Churn Rate </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Building%20s%20SMS%20spam%20detector.ipynb" target="_blank"> Customer Churn Rate NB </a>

<b> Credit scoring (Non-payment) </b> <br>

The project's goal is to predict customer who will not pay their loan debt within 90 days. I trained a random forest classifier and achieved an 83% accuracy rate in this project.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Credit_Score.ipynb"> Credit scoring (Non-payment) </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Credit_Score.ipynb" target="_blank"> Credit scoring (Non-payment) NB </a>

<b> Diabetes Prediction </b> <br>

This projects goal was to predict diabetes using the patients historical medical information. A extreme gradient boost classification model was trained on this dataset. This project shows my programatic ability to evaluate model performance. I used a variety of metrics to evaluate model performance.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Diabetes%20Prediction.ipynb"> Diabetes Prediction </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Diabetes%20Prediction.ipynb" target="_blank"> Diabetes Prediction NB </a>

<b> Forest cover </b> <br>

The goal is to predict the forest cover type from strictly cartographic variables. The categorical independent variables were transformed using a label encoder. Both a random forest classifier and extreme gradient boost classifier model were used to predict forest cover type. The random forest classifier dramatically outperformed the extreme gradient boost model.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Forest_Cover_Classification.ipynb"> Forest cover </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Forest_Cover_Classification.ipynb" target="_blank"> Forest cover NB </a>

<b> Metro Interstate Traffic Volume </b> <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Metro%20Traffic.ipynb"> Metro Interstate Traffic Volume </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Metro%20Traffic.ipynb" target="_blank"> Metro Interstate Traffic Volume NB </a>

<b> NYC Temp V Energy </b> <br>

The goal for this project was to predict New York City energy consumption based on tempature. Energy does not have a linear relationship with tempature. Higher tempatures require energy for air conditioning while lower tempature require energy for heating. As warm tempatures cool or cold tempatures warm, less energy is required. This project shows my ability to use polynomials to predict non-linear relationships.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/NYC%20Temp%20V%20Energy.ipynb"> NYC Temp V Energy </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/NYC%20Temp%20V%20Energy.ipynb" target="_blank"> NYC Temp V Energy NB </a>

<b> NYC Weather V Energy </b> <br>

This project evaluate New York City energy consumption and its realtionship to other weather variables. It is an expansion on the NYC Temp V Energy project. The project compares prediction accuracy between a random forest regressor and extreme gradient boost regressor. The extreme gradient boost regressor boost regressor slightly outperformed the random forest regressor model.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/NYC%20Weather%20V%20Energy.ipynb"> NYC Weather V Energy </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/NYC%20Weather%20V%20Energy.ipynb" target="_blank"> NYC Weather V Energy NB </a>

<b> News prediction </b> <br>

This project uses news articles to create a model that can predict the news articles catagory. The news article's body is TF-IDF count vectorized to show the count and significance of each word. This information is used to train a niave bayes model to predict an article's genre. The niave bayes model has a 84% accuracy rate. This dataset came from <a href="https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_20newsgroups.html"> sklearn 20newsgroups </a>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/News%20prediction.ipynb"> News prediction </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/News%20prediction.ipynb" target="_blank"> News prediction NB </a>

<b> Bird Baths </b> <br>

This projects goal is to predict which birds are more likely to be seen in an urban enviroment or a rural enviroment. The independent variables urban_rural, bird_type and bioregions were used to predict birds perfered habitat. A logistic regression and Extreme Gradient Boost classification model's performance were compared. Ultimately, the XGB classification model preformed better.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Bird%20Baths.ipynb"> Bird Baths </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Bird%20Baths.ipynb" target="_blank"> Bird Baths NB </a>

<b> Craiglist Car Search </b> <br>

This project shows my ability to scrape webpages and aquire data. For this project, I scraped craiglist for used car information and created a tabular dataset of car data.

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Craiglist%20Scraper.ipynb"> Craiglist Car Search </a> <br>
<a href="https://nbviewer.org/github/Lhett2626/Lhett2626.github.io/blob/main/Craiglist%20Scraper.ipynb" target="_blank"> Craiglist Car Search NB </a> <br>

<b> Spelling Bee Solver </b> <br>

This was a fun project where I build a program to find all solutions for the <a href="https://www.nytimes.com/puzzles/spelling-bee"> NY Times Spelling Bee </a> <br>

<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Spelling_Bee_Solver.ipynb"> Spelling Bee Solver </a> <br>
<a href="https://github.com/Lhett2626/Lhett2626.github.io/blob/main/Spelling_Bee_Solver.ipynb" target="_blank"> Spelling Bee Solver NB </a>











