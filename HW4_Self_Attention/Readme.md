Self-Attention 
===
### **Objectives**
  * Multiclass Classification : predict speaker class from given speech
  * Learn to use transformer

 
### **Focused Knowledge/Keywords**
  * Network Models
      - Self-Attention
      - Transformer
      - Conformer
   
  * AM-Softmax

### **Results**
| Model        | Public Score | Private Score |
|:-------------| :-----------:| :------------:|
| Transformer  | 0.94166      | 0.94611       |
| Conformer    | 0.95595      | 0.95333       |

### **Observations & Summaries**
  * Much more layers/dimensions for the network will help to learn the relevance between each audio segment, 
    try to enlarge network depends on your CUDA memory size

### **To-Do Enhancements**
  * Parameter Tuning 
  * Network Tuning ( Transformer, Conformer )


### **Reference**
  * [Slide and Sample Code](https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.html)
  * Github : 
      - [Conformer](https://github.com/lucidrains/conformer)
      
  * Articles for Implementation : 
      - [Tom likes Jerry](https://blog.csdn.net/qq_43319080/article/details/120256218?spm=1001.2101.3001.6650.7&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7ERate-7.pc_relevant_default&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7ERate-7.pc_relevant_default&utm_relevant_index=12)
      - [Francis Komizu](https://zhuanlan.zhihu.com/p/439212197)


