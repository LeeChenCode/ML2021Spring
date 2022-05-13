BERT - Bidirectional Encoder Representations from Transformers
===
### **Objectives**
  * Chinese Extractive Question Answering
    - Input: Paragraph + Question
    - Output: Answer
  * Learn how to fine tune a pretrained model on downstream task using transformers

### **Focused Knowledge/Keywords**
  * Network Models
    - BERT
    - MacBert
  
  * Automatic Mixed Precision
  * Learning Rate Decay
  * Gradient Accumulation
  * Text Pre/Postprocessing



### **Results**
| Model        | Public Score | Private Score |
|:-------------| :-----------:| :------------:|
| BERT         | 0.75858      | 0.77077       |
| MacBERT      | 0.82723      | 0.82979       |

    
### **Observations & Summaries**
  * NLP techniques will help to improve the accuracy with pre/post processing, you can check the result file to figure out any test processing needed
    e.g. [UNK] or empty text in the result

### **To-Do Enhancements**
  * Parameter Tuning 
  * Network Tuning 
  * Text Pre/Postprocessing


### **Reference**
  * [Slide and Sample Code](https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.html)
  * Github : 
      - [pai4451](https://github.com/pai4451/ML2021)
  * Articles for Implementation : 
    - [Francis Komizu](https://zhuanlan.zhihu.com/p/493772106)
    - [CSDN](https://blog.csdn.net/qq_39610915/article/details/119913009)
    - [Learning Rate Decay](https://huggingface.co/docs/transformers/main_classes/optimizer_schedules#transformers.get_polynomial_decay_schedule_with_warmup.num_training_steps)




