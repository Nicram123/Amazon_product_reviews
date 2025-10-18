# Amazon Product Reviews (NLP Project)

Here you can find a complete deep learning project focused on **Natural Language Processing (NLP)**.  
The goal of this project is Classification of reviews as negative (0) or positive (1) using available training data.

The project has three main parts:

1. **Text Preprocessing and Tokenization**  
2. **Embedding and Feature Representation**  
3. **Model Training and Evaluation**

---

## 🧩 Stack

**Pandas**, **NumPy**, **Matplotlib**, **Scikit-Learn**, **TensorFlow**, **TensorFlow Hub**

---



### Example visualizations (placeholders):

- **Question length distribution**  
<img width="532" height="353" alt="image" src="https://github.com/user-attachments/assets/dc78659a-317f-4c8a-b54d-ce73c116ecdb" />
  
- **Most frequent reviews**  
<img width="525" height="427" alt="image" src="https://github.com/user-attachments/assets/7c07cb82-8f04-40cc-a0ea-52e1e6cffed9" />
  
- **K-means clustering for reviews**  
<img width="761" height="442" alt="image" src="https://github.com/user-attachments/assets/1fb078df-966f-4876-9b19-00f5fc8f4fe4" />

---

## 🧠 Models use
1. Pipeline (Model 0): Uses TfidfVectorizer and Logistic Regression for text classification.
2. Char-level CNN with Embedding (Model 1): Uses TextVectorizer, embedding, Conv1D, and GlobalAveragePooling1D for character-level text classification.
3. Sentence Encoder (Model 2): Uses a pre-trained sentence encoder from TensorFlow Hub for sentence-level text classification.
4. Char-level CNN (Model 3): Uses char_vectorizer, char_embed, and Conv1D for character-level text classification.
5. Char-level + Token-level CNN (Model 4): Combines character-level and token-level features using Conv1D for text classification.

##Results:
Model 0 (Pipeline) achieved the best results.

##Next Steps:
Generated summaries of reviews using a generative approach.
Performed KMeans clustering to identify themes and trends in reviews.
Conclusion:

--- 

The Pipeline model with TfidfVectorizer and Logistic Regression performed best.
Model 4, which combined character-level and token-level features, also achieved high accuracy.

