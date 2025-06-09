# Home Assignment 2
# CS5720 Neural Networks and Deep Learning

## Student Name: gudiseva charan santhosh 
## Student id: 700776700
## Course: CS5720 – Neural Networks and Deep Learning  
## University: University of Central Missouri  

---

## Assignment Overview

## Question 1: Convolution Operations with Different Parameters
- In this task, I performed convolution on a 5×5 matrix using a 3×3 kernel with different stride and padding values.

## What I Did:
- Defined a 5×5 input matrix and a 3×3 kernel.
- Used TensorFlow to apply convolution in 4 configurations:
- Stride = 1, Padding = ‘VALID’
- Stride = 1, Padding = ‘SAME’
- Stride = 2, Padding = ‘VALID’
- Stride = 2, Padding = ‘SAME’
- Printed all the output feature maps for analysis.

## What I Observed:
- 'VALID' padding reduces output size.
- 'SAME' padding keeps the output size equal to input.
- Increasing stride reduces the output resolution.

## Question 2: CNN Feature Extraction and Pooling
## Task 1: Edge Detection using Sobel Filter
- I used OpenCV and NumPy to apply Sobel filters for edge detection.

## What I Did:
- Uploaded a grayscale image using Google Colab.
- Applied Sobel-X and Sobel-Y filters.
- Displayed original, X-edge, and Y-edge images using matplotlib.

## What I Observed:
- Sobel-X detects vertical edges.
- Sobel-Y detects horizontal edges.
- Combined, they highlight sharp changes in intensity.

## Task 2: Max Pooling and Average Pooling
- I used TensorFlow to demonstrate pooling techniques on a random 4x4 matrix.

## What I Did:
- Created a 4x4 matrix using NumPy.
- Applied:
- 2×2 Max Pooling
- 2×2 Average Pooling

- Printed the original, max-pooled, and average-pooled matrices.

## What I Observed:
- Max pooling retains strong features.
- Average pooling smooths the data.
- Pooling reduces the dimensionality of feature maps.

## Question 3: Data Preprocessing - Normalization vs. Standardization
- In this task, I compared two scaling methods using the Iris dataset.

## What I Did:
- Loaded the Iris dataset from sklearn.
- Applied Min-Max Normalization using MinMaxScaler.
- Applied Z-score Standardization using StandardScaler.
- Plotted histograms to compare feature distributions.
- Trained Logistic Regression models:
- On raw data
- On normalized data
- On standardized data
- Compared the model accuracies.

## What I Observed:
- All models achieved similar accuracy (~97%).
- Normalization scaled values between 0 and 1.
- Standardization centered values around 0 with unit variance.

---

##  Notes
- Make sure to `pip install tensorflow`,`pip install opencv-python matplotlib tensorflow`,`pip install pandas scikit-learn` if not already installed.
---

## How to Run This Project

1. Clone the repo:git clone https://github.com/charansanthosh1675/Home_Assignment_2_charan-santhosh.git
2. Install required libraries:pip install tensorflow matplotlib,pip install opencv-python matplotlib tensorflow,pip install pandas scikit-learn
3. Run the Python file:python Home_Assignment_2_charan_santhosh.py

---

## Output Screenshot Example:

## question 1

![image](https://github.com/user-attachments/assets/e41b6d5b-3983-4202-aa8b-44322f02bf16)

## question 2 
## Task 1

![image](https://github.com/user-attachments/assets/52c0166f-8cc6-4996-9ec6-0d4047f7be56)

## Task 2

![image](https://github.com/user-attachments/assets/df84500d-cf63-4ef3-aa25-5c41d0d224a2)

## question 3

![image](https://github.com/user-attachments/assets/211ae552-0a2e-4f2a-b7a1-6cc2660d7810)






