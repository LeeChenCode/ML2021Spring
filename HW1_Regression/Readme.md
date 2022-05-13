Regression
===
### **Objectives**
  * Solve a regression problem - COVID-19 Cases Prediction, with deep neural networks (DNN).
  * Understand basic DNN training tips
      e.g. hyper-parameter tuning, feature selection, regularization, ...
  * Get familiar with PyTorch
 
### **Focused Knowledge/Keywords**
  * Deep Neural Networks (DNN)
  * Activation Function (Relu,Sigmoid,Leckyrelu...)
  * Optimizer (SGD, adam…)
  * Loss Function (RMSE...)
  * Normalization(Batch Normalization, Dropout) / L2 Regularization 
  * Feature selection using sklearn f-regression
  * Parameters/Network Tuning

### **Results**
| Public Score | Private Score |
| :-----------:| :------------:|
| 0.89477      | 0.91152       |

### **Observations & Summaries**
  * Small batch size may get better gradient as the larger difference between batches
  * Normalization is effective for gradient descent convergence
  * Use feature selection to select high associated data columns is more effective on training than selecting all data
  * LeckyRelu improves dead neuron problem and further improves the accuracy

### **To-Do Enhancements**
  * Parameter Tuning ( learning rate... )
  * Network Tuning ( layers, dimension...)


### **Reference**
  * [Slide and Sample Code](https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.html)
  * Articles for Implementation : 
      - [Feature selection using sklearn f-regression](https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.html)
      - https://juejin.cn/post/7037420281543000072
