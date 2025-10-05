![alt text](https://github.com/mofidi80/ML_Foundations/blob/2b4e5275576ed1f32f8a3fabe54b9c9d1fc80638/blob/nano-banana-2025-10-05T17-36-21.png)


## 1. Housing Dataset Linear Regression Hyperparameter Optimization
In this project we attempt to optimize the hyperparameters of lasso and ridge models on Boston housing dataset.

### Goals
1. Find optimal hyperparameter for Lasso linear regression from among the given options.
2. Find optimal hyperparameter for Ridge linear regression from among the given options.
3. Compare the two models to find the best model for this dataset.

### Outcome
* We found out that in this dataset using lasso regularization is slightly better for accuracy of predictions.

Use this link to easily view the notebook online:
https://nbviewer.org/github/mofidi80/Housing_Linreg_hyperpara_opt/blob/main/boston%20housing%20linreg%20hyperparameter%20opt.ipynb


## 2. Student Dataset Creator
Simple python script for creating a sql dataset to store student data along with a webcam picture of said student with corresponding name and id.

In the second year of my undergraduate degree one of my professors wanted to get to know the students of the class and asked us to take a selfie and send it to her; I thought it would be difficult to keep the data from all her classes organized so I wrote this script. She seemed to really like it though I don't know if she ended up using it later.
*For use refer to the files "dataset_creator.py", "face detection database.db", "haarcascade_frontalface_default.xml"*


## 3. Linear ML Models Sensitivity to Outliers
In this project, we will test LinearRegression, Lasso, and Ridge linear regression models to see how sensitive they are to outliers using mean squared error and mean absolute error.

### Goals
1. Which model is more sensitive to outliers.
2. Which testing metric is more affected by outliers.

### Outcome
We found out that MSE is more affected by outliers and Ridge regularization is more sensitive to outliers. So if we want to pay less attention to outliers we should use MAE and Lasso regularization.

Use this link to easily view the notebook online:
https://nbviewer.org/github/mofidi80/LinearML_Sensitivity_Outliers/blob/main/linear%20ml%20sensitivity%20outliers.ipynb

## 4. Spectal Segmentation on Image
In this project, we use a spectral segmentation model to seperate the foreground from the background.

### Goal
See how well we can seperate the bird in the image from the background

### Outcome
![Alt text](https://github.com/mofidi80/ML_Foundations/blob/343ff70e8550f64024ad23f4aea22ae641a0cedb/blob/Untitled.png)

## Built With (for all projects)
* Python
   + Numpy
   + Pandas
   + Matplotlib, Seaborn
   + Scikit-Learn
   + open-cv
   + sqlite3 (only in python ver < 2.5)


## Installation
1. First intall jupyter notebook from the link below if you haven't already.
   + https://jupyter.org/install
2. Make sure you have all the libraries mentioned in Built With section installed; If not first run your environment then use the following commands:
+ Numpy:
  ```console
  pip install numpy
  ```
+ Pandas:
  ```console
  pip install pandas
  ```
+ Matplotlib:
  ```console
  pip install matplotlib
  ```
+ Scikit-Learn:
  ```console
  pip install scikit-learn
  ```
+ OpenCV:
  ```console
  pip install pandas
  ```
3. Download the following required files:
   + For project #1: housing.csv
   + For project #2: haarcascade_frontalface_default.xml
   + For project #4: bird.png

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Contact
Mohammad Mofidi
* Email: mohammad.mofidi.k@gmail.com
* Linkedin: https://www.linkedin.com/in/mohammad-mofidi-khajeh-2715832b8/
* Instagram: https://www.instagram.com/_mohammadmofidi/










