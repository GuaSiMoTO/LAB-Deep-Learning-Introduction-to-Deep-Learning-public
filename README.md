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

## Iteration 0: Exploring a Simple Perceptron

Understand how a simple perceptron can solve classification problems and how to adjust the input layers to improve accuracy.

## Steps

### Initial Setup in TensorFlow Playground
- Open [TensorFlow Playground](https://playground.tensorflow.org/#activation=sigmoid&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=&seed=0.20988&showTestData=false&discretize=false&percTrainData=20&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false)
- Select one of the four available datasets (circles, XOR, etc.).
- Ensure that no hidden layers are selected (0 HIDDEN LAYERS).
- In the **FEATURES** section, select the input features `x_1` and `x_2`.
- In the **OUTPUT** section, select the Sigmoid activation function.
- Ensure regularization is turned off (None).

### Classification with the Exclusion Dataset
- Select the exclusion dataset.
- Adjust the input features and observe how the decision boundary is formed to separate the classes.
- Train the model and observe the results.
- Discuss the limitations of the simple perceptron with this dataset and the need for more complex networks.

![tensorflow-playground](https://github.com/user-attachments/assets/d9a81ee4-39ba-461f-9184-110a65551988)

### Classification with the Circles Dataset
- Select the circles dataset.
- Adjust the input features and observe how the decision boundary is formed to separate the classes.
- Train the model and observe the results.
- Discuss how the simple perceptron has managed (or failed) to separate the classes.

### Classification with the XOR Dataset
- Select the XOR dataset.
- Adjust the input features and observe how the decision boundary is formed to separate the classes.
- Train the model and observe the results.
- Discuss the limitations of the simple perceptron with this dataset and the need for more complex networks.

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
