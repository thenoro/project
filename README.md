# Report Project

## Overview of contents
This datascience project is organized in the following structure:
<ul>
    <li>project/
        <ul>
           <li> data/</li>
            <li>docs/</li>
            <li>images/</li>
            <li>src/</li>
            <li>reports/</li> 
        </ul>
    </li>
</ul>

## Analysis
These are the steps performed:
<ol>
    <li>Load and visualize the dataset using a scatter plot with different colors for each target class</li>
    <li>Split the data into training and testing sets using the train_test_split() function from scikit-learn</li>
    <li>Train a logistic regression model using the LogisticRegression() function</li>
    <li>Evaluate the model on the testing set using the predict() method, and calculate the accuracy of the predictions using accuracy_score() from scikit-learn.</li>
    <li>Finally, visualize the model predictions on the testing set using the plt.scatter() function</li>
</ol>

## Dependencies
The following packages are needed to run the Report: 
  - ipykernel
  - scikit-learn=1.3.0
  - pandas
  - matplotlib
  - python
