
# 🧠 Depression Detection from Social Media Texts

**Project Title:** Detecting Signs of Depression from Social Media Texts  
**Institution:** University of Central Florida

---

## 📘 Overview

This project addresses the challenge of **automatically detecting signs of depression** in social media posts using advanced **Natural Language Processing (NLP)** techniques. Rather than relying on traditional machine learning methods, we fine-tuned a state-of-the-art transformer model (**RoBERTa-base**) to classify posts into three depression severity levels:

- Not Depressed  
- Moderately Depressed  
- Severely Depressed

Our aim is to contribute toward early intervention in mental health by detecting depressive cues in text-based digital interactions.

---

## 🛠️ Methodology

### 1. Model Choice: RoBERTa-base
RoBERTa is a robustly optimized version of BERT, trained on a large corpus including Common Crawl data. The model's architecture includes:

- 12 Transformer layers
- 110 million parameters
- Masked Language Modeling (MLM) task (no Next Sentence Prediction)
- Dynamic token masking during training

### 2. Data Preprocessing
- Removal of duplicates  
- Emoji demojization  
- Special character and noise cleaning

### 3. Training
Fine-tuning RoBERTa-base with:
- Hyperparameter tuning (learning rate, batch size, epochs, optimizer)
- Evaluation through precision, recall, F1-score
- Label distribution: not depressed, moderately depressed, severely depressed

### 4. Evaluation
Used classification reports to analyze the model's performance across all labels with metrics like:
- Accuracy
- Precision
- Recall
- F1-score

Baseline models compared:
- Support Vector Machine (SVM)
- Logistic Regression
- Naive Bayes
- Random Forest

RoBERTa outperformed all baselines in every major metric.

---

## 📊 Results

- **RoBERTa-based model outperformed** all baseline classifiers  
- Higher F1-scores across all three classes  
- Demonstrated robust understanding of nuanced emotional cues in informal social media text  
- Statistical analysis validated significant performance improvements

---

## 🔮 Future Scope

We propose extending the model beyond text to include **multimodal depression detection**, using:
- 🎥 Video (facial expression recognition)
- 🔊 Audio (voice tone & pitch analysis)

These extensions could further increase accuracy and context-awareness. Future goals include:
- Multimodal dataset integration  
- Privacy-preserving model deployment  
- Ethical bias mitigation in mental health tools

---

## 🧾 References
1. Yan Ding et al., Deep Integrated SVM for Depression Recognition  
2. Nafiz Al Asad et al., Social Media-based Detection via IEEE Conference  
3. A. Ahmed et al., Anxiety & Depression Detection using Supervised Learning  
4. Mandar Deshpande, Emotion AI for Depression  
5. Swati Jain et al., Suicidal Ideation Detection via ML  
6. Shahriar Saleque et al., MDD Detection via Signal Processing & ML

---

## 📬 Contact

📧 **manasakaranam6199@gmail.com**  


---

