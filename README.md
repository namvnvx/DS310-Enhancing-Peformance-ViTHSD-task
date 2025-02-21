# 🚀 Enhancing Performance in Hate Speech Detection for Vietnamese Social Media Texts  

## 📌 Overview  
This project focuses on improving **hate speech detection** in **Vietnamese social media texts**, addressing challenges such as **imbalanced multilabel data** and **text normalization**.  

## 📊 Data Processing  
- **Handling Imbalanced Data**: Techniques are applied to mitigate label imbalance in multilabel classification.  
- **Normalization**: The **ViLexNorm** dataset is used to standardize text before model training.  

## 🔬 Experiments and Results  
We evaluate **three approaches** to applying normalization and data augmentation:  
1. **Normalization only**  
2. **Augmentation first, then normalization**  
3. **Normalization first, then augmentation**  

## 🏆 Models Evaluated  
The following models were tested for performance comparison:  
- **Bi-GRU-LSTM-CNN** (Hybrid deep learning model)  
- **XLM-R** (Cross-lingual Transformer)  
- **ViSoBERT** (Vietnamese Social Media BERT)  
- **PhoBERT** (Pretrained Vietnamese BERT)  

📢 **Findings**: The results highlight how different preprocessing orders impact model performance, providing insights into optimizing hate speech detection for Vietnamese social media.  

---  
🔗 **Next Steps**: Further optimizations in text preprocessing and model tuning.  
