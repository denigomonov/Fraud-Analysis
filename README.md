# Fraud-Analysis

## Project Goal:
My main goal in this project was to see how well Keras can be used to classify binary. First, I wanted to perform a visual analysis to discover if there are any trends that can be spotted from a human perspective and point out features of interest. Finally, after labeling and feeding the data to the model, I assessed the performance of this approach.

---

## Vechile Insurance Claim Fraud Data:
For the development of this project I retrieved data from - [Kaggle](https://www.kaggle.com/datasets/shivamb/vehicle-claim-fraud-detection).

---

## Development:
### EDA (Jupyter):
- Visualizing data via _Matplotlib_ and _Plotly_ to discover any trends that would be present through breaking down data visually. _Horizontal Bar Chart_ matrix was used to represent distinct counts of each feature per category and _Parallel Category Chart_ was used to see the feature flow resulting in fraud/not fraud.

![Animation](https://user-images.githubusercontent.com/34199193/211701203-1f7919e1-0ab4-4cd8-9908-dac57999582e.gif)
### ML (Keras):
- Encoding columns via _cat.codes_ and splitting data for the model fitting.
- Creating a Keras model with 32 input neurons in the input layer and  32 neurons in 1 hidden layer, and utilizing adam optimizer and binary crossentropy.
- Evaluating model performance and achieving loss: 0.9092 - accuracy: 0.9361

![Animation_2](https://user-images.githubusercontent.com/34199193/211701393-2570dd2b-b37b-4d20-954b-7259fb7f0ee7.gif)

