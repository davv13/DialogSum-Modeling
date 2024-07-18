# **DialogSum Modeling**

#### We are going to work with `DIALOGSUM` dataset. DialogSum is a large-scale dialogue summarization dataset, consisting of 13,460 dialogues with corresponding manually labeled summaries and topics. 

## **Data Splits**  
- train: 12460  
- validation: 500  
- test: 500

## **Project Goal**
#### The aim is to construct a model which will predict topics (clustered) based on dialogue or summary or both. The task reduces to multiclass classification problem with target that has 20 classes. The model should make predictions on a test set (500 observations) that are included in the data. The topics are clustered into 20 clusters, you can find them in dialogsum_clustered.csv. 

### **Reference**
DialogSum dataset link: https://huggingface.co/datasets/knkarthick/dialogsum 


 