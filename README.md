# Handwritten Equation Solving Deep Learning Model

This project consists of a deep learning model that evaluates handwritten equations from input images and solves them.

## Dataset

The dataset used for training the DL model in this project is a subset of the chrome dataset and has the following characteristics:

- Dataset consists of 28 x 28 jpg image files.
- For feasibility, only 0 to 9 number and "+", "-" & "×" character images are taken in consideration for training the model in this project.
- After evaluation of the dataset, a bias is found for some numbers and characters, and thus to remove it, the number of images for each number are reduced to around 4000 (in contrast to original 12000 images for numbers and 3000 images for characters).
- Link : [Kaggle Dataset](https://www.kaggle.com/xainano/handwrittenmathsymbols)

## Model Summary

![Model Summary](https://raw.githubusercontent.com/gohil-jay/Handwritten-Equation-Solving-DL-Model/main/assets/Model.png)

## Model Details

- Identification of Handwriting : OpenCV
- Detection of Digits : CNN model
- Activation Functions : ReLU and Softmax
- Loss Function : Categorical Crossentropy

## Model Training

![Model Training](https://raw.githubusercontent.com/gohil-jay/Handwritten-Equation-Solving-DL-Model/main/assets/Model%20Training.png)

## Model Result

![Model Result](https://raw.githubusercontent.com/gohil-jay/Handwritten-Equation-Solving-DL-Model/main/assets/Model%20Result.png)

![Model Output](https://raw.githubusercontent.com/gohil-jay/Handwritten-Equation-Solving-DL-Model/main/assets/Model%20Output.png)

## Tutorial References

- [Deep Learning](https://www.youtube.com/playlist?list=PLZoTAELRMXVPGU70ZGsckrMdr0FteeRUi)
- [Activation Functions](https://www.youtube.com/watch?v=qVLQ9Cqm-ec)
- [Loss Function](https://www.youtube.com/watch?v=e59u5YyuEfQ&t=1600s)
- [Optimisers](https://www.youtube.com/watch?v=TudQZtgpoHk)

## Code References

- [Handwritten Expression Evaluation by Jose Joy](https://github.com/JoseJoy249/Handwritten-Expression-Evaluation)
- [Handwritten Equation Solver by Vipul](https://github.com/vipul79321/Handwritten-Equation-Solver)

## Literature References

- Guyon, I., Henderson, D., Albrecht, P., Lecun, Y., & Denker, J. S. (1992). Writer independent and writer adaptive neural network for on-line character recognition. In S. Impedovo, & J. C. Simon (Eds.), From pixels to features III: Frontiers in handwriting recognition (pp. 493-506). Elsevier. https://nyuscholars.nyu.edu/en/publications/writer-independent-and-writer-adaptive-neural-network-for-on-line
- Wang, P.S.P., M.V. Nagendraprasad and A. Gupta (1991). A 'hybrid' approach to handwritten numerical recognition. Proc. 2nd Internal. Workshop on Frontiers in handwriting Recognition, Bonas, France, 199l, 101-110.
- Kimura, F. and M. Shridhar (1991). Handwritten numerical recognition based on multiple algorithms. Pattern Recognition 24 (10), 969-983. https://www.sciencedirect.com/science/article/abs/pii/003132039190094L
