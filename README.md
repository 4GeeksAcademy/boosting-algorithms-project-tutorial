<!-- hide -->
# Boosting - Step by step guide
<!-- endhide -->

- Use the data you have analyzed in the previous two projects.
- Continue with the development to find a model that fits better.

<onlyfor saas="false" withBanner="false">
  
## 🌱  How to start this project

Follow the instructions below:

1. Create a new repository based on [machine learning project](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) by [clicking here](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Open the newly created repository in Codespace using the [Codespace button extension](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).
3. Once the Codespace VSCode has finished opening, start your project by following the instructions below.

</onlyfor>

## 🚛 How to deliver this project

Once you have finished solving the exercises, be sure to commit your changes, push to your repository and go to 4Geeks.com to upload the repository link.

## 📝 Instructions

### Predicting diabetes

In the two previous projects we saw how we could use a decision tree and then a random forest to improve the prediction of diabetes. We have reached a point where we need to improve. Can boosting be the best alternative to optimize the results?

Boosting is a sequential composition of models (usually decision trees) in which the new model aims to correct the errors of the previous one. This view may be useful in this data set, since several of the assumptions studied in the module are met.

In this project you will focus on this idea by training the dataset to improve the $accuracy$.

Remember that previous projects can be found [here](https://github.com/4GeeksAcademy/decision-tree-project-tutorial) (decision trees) and [here](https://github.com/4GeeksAcademy/random-forest-project-tutorial) (random forest).

#### Step 1: Loading the dataset

Loads the processed dataset from the previous project (split into training and test samples and analyzed with EDA).

#### Step 2: Build a boosting

One way to optimize and improve the results is to generate a boosting so that there is the necessary variety to enrich the prediction. Train it and analyze its results. Try modifying the hyperparameters that define the model with different values and analyze their impact on the final accuracy and plot the conclusions.

#### Step 3: Save the model

Store the model in the corresponding folder.

#### Step 4: Analyze and compare model results

Make a study now of the three models used, analyze their predictions, the class with the highest prediction accuracy and the one with the lowest. Which of the three models do you choose?

> NOTE: Solution: https://github.com/4GeeksAcademy/boosting-algorithms-project-tutorial/blob/main/solution.ipynb
