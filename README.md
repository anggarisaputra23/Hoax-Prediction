# HOAX PREDICTION USING RANDOM FOREST, LSTM, & TRANSFORMER BERT PRETAINED MODEL


 --- 

**Introduction**
1. In the digital era, the rapid spread of misinformation and hoaxes has become a significant threat;
2. Indonesia, with one of the world’s largest populations of internet users;
3. The Ministry of Communication and Informatics (Kominfo) reported handling approximately 12,547 instances of misinformation from August 2018 to the end of 2023. (https://heaptalk.com/govact/kominfo-addresses-12547-instances-of-misinformation-until-the-end-of-2023)
4. Hoaxes in Indonesia often intersect with sensitive topics such as politics, religion, and public health, making their impact far-reaching and potentially destabilizing.

 --- 

 **Data used**
1. The dataset utilized in this study is sourced from the research conducted by I. Y. R. Pratiwi, R. A. Asmara, and F. Rahutomo, which is publicly available on Mendeley Data (https://data.mendeley.com/datasets/p3hfgr5j3m/1). 
2. The dataset comprises a total of 822 Indonesian news articles, each annotated with a binary label indicating whether the content is classified as a hoax or non-hoax. 
3. For ease of access and integration with machine learning workflows, the dataset was retrieved via the Hugging Face platform "pauwdanny/indonesian_hoax_news_dataset".
4. The data is structured in a tabular format, typically including fields which are content (in English), and corresponding hoax label, allowing for effective preprocessing and model training in a supervised learning framework.
 --- 

 **Model Saved**
 You could use the model saved in this repository or use the trasnformer model which has been finetuned and accessed it through huggingface. The models are anggari/xlmroberta, anggari/hoax_bert, anggari/indobert.

 ---

 **Model Preformance**
 ![image](https://github.com/user-attachments/assets/1fba4fc8-7f30-40e5-a0ac-11d487e020cb)
