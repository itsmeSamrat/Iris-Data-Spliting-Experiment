Breaking Down the Numbers: Which Data Split Ratio Yields Superior Machine Learning Results?

<!-- Logo Section  -->

<div align="center">
    <a href="https://github.com/itsmeSamrat" target="_blank">
        <img src="https://github.com/itsmeSamrat/Iris-Data-Spliting-Experiment/blob/main/cover%20image.png?raw=true" 
        alt="Logo" width="600" height="300">
    </a>
</div>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=3500&pause=200&center=true&vCenter=true&multiline=true&width=600&height=100&lines=Breaking+Down+the+Numbers;Which+Data+Split+Yields+Superior+ML+Results%3F">
</div>

## Description

In this experiment, we will be trying to find which split give us constant high-accuracy models. Either 60–20–20 ratio or 80–10–10 ratio. For this, we have the Iris flower dataset, which is easy to understand and widely used dataset.

In the first experiment, we need to split the dataset into a 60–20–20 ratio meaning 60% of the data will be used to train the model, 20% will be used to validate the models and 20% will be used to get the unbiased result of the best performing model which we get from the validated dataset. We need to perform the KFold Cross Validation to find a baseline performance of the models, perform Grid Search to find optimal hyperparameter for the model which in turn will increase its accuracy, and finally compare the 3 models which we have selected using classification metrics like Accuracy, Precision, Recall, and Latency of the model.

In the second experiment, the change will be only on how we split the dataset. Here, we split the dataset into an 80–10–10 ratio. 80% will go to train the model, 10% will go to validate the model and 10% will go to test the model. Other all the steps are the same.

We have selected three models for our experiment:

1. Logistic Regression (LR)
2. Support Vector Classifier (SVC)
3. Random Forest Classifier (RF)

[getting started](#getting-started)

## Getting Started

- Clone the repo into your local machine.

```bash
    git clone https://github.com/itsmeSamrat/Iris-Data-Spliting-Experiment.git
```

- Install all the packages and libraries from requirement.txt file
- Run the [notebook](https://github.com/itsmeSamrat/Iris-Data-Spliting-Experiment/blob/main/Splitting%20the%20Data%20to%2060-20-20%20ratio%20vs.%2080-10-10.ipynb), it should run without any problems.
- Try testing using other splits like 70-15-15 and publish your result.
- You can try using other different models and other dataset of you liking.
- If you find this interesting. Support by staring the repo 🙂😁.

Thank you. ✌✌

## Medium Article

[Splitting the Data to 60–20–20 ratio vs. 80–10–10. Which one is better?](https://medium.com/@itsmeSamrat/splitting-the-data-to-60-20-20-ratio-vs-80-10-10-which-one-is-better-bbc3503830d8)

## Acknowledgement

- [Dataset](https://www.kaggle.com/datasets/uciml/iris)

## License

This project is under MIT License - see the [License.txt](https://github.com/itsmeSamrat/Iris-Data-Spliting-Experiment/blob/main/license.txt) file for more details.

## Feedback

- If you notice any mistake or can make it better. Feel free to open a pull request and correct it or email me on the below email id.

## Contact Me 📨

Email : [itsmesamratthapa@gmail.com](mailto:itsmesamratthapa@gmail.com)

<!-- Back to the top -->

[Return Back to Top ⬆️](#getting-started)
