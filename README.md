# BreastCancerDetection: A Deep Dive into Breast Cancer Detection

Welcome to Breast-Cancer-Detection, where the strength of artificial intelligence collides with the challenge of breast cancer diagnosis. In this repository, we have developed a breast cancer detection model using Artificial Neural Networks (ANNs) to assist in identifying malignant and benign breast tumors.

## Project Overview

Our mission is to create a robust system capable of accurately classifying breast cancer cases based on diagnostic features. By leveraging powerful deep learning techniques and data analysis, we've trained the model to identify subtle patterns indicative of malignant tumors. The dataset consists of well-annotated features from breast biopsies, allowing the model to learn and distinguish between malignant and benign cases.

## Technologies Used

- TensorFlow
- Keras
- Scikit-Learn
- Matplotlib
- Pandas
- Numpy

## Access the Dataset

To access the dataset used in this project, visit [Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data) on Kaggle. Follow the dataset's page for download and usage instructions.

## Dataset Structure

1) ID number
  
2) Diagnosis (M = malignant, B = benign)<br>

3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)<br>
b) texture (standard deviation of gray-scale values)<br>
c) perimeter<br>
d) area<br>
e) smoothness (local variation in radius lengths)<br>
f) compactness (perimeter^2 / area - 1.0)<br>
g) concavity (severity of concave portions of the contour)<br>
h) concave points (number of concave portions of the contour)<br>
i) symmetry<br>
j) fractal dimension ("coastline approximation" - 1)<br>

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

## How to Use

1. Clone the repository: `git clone [repo_url]`
2. Navigate to the appropriate directory: `cd BreastCancerVision`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the main script to train and evaluate the model: `python main.py`

Feel free to explore the code, experiment with the model, and contribute to the advancement of BreastCancerVision!

# Contact

For questions, suggestions, or collaboration opportunities, please contact me at [korayalkankarakoc@gmail.com](mailto:korayalkankarakoc.com).

# Contribution

Contributions are welcome! If you have ideas for improvements, open an issue or create a pull request.<br>
Together, let's make a positive impact in breast cancer detection!

---
