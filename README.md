# Mental-Health-Status-Classification-using-Long-Short-Term-Memory--LSTM--and-Bidirectional-LSTM

## 📌 Overview
This project focuses on **classifying mental health statuses** of individuals based on their textual statements into one of seven categories:  

- Normal  
- Depression  
- Suicidal  
- Anxiety  
- Stress  
- Bi-Polar  
- Personality Disorder  

By leveraging **Natural Language Processing (NLP)** and **Deep Learning** techniques, this project aims to provide insights into mental health research and contribute to the development of intelligent systems, such as **early-detection chatbots** and **mental health support tools**.  

## ⚙️ Methodology
1. **Data Preparation**  
   - Load dataset from CSV  
   - Clean text using regex (remove URLs, special characters, etc.)  
   - Handle missing values  
   - Encode categorical labels  

2. **Feature Engineering**  
   - Tokenization with Keras `Tokenizer`  
   - Sequence padding with `pad_sequences`  

3. **Modeling**  
   - Neural network models built with **TensorFlow/Keras**  
   - Multi-class classification setup for 7 categories  

4. **Evaluation**  
   - Metrics: Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix to visualize misclassifications  
