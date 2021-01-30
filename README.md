# Captcha Detection
The following code has been designed to add numbers in a given Captcha consisting of numbers. The model has been first trained on MNIST digit dataset. Then using the trained model, we run this on detected digits and add them. To detect the numbers we use several classical CV concepts such as erosion, contour detection,etc.

## Installation
To run the code, you must have the following libraries present:
+ `pytorch >= 1.0`
+ `opencv < 4.0`
+ `numpy`
+ `torchsummary`
## Run
To run just start the notebook. The path of datasets should be set accordingly. Code will be ported into scripts shortly
## Evaluation
Evaluation on the entire dataset after 50 epochs gives us an accuracy of 68%
## Plots
### Loss Plots :   
![](https://github.com/darthgera123/Captcha-Detection/blob/main/plots/lossplots.png)
### Accuracy Plots :  
![](https://github.com/darthgera123/Captcha-Detection/blob/main/plots/accuracyplots.png)
