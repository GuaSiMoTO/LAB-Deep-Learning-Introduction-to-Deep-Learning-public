# LAB-Deep-Learning-Introduction-to-Deep-Learning

![Image](https://user-images.githubusercontent.com/970858/63474771-d6734700-c469-11e9-83bb-9429da563909.png)

## **Introduction**

In this lab, students will practice what they have learned about perceptrons, starting from the theory to a real-world application. We will work with simple datasets that relate directly to the concepts learned in class. The goal is to build, train, and evaluate perceptron models for binary classification tasks.

Students will use the fundamental building blocks of machine learning, including TensorFlow/Keras, to create perceptron models, while applying the basic ideas of data preprocessing, feature selection, and model evaluation.

## **Task Objective**

You will build simple perceptron models to classify data from simple datasets. In this lab, you'll work through iterations of data preprocessing, model building, training, and evaluation. The aim is to reinforce key concepts learned from the lessons on Perceptrons, TensorFlow, and basic neural networks.

## Initial Setup

### Requirements
Start by forking the provided GitHub repository to your account and then clone it locally. This will be your workspace for completing the lab exercises.
- [Learn how to fork this repo](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project)
- Clone this repo into your code/labs folder.

### Setup Instructions
To run the notebook and reproduce the results, follow these steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/codeskills-ai/LAB-Deep-Learning-Introduction-to-Deep-Learning.git
    cd LAB-Deep-Learning-Introduction-to-Deep-Learning
    ```

2. Create a virtual environment and install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ``` 

To test that everything is set up correctly, run the first cell in the notebook. This cell usually contains import statements and initial setup code. If it runs without errors, you are ready to start solving the exercises.

You can write and execute your code in the provided cells within the notebook. Any outputs, including print statements and visualizations, will be displayed directly in the notebook, making it easy to debug and verify your solutions.

# Iteration 0: Exploring a Simple Perceptron

In this iteration, you will explore how a simple perceptron operates for classifying linearly separable data. You will use TensorFlow Playground to configure and observe the behavior of a basic perceptron model.

1. **Access TensorFlow Playground:**
   - Go to [TensorFlow Playground](https://playground.tensorflow.org/).

2. **Configure the Model:**
   - **Number of Layers:**
     - **Input Layer**: 3 neurons (representing the three input features).
     - **Hidden Layer**: **None** (this ensures the model is a simple perceptron).
     - **Output Layer**: 1 neuron.
   - **Activation Functions:**
     - **Output Layer**: Set to Sigmoid (feel free to experiment with other activations like 'ReLU').
   - **Dataset:**
     - **Dataset**: Use the 'Linearly Separable' dataset.
   - **Training Configuration:**
     - **Learning Rate**: Set to 0.01.
     - **Epochs**: Set to 50.

## Tasks

### Initial Observation

1. **Verify Initial Configuration:**
   - Ensure the network is configured with no hidden layers and one neuron in the output layer.
   - Check that the activation function for the output layer is ReLU.

2. **Predict Initial Output:**
   - Look at the dataset in the feature space. What kind of decision boundary do you expect the perceptron to create?
   - Click the **▶️** button to train the model.
   - Observe the decision boundary and compare it with your expectations.

###  Adjusting Learning Rate

1. **Modify the Learning Rate:**
   - Change the learning rate to a different value (e.g., 0.1 or 0.001).
   - Observe how the learning rate affects the training and the decision boundary.

2. **Reflect on Learning Rate Effects:**
   - How does changing the learning rate influence the convergence of the perceptron? Does the decision boundary change significantly?

### Comparing Activation Functions

1. **Change Activation Function:**
   - Change the activation function of the output layer to 'Sigmoid' or 'Tanh'.
   - Observe how the decision boundary is affected by this change.

2. **Discuss Activation Effects:**
   - How does the choice of activation function affect the perceptron’s performance in classifying the data?

## Discussion Questions

1. **Understanding the Perceptron:**
   - What did you learn about the behavior of the simple perceptron with different settings?
   - What limitations did you notice when using a simple perceptron?

2. **Application of Perceptrons:**
   - What types of classification problems can a simple perceptron solve effectively?
   - When might it be necessary to use a more complex neural network?
- **Step 1**: Import the necessary libraries for visualization.
- **Step 2**: Visualize the distribution of the target variable using a histogram.
- **Step 3**: Generate a pairplot to visualize some of the features against the target.


## **Workflow**

### **Iteration 1: Data Loading**

For the first iteration, load a simple dataset that includes features and a binary target variable. For this lab, you'll use the **Breast Cancer Wisconsin Dataset** from scikit-learn.

- **Step 1**: Import the necessary Python libraries.
- **Step 2**: Load the dataset.
- **Step 3**: Inspect the data by displaying the first few rows of the dataset.

---

### **Iteration 2: Data Exploration**

To understand the dataset better, visualize the relationships between the features and the target.

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

## Submission
Once you have completed your analysis and visualizations, push your Jupyter notebook to your forked GitHub repository. Ensure that your final submission includes narratives explaining your visualizations and insights.


```bash
$ git add .
$ git commit -m "done"
$ git push origin main
```

Then create a Pull Request!!

## Additional Resources

- [ ]()
- [ ](/)
- [ ]()
- [ ]().
- [ ]().

![happy_coding](https://user-images.githubusercontent.com/970858/63899010-c23fc480-c9ea-11e9-84a2-542907e42362.png)
