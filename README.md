# Personalize

https://docs.aws.amazon.com/personalize/latest/dg/getting-started-console.html

## Overview

1. Create/import training data (datasets)
    1. Create dataset group
    2. Specify your schema which your dataset abides to
2. Create a Solution (i.e. use the dataset to train a model. A trained model is referred to as a solution)
    1. Create solution after training data has been imported successfully
    2. Choose recipe aka algorithm and data processing (manual or automatic)
3. Create a campaign (get recommendations from the solution)
    1. Specify solution
4. Get recommendations
    1. Get recommendations within console or alternatively use the getRecommendations API to get recommendations in your app

## Recommendations Output

![recommendations](https://i.imgur.com/QxDxb0J.png "Recommendations")

