GAN - Generative Adversarial Network
===
### **Objectives**
  * Anime Face Generation : Train your own anime face generator using Generative Adversarial Networks


 
### **Focused Knowledge/Keywords**
  * Network Models
    - GAN
    - DCGAN
    - WGAN-GP
    - SNGAN
    - StyleGAN

  * Loss Function
    - JS divergence
    - Wasserstein


### **Results**
| Public Score | Private Score |
| :-----------:| :------------:|
| N/A          | N/A           |

  * Test platform is not opened to non NTU course students

  * styleGAN2 result
![image](https://user-images.githubusercontent.com/102935839/168249220-11fcacf5-3f9a-4cbf-be29-0b687f791770.png)

  
  
### **Observations & Summaries**
  * It is possible to get mode collapse if you train generator in high frequency ( e.g. critic=1 )
  * styleGAN2 is much more effective to generate detail face features than other models   

### **To-Do Enhancements**
  * Parameter Tuning 
  * Network Tuning 


### **Reference**
  * [Slide and Sample Code](https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.html)
  * Github : 
      - [pai4451](https://github.com/pai4451/ML2021)
      - [StyleGan2](https://github.com/lucidrains/stylegan2-pytorch)
  * Articles for Implementation : 
    - [Francis Komizu](https://zhuanlan.zhihu.com/p/493013529)



