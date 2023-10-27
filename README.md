# Maternal Decision Tree - Maternal Risk


## Project Background
This project was developed as part of a certification program in Introduction to Artificial Intelligence and Machine Learning at the Federal University of Bahia (UFBA). The program provided valuable insights and hands-on experience in the field of AI and machine learning.


### About Dataset
Context
Data has been collected from different hospitals, community clinics, maternal health cares through the IoT based risk monitoring system.

Age: Age in years when a woman is pregnant.
SystolicBP: Upper value of Blood Pressure in mmHg, another significant attribute during pregnancy.
DiastolicBP: Lower value of Blood Pressure in mmHg, another significant attribute during pregnancy.
BS: Blood glucose levels is in terms of a molar concentration, mmol/L.
HeartRate: A normal resting heart rate in beats per minute.
Risk Level: Predicted Risk Intensity Level during pregnancy considering the previous attribute.

### Data Preprocessing
Data Normalization with Z-score
In this project, we employed data normalization techniques to ensure that our features were on a consistent scale. One of the techniques used was Z-score normalization (also known as standardization or mean normalization). This technique helps in making the data follow a standard normal distribution with a mean of 0 and a standard deviation of 1.

### Choice of Machine Learning Algorithm
In this project, we carefully considered several machine learning algorithms to address the specific problem at hand. After thorough experimentation and analysis, we ultimately chose to implement the Decision Tree algorithm.


## Getting Started

### Prerequisites

List any prerequisites or dependencies that need to be installed before running your code.

- Python (version X.X)
- Jupyter Notebook
- Numpy
- Pandas
- Matplotlib
- Scikit-Learn

### Installation

Provide instructions for installing the necessary dependencies. You can use code blocks or bullet points.

```bash
pip install numpy
pip install pandas
pip install matplotlib
pip install scikit-learn

