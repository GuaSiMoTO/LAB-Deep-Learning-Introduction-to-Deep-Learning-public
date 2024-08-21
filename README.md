# LAB-Deep-Learning-Introduction-to-Deep-Learning

---

## **Introduction**

In this lab, students will practice what they have learned about perceptrons, starting from the theory to a real-world application. We will work with simple datasets that relate directly to the concepts learned in class. The goal is to build, train, and evaluate perceptron models for binary classification tasks.

Students will use the fundamental building blocks of machine learning, including TensorFlow/Keras, to create perceptron models, while applying the basic ideas of data preprocessing, feature selection, and model evaluation.

## **Task Objective**

You will build simple perceptron models to classify data from simple datasets. In this lab, you'll work through iterations of data preprocessing, model building, training, and evaluation. The aim is to reinforce key concepts learned from the lessons on Perceptrons, TensorFlow, and basic neural networks.

## **Requirements**

To complete this lab, ensure you have the following setup:
1. Install Python and the necessary libraries.
2. Open your preferred IDE (VS Code, Jupyter Notebook, PyCharm) to work through the exercises.
3. Fork the provided repository (if applicable) and clone it locally to begin working on the lab.

---

## **Workflow**

### **Iteration 1: Data Loading**

For the first iteration, load a simple dataset that includes features and a binary target variable. For this lab, you'll use the **Breast Cancer Wisconsin Dataset** from scikit-learn.

- **Step 1**: Import the necessary Python libraries.
- **Step 2**: Load the dataset.
- **Step 3**: Inspect the data by displaying the first few rows of the dataset.

---

### **Iteration 2: Data Exploration**

To understand the dataset better, visualize the relationships between the features and the target.

- **Step 1**: Import the necessary libraries for visualization.
- **Step 2**: Visualize the distribution of the target variable using a histogram.
- **Step 3**: Generate a pairplot to visualize some of the features against the target.

---

### **Iteration 3: Data Preprocessing**

Prepare the data for training by scaling the features and splitting the dataset.

- **Step 1**: Import `train_test_split` from scikit-learn.
- **Step 2**: Split the dataset into training and test sets with an 80-20 ratio.
- **Step 3**: Standardize the features using a scaler.

---

### **Iteration 4: Model Building**

Create a simple perceptron model using TensorFlow/Keras.

- **Step 1**: Import the necessary components from TensorFlow/Keras.
- **Step 2**: Build a perceptron model with a single Dense layer. The activation function for the output layer should be 'sigmoid'.
- **Step 3**: Compile the model.

---

### **Iteration 5: Model Training**

Train the perceptron model on the training data.

- **Step 1**: Train the model for 50 epochs.
- **Step 2**: Track the loss and accuracy during training.

---

### **Iteration 6: Model Evaluation**

Evaluate the performance of your perceptron model on the test data.

- **Step 1**: Use the `evaluate()` function to check the accuracy of the model on the test set.
- **Step 2**: Plot the training and validation accuracy over epochs to visualize the learning process.

---

### **Iteration 7: Conclusion and Reflection**

After completing the above steps, reflect on the results and write down your observations:
- How did the perceptron perform on the binary classification task?
- What challenges did you encounter during training, and how did you overcome them?
- How would you modify the model for better performance?

---

## **Submission**

After completing all iterations, ensure your code is clean and well-commented. Push your final Jupyter notebook or Python script to the GitHub repository and submit the link for evaluation.

---

## **Conclusion**

This lab provides a hands-on experience with perceptrons, helping you solidify the basic concepts of neural networks and binary classification. By practicing this lab, you will strengthen your understanding of how simple neural networks like perceptrons can be used in practical machine learning tasks.

---

Happy coding! 🎉
