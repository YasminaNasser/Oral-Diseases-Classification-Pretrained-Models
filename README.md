# Oral-Diseases-Classification-Pretrained-Models

This project explores the application of **transfer learning** for classifying **7 types of oral diseases** using various pretrained convolutional neural networks (CNNs). The goal is to evaluate the performance, efficiency, and accuracy of different architectures on a medical image classification task.

---

## Models Compared

The following pretrained models (with `imagenet` weights) were fine-tuned and evaluated:

- **MobileNetV2**
- **ResNet50**
- **InceptionResNetV2**

---

##  Key Results

- **MobileNetV2** achieved the **highest validation accuracy**  
-  MobileNetV2 also converged in **fewer epochs** and with **shorter training steps**  
- Other models (e.g., InceptionResNetV2) showed strong accuracy but at higher computational cost

---

##  Target Disease Classes

The models classify input oral images into the following 7 categories:

- **CaS** – Candidiasis  
- **CoS** – Coated Tongue  
- **Gum** – Gum Inflammation  
- **MC** – Mucocele  
- **OC** – Oral Cancer  
- **OLP** – Oral Lichen Planus  
- **OT** – Other / Unspecified  

---

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- Matplotlib / Seaborn
- Kaggle(GPU)

---
