# ML-CEP
Project made for Machine Learning course, which compares the performance of different Machine Learning models on performing binary classification.
The dataset used is the CIFAR-10 dataset on which binary classification is performed between animal and vehicle classes. The 10 original classes of the dataset were pre processed to be binned into 2 classes animal and vehicle.

The Machine Learning models used are:
    1. Logistics Regression
    2. XGBoost (eXtreme Gradient Boosting)
    3. CNN (Convolutional Neural Network)

The Logistics Regression model is used from the SKLearn library which is a parametric algorithm and is suitable for classification tasks especially binary classification.

The XGBoost model is used from xgboost library which is a non parametric algorithm. It uses ensemble learning techniques to improve the gradient in quick successions and hence achieves high accuracy.

The CNN model is used from PyTorch library named as torch and is dependent on related libraries such as torchvision and torcheval. It is a neural network which uses the defined network to optimize its neurons weights and values to produce the output with very high accuracies.

Other libraries used are Pandas, Numpy, PIL (Pillow Imaging Library) and OpenCV which are used for preprocessing and data handling.
