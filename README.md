# Artificial-Intelligence-Project
## Fracture Detection from X-ray Images using Vision Transformers (ViT)

This project leverages deep learning and state-of-the-art Vision Transformer (ViT) models to classify bone X-ray images as **fractured** or **healthy**. It is designed to assist in early diagnosis and medical image analysis using AI-based image classification.

---

## Project Overview

The model is trained on a dataset of labeled bone X-ray images. The images were preprocessed and classified using ViT-based architectures from the Hugging Face Transformers library.

-  Task: Binary Classification (Fractured / Healthy)
-  Model: `google/vit-base-patch16-224-in21k`
-  Data: Pre-classified X-ray images
-  Frameworks: PyTorch, Transformers, Datasets
-  Evaluation: Accuracy, Precision, Recall, F1, AUC

---

##  How It Works

1. **Preprocessing:**  
   - Images resized to 224×224 (ViT input format)  
   - Converted to RGB and normalized  

2. **Feature Extraction:**  
   - Used ViT, DeiT, Swin, Beit, ConvNext feature extractors from Hugging Face  

3. **Model Training:**  
   - Fine-tuned pre-trained ViT model on X-ray dataset  
   - Training done using `Trainer` API  

4. **Evaluation Metrics:**  
   - Accuracy  
   - Precision  
   - Recall  
   - F1-Score  
   - AUC  

---

##  Sample Images

> *Include a few examples from your dataset here if possible*  
> *(e.g. fractured vs. healthy X-rays)*

---

##  Results for model Vit (You can see all results in report directory)

| Metric      | Value     |
|-------------|-----------|
| Accuracy    | 63.8%     |
| Precision   | 51%       |
| Recall      | 97.5%     |
| F1 Score    | 67%       |
| AUC         | 70%       |


---

##  Key libraries used:

- transformers

- datasets

- scikit-learn

- torch

- Pillow

## Future Work

- Deploy as a web service with FastAPI or Streamlit

- Test on other medical imaging datasets


## Acknowledgements
- Hugging Face Transformers & Datasets
  
- PyTorch
  
- Open medical X-ray datasets

- Vision Transformer (ViT) by Google Research







