CNN - Convolutional Neural Network 
===
### **Objectives**
  * Solve food image classification with convolutional neural networks.
  * Improve the performance with data augmentations.
  * Understand how to utilize unlabeled data and how it benefits.

 
### **Focused Knowledge/Keywords**
  * Convolutional Neural Network 
  * Data Augmentation
  * Use unlabeled data for Semi-Supervised Learning
  * Pre-Trained Model : ResNet


### **Results**
| Public Score | Private Score |
| :-----------:| :------------:|
| 0.82437      | 0.81829       |

### **Observations & Summaries**
  * Enlarge network & Data Augmentation improves the accuracy significantly, recommmend to modify them first
  * Batch Normalization and Dropout improve the overfitting problem
  * Unlabeled data may be more effective for result improving, when model accuracy is good enough before use it for training
  * It's also effective to apply data augmentation on unlabeled data 

### **To-Do Enhancements**
  * Data Augmentation
  * Parameter Tuning ( epoch, learning rate with warmup... )
  * Network Tuning ( layers, dimension, other CNN models...)
  * Ensemble techniques


### **Reference**
  * [Slide and Sample Code](https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.html)
  * Github : 
      - [1am9trash](https://github.com/1am9trash/Hung_Yi_Lee_ML_2021/blob/main/hw/hw3/hw3_code.ipynb)
  * Articles for Implementation : 
      - [Francis Komizu](https://zhuanlan.zhihu.com/p/436809552)
      - [Torchvision Data Augmentation](https://chih-sheng-huang821.medium.com/03-pytorch-dataaug-a712a7a7f55e)

