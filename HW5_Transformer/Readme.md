Transformer
===
### **Objectives**
  * Neural Machine Translation : translate from english to traditional chinese


 
### **Focused Knowledge/Keywords**
  * Network Models
      - Recurrent Neural Network (RNN)
      - Transformer

  * Back Translation(BT)
  * BLEU

### **Results**
| Public Score | Private Score |
| :-----------:| :------------:|
| N/A          | N/A           |

  * Test platform is not opened to non NTU course students

  * BLEU Score:
    - RNN : 19.17
    - Transformer : 23.45
    - Transformer with back translation : 24.81
  
  
### **Observations & Summaries**
  * Back Translation is effective and you can see it obviously improves the BLEU score since early epoch
  * It is still diffcult problem to think about how to further enhance the quality of translation
    - e.g. fund will be translated to "資金", but "社會捐款" may be better translation in the paragraph.  

### **To-Do Enhancements**
  * Parameter Tuning 
  * Network Tuning 
  * How to improve the quality of translation


### **Reference**
  * [Slide and Sample Code](https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.html)
  * Github : 
      - [pai4451](https://github.com/pai4451/ML2021)
      



