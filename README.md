# internship-Task6
Internship

 K-Nearest Neighbors (KNN) Classification using the Iris Dataset

 Aim
The goal of this project is to understand and implement the **K-Nearest Neighbors (KNN)** algorithm for classification tasks using the **Iris dataset**. This includes:
- Learning instance-based learning and the role of Euclidean distance
- Experimenting with different values of `K`
- Evaluating model performance using accuracy and confusion matrix
- Visualizing decision boundaries to interpret the classifier’s behavior



 1. Choose a Classification Dataset and Normalize Features
We selected the **Iris dataset**, a classic multi-class classification problem. Normalization is essential in KNN to ensure all features contribute equally to distance calculations, which is crucial because KNN is distance-based.

  2. Use `KNeighborsClassifier` from `sklearn`
The `KNeighborsClassifier` from `scikit-learn` was used to train and test the model. This model works by finding the `k` nearest training examples in the feature space and predicting the majority class among them.

  3. Experiment with Different Values of `K`
We experimented with multiple `k` values (1, 3, 5, 7) to study how the number of neighbors affects classification accuracy and decision boundaries.

  4. Evaluate Model using Accuracy and Confusion Matrix
The model performance was evaluated using:

    - **Accuracy Score**: Percentage of correct predictions
    - **Confusion Matrix**: To analyze true positives, false positives, and misclassifications across classes

 6. Visualize Decision Boundaries
We plotted decision boundaries for a 2D feature space to visually understand how KNN partitions the feature space and how it changes with different `k`.




  Description:
The Iris dataset contains **150 samples** divided into **3 species of Iris**: *Setosa*, *Versicolor*, and *Virginica*. Each sample has **4 features**:

      - Sepal length (cm)
      - Sepal width (cm)
      - Petal length (cm)
      - Petal width (cm)

For visualization purposes, only the first two features were used when plotting the decision boundary. However, the model can be extended to use all four features for better accuracy.


 Tools & Libraries Used:

- **Python**
- **Pandas** for data handling
- **Scikit-learn** for model implementation
- **Matplotlib** for visualization


 Results
- Accuracy was evaluated for `k = 1, 3, 5, 7`
- Confusion matrices were generated for each `k`
- A decision boundary plot was created for `k = 5`



