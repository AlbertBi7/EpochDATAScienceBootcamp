# Google Play Store Apps

## Dataset Overview

**Dataset Link:** https://www.kaggle.com/datasets/lava18/google-play-store-apps

This dataset contains information about thousands of applications available on the Google Play Store. It includes details such as the app category, rating, number of installs, reviews, size, content rating, pricing, and more.
---

## Business Problem

By analyzing this dataset, we can identify the factors that influence an app's popularity. This can help developers make better decisions about pricing, app category, content rating, and feature improvements before launching or updating an app.

---

## Machine Learning Problem Framing

I chose to frame this as a **Regression** problem.

The objective is to predict the **rating** of an app based on its characteristics, such as the number of reviews, category, size, pricing, and installs. Since the rating is a continuous numerical value (typically between 1 and 5), regression is the most suitable machine learning approach.

---

## Target Variable

**Target Variable:** `Rating`

This column represents the average user rating given to an app on the Google Play Store.

---

## Key Features

Some of the important features for this problem include:

* `Category` – Type of application
* `Reviews` – Number of user reviews
* `Installs` – Total number of downloads
* `Size` – App size
* `Type` – Free or Paid
* `Price` – Price of the app
* `Content Rating` – Target audience
* `Genres` – App genre
* `Last Updated` – Date of the latest update

These features can help explain the factors that influence user ratings.

---

## Key Observations

1. The dataset contains over **10,000 apps** from a wide variety of categories, making it suitable for exploratory analysis and machine learning.

2. Some columns, particularly **Rating**, contain missing values that need to be handled before model training.

3. Features such as the number of installs, reviews, app category, and pricing appear to have a significant relationship with an app's rating and overall popularity.

