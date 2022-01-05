# Handwritten Equation Solving Deep Learning Model

This project consists of a deep learning model that evaluates handwritten equations from input images and solves them.

## Dataset

The dataset used for training the DL model in this project is a subset of the chrome dataset which can be found [here](https://www.kaggle.com/xainano/handwrittenmathsymbols) and has the following characteristics:

- Dataset consists of 28 x 28 jpg image files.
- For feasibility, only 0 to 9 number and "+", "—" & "×" character images are taken in consideration for training the model in this project.
- After evaluation of the dataset, a bias is found for some numbers and characters, and thus to remove it, the number of images for each number are reduced to around 4000 (in contrast to original 12000 images for numbers and 3000 images for characters).

