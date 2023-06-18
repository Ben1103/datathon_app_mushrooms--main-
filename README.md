# Mushroom Classification Competition

Welcome to the Mushroom Classification Competition repository! This repository contains the code and resources for the competition organised for the students at WBS Coding School taking the 15-week data science bootcamp.

## Competition Description

In this competition, your task is to build a classification machine learning model that predicts whether mushrooms are poisonous or edible. The objective of the model is to prevent anyone from eating a poisonous mushroom while maximising the number of edible mushrooms.

## Dataset

The dataset provided for this competition consists of various features that describe different attributes of mushrooms. These features include physical characteristics such as cap shape, cap colour, stalk shape, gill colour, and more. The target variable is the mushroom's class, which can be either "poisonous" or "edible".

You can find the training and test data in the [data](./data) directory of this repository.

## Submission and Evaluation

To participate in the competition, you will need to submit your predictions through the Streamlit app provided in the `app.py` file. This app allows you to upload your model's predictions and automatically scores and ranks the entries based on their performance.

The submissions will be evaluated based on the following criteria:

1. **Prevention of Poisoning**: The primary goal of the competition is to ensure that no one consumes a poisonous mushroom. Therefore, the model's ability to correctly classify poisonous mushrooms is crucial. Submissions will be evaluated based on how well they prevent the consumption of poisonous mushrooms.

2. **Edible Mushroom Maximisation**: While preventing poisoning is important, we also want to maximise the number of edible mushrooms that can be safely consumed. Submissions will be evaluated based on their ability to correctly identify edible mushrooms.

To quantify these criteria, the following metrics will be considered:

- **Precision**: Higher precision indicates a lower risk of false positives, i.e., misclassifying edible mushrooms as poisonous.

- **Recall**: Higher recall indicates a lower risk of false negatives, i.e., misclassifying poisonous mushrooms as edible.

Participants are encouraged to strike a balance between precision and recall. Maximising the accuracy alone is not sufficient, as it could lead to a higher risk of consuming poisonous mushrooms.

Note: It is important to prioritise the prevention of poisoning over edible mushroom maximisation. A model with higher precision and lower recall is preferred over a model with lower precision and higher recall, as the former ensures safety while the latter poses a risk.

The submissions that prevent any poisonis mushroom being eaten and maximising the consumption of edible mushrooms will be recognised as the winners of the competition.

## Resources

- [Mushroom Classification Dataset](https://archive.ics.uci.edu/dataset/73/mushroom): The dataset for the competition.
- [scikit-learn](https://scikit-learn.org/): A powerful machine learning library for Python.
- [pandas](https://pandas.pydata.org/): A versatile data manipulation library for Python.
- [NumPy](https://numpy.org/): A fundamental package for scientific computing with Python.
- [Streamlit](https://streamlit.io/): An open-source Python library for building interactive web applications.

## Acknowledgements

This competition is organised by WBS Coding School as part of the 15-week data science bootcamp. Special thanks to all the instructors and mentors for their support and guidance throughout the competition.

Happy coding and good luck with the Mushroom Classification Competition!
