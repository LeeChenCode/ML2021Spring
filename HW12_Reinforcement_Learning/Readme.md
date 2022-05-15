RL - Reinforcement Learning
===
### **Objectives**
  * Implement Deep Reinforcement Learning to achieve lunar landing task


 
### **Focused Knowledge/Keywords**
  * Network Models
    - Policy Gradient
    - Deep Q-Learning Network (DQN)
    - Actor-Critic 

  * Discount Accumulated Award
  * Advantage Function


### **Results**
| Public Score | Private Score |
| :-----------:| :------------:|
| N/A          | N/A           |

  * Test platform is not opened to non NTU course students

  * DQN Result

!<img width="378" alt="image" src="https://user-images.githubusercontent.com/102935839/168341817-fd2c3014-3129-4431-a911-be974429154f.png">
!<img width="379" alt="image" src="https://user-images.githubusercontent.com/102935839/168342170-01a730a8-4e61-4ab0-a712-05729d1f8ded.png">

  * Actor Critic Result
 
![image](https://user-images.githubusercontent.com/102935839/168480409-15a91549-4906-4722-a8f4-59ccf34b58fb.png)
![image](https://user-images.githubusercontent.com/102935839/168480430-358c085e-a236-4a49-9238-5cde8772c1fe.png)

  
  
### **Observations & Summaries**
  *  DQN has much better result at arounnd 500 batch training
  *  It's difficult to achieve convergence for policy gradient & actor-critic, need to fine-tune them further. 

### **To-Do Enhancements**
  * Fine tune policy gradient & actor-critic
  * Try other RL models ( A3C, Deul DQN, Rainbow, Deep Deterministic Policy Gradient...)


### **Reference**
  * [Slide and Sample Code](https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.html)
  * Github : 
      - DQN : [pai4451](https://github.com/pai4451/ML2021)
      - Actor-Critic : [nikhilbarhate99](https://github.com/nikhilbarhate99/Actor-Critic-PyTorch)
  * Articles for Implementation :
      - [Q-Learning](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html)
      - [Actor-Critic](https://blog.csdn.net/qq_34003876/article/details/107477426)



