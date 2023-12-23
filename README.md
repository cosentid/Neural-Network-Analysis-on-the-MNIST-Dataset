# Neural-Network-Analysis-on-the-MNIST-Dataset

**Objective:**
This project aims to provide students with practical experience in building and evaluating neural network models. Using the MNIST dataset, a classic in the field of machine learning, students will explore various neural network architectures, implement validation techniques, and critically analyze model performance.

**Dataset:**
The MNIST database, a large collection of handwritten digits, is a benchmark dataset in machine learning. It consists of 70,000 images (28x28 pixels) of handwritten digits (0-9). Students will use this dataset to train and test neural network models.

**Project Tasks:**

1. **Data Preparation:**
   - Load the MNIST dataset.
   - Normalize the image pixel values.
   - Split the data into training (70%), validation (10%), and testing (20%) sets.

2. **Model Building:**
   - Design various neural network architectures, starting from simple single-layer networks to more complex multi-layer architectures.
   - Experiment with different numbers of neurons, layers, and activation functions.

3. **Training with Validation and Patience:**
   - Use the validation dataset for early stopping with patience to prevent overfitting. Set patience equal to 10 epochs.

4. **Performance Evaluation:**
   - Train each neural network model on the training set.
   - Evaluate the final model performance on the test set.
   - Record key metrics such as train/test accuracy, loss over epochs for both training and validation sets.
   - Record the time used to train each model.

5. **Result Reporting:**
   - Present the results in a $3 \times M$ table, a row for train, test, and time, and a column for each model, where $M$ is the total number of models.

   - Create a $1 \times 2$ figure of train and test performance vs epochs, for all the models on the same figure, with each model distinguished by color and appropiate legends.

   - Discuss the impact of various architectures and training techniques on model performance.

6. **Models:**
   - `nn1` $784 \times 20 \times 10$
   - `nn2` $784 \times 40 \times 20 \times 10$
   - `nn3` $784 \times 80 \times 40 \times 20 \times 10$
   -  Use `Adam` with `l=0.001`
   -  The total number models to try is $M=3$.
