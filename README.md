# Pneumonia Detection using Convolutional Neural Network

## Project Description :

This project uses Convolutional Neural Networks (CNN) to detect Pneumonia from chest X-ray images. The dataset is sourced from the Kaggle dataset "Chest X-Ray Images (Pneumonia)" by Paul Mooney.

## Dataset :

The dataset consists of X-ray images categorized into two classes:
  * **Normal**
  * **Pneumonia**

You can download the dataset from [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

## Usage : 

<> Create a virtual environment and activate it.

    python3 -m venv venv
    source venv/bin/activate

<>Install the required packages.

    pip install -r requirements.txt

<> Download the dataset and place it in the data/ directory and run the ipy notebook file.

## Model Architecture :

  The CNN model architecture consists of several convolutional layers, each followed by max-pooling layers, and finally dense layers for classification.
  
## Summary of the model :

* Conv2D layers with ReLU activation
* MaxPooling2D layers
* Flatten layer
* Dense layers with ReLU activation
* Output Dense layer with sigmoid activation for binary classification

<div justify-content='center'>
 <img src="https://github.com/sabariraj01/Pneumonia_Detection_Using-CNN/assets/114046096/558151fc-288f-408c-8887-af208e22fa1f" alt="Sample Output 1" width="400">
</div>


## Results :

* Training accuracy : 98.16%
* Validation accuracy : 100%
  
<img src="https://github.com/sabariraj01/Pneumonia_Detection_Using-CNN/assets/114046096/b88600e9-5f82-4f04-9790-87b03d533c62" alt="Confusion Matrix" width="400">

<img src="https://github.com/sabariraj01/Pneumonia_Detection_Using-CNN/assets/114046096/b4da5c98-620b-4800-b68c-4e1632c7e8f4" alt="ROC Curve" width="400">

## Sample Inputs :

<img src="https://github.com/sabariraj01/Pneumonia_Detection_Using-CNN/assets/114046096/a55ef14c-a1a5-4cf6-b482-daf526247939" alt="Sample Input" width="450">

## Sample Outputs : 


<img src="https://github.com/sabariraj01/Pneumonia_Detection_Using-CNN/assets/114046096/c5c68ba3-5a88-4724-8396-fac6be1adb97" alt="Sample Output 1" width="400">
<br>
<img src="https://github.com/sabariraj01/Pneumonia_Detection_Using-CNN/assets/114046096/e9a3eee3-3ac0-412d-bbb1-45c5446dcac3" alt="Sample Output 2" width="400">

