# Android playstore dataset EDA 📱

### Overview and Motivation

This EDA project aims to discover patterns that lead to a successfull application on the Google Play Store. This will be done by analyzing the historical data collected from the Google Play Store as of 03 Feb 2019 according to dataset source. We hypothesize that there are patterns within the data that lead to a successfull app. We are trying find the successfull pattern to develop an app that may be in the high ranks one day, help ad providers know which apps to post their ads on. This will be done by initializing a machine learning model after the data is cleaned, that when givem features about an arbitrary app it gives an estimate rating for that app.

### Dataset Link 🔗
https://www.kaggle.com/lava18/google-play-store-apps

### Takeaways 🥡
**Make sure to check the [Notebook Section 5 for more insights](playstore-eda.ipynb)**

- Developers should optimize their app download size as much as possible as this leads to better rating and more installs.
- Paid apps represent only 7.8% of all apps.
- The trend is games have a much larger download size than any other category. If you're developing anything other than a game, you need to optimize your downlaod size. on Average any app should have a size of 17.8 MB.
- There are more family apps in the play store than games.
- Finance and lifestyle apps are valued the most. On average an app price is $1.
- There are apps as expensive as $400 with more than 10K downloads.
- Communication apps are the most downloaded apps.
- Average rating on the playstore is 4.17.
