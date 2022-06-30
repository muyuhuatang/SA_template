# Template Codes for Senetiment Analysis Tasks


Recently, after attending the SICSS-2022, Singapore event, I noticed that many researchers from Social Science field are becoming more and more interested in applying the most welcomed and state-of-the-art AI models to help them dig out more insights from the Natural Lanugage Corpus.

However, the researchers from Social Science clusters may find difficult about how to apply and use the Transformer models like BERT from 0 to 1. 
Thus, for the convenience of the people who in need, I create the repo to make the most simple but very elastic illustration of how to apply the Transformer models like BERT to apply simple sentiment analysis through the most simple method :)

To provide a baseline for the BERT models, I applied the SVM (support vector machine) model at first.

Do note that, the dataset I used here is simply from Weseem(2016) and Latent Hatred(2021) paper, which is used for Hate Speech Detection task. The acc here is much higher than in the ordinary cases, based on my previous experiences, the BERT could achive around 80% acc in most sentiment analysis tasks, while the SVM model's acc is significantly lower. 

## SVM model

for the SVM model, the setting are really simple by the sklearn python library and TF-IDF based vectorization method. 

## BERT model

for the BERT model, I simply use the 'bert-based-uncased' version for the simplest example. 

for your convenience, I used the huggingface library and imported the auto-tokenizer and auto-model, which means that if you want to try out other models, you can just simply replace the model name of 'bert-base-uncased' to whatever your want (should be supported by huggingface library also) like 'roberta-large'. 

For reference, you can check out and search all the models in huggingface official website: 

https://huggingface.co/models


### Note

1. You can easily apply the provided codes in the ordinary google account in the free version of Google CoLab service (you do not need to charge for pro service), which is already providing very powerful GPUs to have a try

2. If you have any questions, please feel free to leave questions here, I will fix them once I saw them. :D



