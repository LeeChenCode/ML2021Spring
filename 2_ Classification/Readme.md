Classification
===
### **Objectives**
  * Phoneme Classification : train a deep neural network classifier to predict the phonemes for each frame from the speech corpus TIMIT
 
### **Focused Knowledge/Keywords**
  * Deep Neural Networks for classification
  * Loss Function (Cross Entropy...)
  * Activation Function (Relu,Sigmoid,LeckyRelu...)
  * Optimizer (SGD, adam…)
  * Normalization(Batch Normalization, Dropout) / L2 Regularization 
  * Parameters/Network Tuning

### **Results**
| Public Score | Private Score |
| :-----------:| :------------:|
| 0.74934      | 0.74925       |

### **Observations & Summaries**
  * Enlarge network improves the accuracy significantly, recommmend to modify it first
  * Small batch size may get better gradient as the larger difference between batches
  * Batch Normalization/ Dropout / L2 Regularization improve the overfitting problem
  * Shrink the validation set ratio improves the accuracy as more data is used for training

### **To-Do Enhancements**
  * Parameter Tuning ( epoch, learning rate... )
  * Network Tuning ( layers, dimension...)


### **Reference**
  * [Slide and Sample Code](https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.html)
  * Articles for Implementation : 
      - [CSDN](https://blog.csdn.net/weixin_43154149/article/details/122174123?spm=1001.2101.3001.6650.1&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1.pc_relevant_default&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1.pc_relevant_default&utm_relevant_index=2)
