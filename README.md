# Explainable-Clinical-NLP-Pipeline-using-BioClinicalBERT-  

##  Project Overview  
This project explores how **Natural Language Processing (NLP)** can be applied to **classify clinical notes into disease categories**.  
The work combines both **baseline ML models** and **state-of-the-art transformer models** while focusing on **data preprocessing, interpretability, and usability**.  

Key outcomes include building an end-to-end pipeline, applying domain-specific text cleaning, experimenting with transformer-based models (BioClinicalBERT), and deploying an **interactive Gradio app** for real-time predictions.  

---

## Key Features  
- **End-to-End NLP Pipeline**  
  Built baseline TF-IDF + Logistic Regression and advanced transformer-based BioClinicalBERT for disease classification.  

- **Healthcare-Specific Preprocessing**  
  Applied **PHI removal** and **medical abbreviation expansion** to improve data quality and make predictions more reliable.  

- **Model Explainability**  
  Integrated **LIME** and **attention visualizations** to provide interpretable predictions for clinical end-users.  

- **Interactive Dashboard**  
  Deployed a **Gradio-based UI** where users can input clinical notes and receive predicted disease categories with explanations.  

---

## Dataset  
- Medical transcription dataset (publicly available).  
- Contains clinical notes with corresponding disease category labels.  
- Dataset required **de-identification (PHI removal)** for ethical usage.  

*(https://www.kaggle.com/datasets/tboyle10/medicaltranscriptions)*  

---

## Methodology  
1. **Data Preprocessing**  
   - Removed Protected Health Information (PHI).  
   - Expanded medical abbreviations using a curated dictionary.  
   - Tokenized and prepared text for both baseline ML and transformer-based models.  

2. **Modeling**  
   - **Baseline**: TF-IDF + Logistic Regression.  
   - **Transformer**: Fine-tuned BioClinicalBERT on the dataset.  

3. **Explainability**  
   - Used **LIME** for local explanations of Logistic Regression.  
   - Visualized **attention weights** for BioClinicalBERT predictions.  

4. **Deployment**  
   - Built a **Gradio dashboard** to allow clinicians/researchers to test predictions interactively.  

---

## Results  
- Logistic Regression provided a reliable baseline.  
- BioClinicalBERT captured clinical context more effectively.  
- The project demonstrates:  
  - How **modern NLP can be adapted for healthcare data**,  
  - The importance of **explainability** in medical AI, and  
  - Deployment of an end-to-end solution.  

---

## Tech Stack  
- **Python**  
- **Libraries**:  
  - PyTorch  
  - HuggingFace Transformers  
  - Scikit-learn  
  - LIME  
  - Gradio  
  - Pandas, NumPy, Matplotlib, Seaborn  


