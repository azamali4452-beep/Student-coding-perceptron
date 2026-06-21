Latent Space Representation of Coding Experience

This project implements a single-layer perceptron to classify students based on their coding experience across six programming languages: C/C++, Python, MATLAB, R, Assembly, and Java.

Project Structure

 perceptron.ipynb: The main notebook containing the data generation, perceptron implementation, and visualization code.
 *data/: The project uses synthetic data generated directly by the notebook code.

How to Run

 1. Open the project in Google Colab.
 2. Run all cells sequentially. The code will generate a dataset of 1000 student entries.
 3. The model will perform classification and generate a 2D plot of the decision boundary for Python vs. C/C++ experience.

 Project Objectives

The project follows these steps to implement a linear classifier:
 Data Preparation: Creating a 1000-entry dataset representing lines of code per language.

 Experience Function: Designing a scoring function to aggregate coding proficiency.

 Perceptron Model: Implementing a neural network architecture (w^Tx \ge b) to differentiate students who have taken a programming class from those who have not.

 *Visualization: Drawing the vector w and the decision boundary w^Tx = b to visualize the linear partition in 2D space.

Methodology
The perceptron algorithm iterates through the data and updates the weight vector w whenever a classification error occurs (w \leftarrow w + y_i x_i). This continues until the data is partitioned correctly, or the maximum number of iterations is reached.

