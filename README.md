# Multimodal Emotion Recognition using Deep Learning  

## Overview  
This project aims to classify emotions from text, audio, and video data using deep learning and feature fusion techniques.  

## Tech Stack & Tools  
- **Text Processing:** DistilBERT, RoBERTa  
- **Audio Processing:** Librosa, Noise Reduction (`noisereduce`)  
- **Video Processing:** OpenCV, LSTMs, CNNs  
- **Modeling:** MLPClassifier, Logistic Regression  
- **Libraries:** TensorFlow, PyTorch, Transformers, Scikit-learn  

## Dataset  
- Emotion-labeled video clips with corresponding text and audio features  
- Extracted from a dataset used in the **ML Hackathon EC Campus Set 2**  

## Approach  
1. **Feature Extraction:**  
   - Tokenized text using transformer models  
   - Processed audio signals and reduced noise  
   - Extracted video frames and applied CNN-LSTM models  
2. **Early Fusion Model:**  
   - Combined text, audio, and video features  
   - Trained using MLPClassifier and Logistic Regression  
3. **Evaluation:**  
   - Accuracy and F1-score analysis  


