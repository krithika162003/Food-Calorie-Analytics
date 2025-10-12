# 🍽️ Food-Calorie-Analytics

## 📘 Abstract
Our project introduces a **novel approach to food calorie analytics** by integrating advanced computer vision models — **EfficientNetB3** for food classification and **YOLOv8** for food detection and segmentation.  
With the rising prevalence of diet-related health concerns, accurately assessing the caloric content of food has become increasingly important. Traditional methods often rely on manual estimations or simplistic algorithms, leading to inaccuracies.

To address this, our system employs:
- **EfficientNetB3** for feature extraction and image classification  
- **YOLOv8** for precise food segmentation and localization  
- A **calorie mapping CSV file** to compute caloric values based on detected food items  

Through extensive experimentation on diverse food datasets — with a focus on **Indian cuisine** — our approach achieves **high accuracy and efficiency**, outperforming conventional calorie estimation methods.

---

## 🧠 Model Summary

### 🔹 EfficientNetB3 Model (Classification)
The food image classification model is developed using **transfer learning** with the **EfficientNetB3** architecture as the backbone.  
Additional layers such as **Batch Normalization**, **Dense**, and **Dropout** layers are added to enhance performance.

**Key Features:**
- Classifies food images into **20 distinct categories**  
- Optimized for **accuracy and generalization**  
- Fine-tuned using a balanced Indian food dataset  
- Uses transfer learning for faster convergence and improved performance  

---

### 🔹 YOLOv8 Model (Detection & Segmentation)
**YOLOv8**, the latest evolution in the YOLO series, provides **state-of-the-art performance** in real-time object detection tasks.  
It accurately identifies and localizes food items within images or videos, enabling calorie estimation with high precision.

**Key Features:**
- Real-time **object detection and segmentation**  
- High inference speed and accuracy  
- Deep convolutional network for precise boundary detection  
- Suitable for diverse visual environments and datasets  

---

## 📂 Data Acquisition
**Dataset Link:** [Google Drive Dataset](https://drive.google.com/file/d/1H9hEnBR7hicROM3iKbb6fAW7HC7dP1aX/view?usp=drive_link)

The dataset consists of **20 Indian food categories**, each containing approximately **200 images**.  
Every category is stored in a separate directory, simplifying preprocessing and model training.  
Calorie values are mapped to these classes using a dedicated **CSV file** (`calorie_16.csv`), enabling calorie estimation for each recognized food item.

**Dataset Highlights:**
- 20 Indian food classes  
- ~200 images per class  
- Balanced and diverse image samples  
- Calorie mapping integrated for real-world estimation  

---

## 📊 Model Results & Evaluation
The project includes:
- **Classification Report**
- **Performance Metrics**
- **Accuracy/Loss Curves**
- **Evaluation Graphs**

These collectively provide a comprehensive view of the model’s accuracy and effectiveness across multiple food categories.

*<img width="414" height="403" alt="Screenshot 2025-09-29 203909" src="https://github.com/user-attachments/assets/dc40a792-5578-4ea9-9a19-70fd8a84ced3" />


<img width="684" height="194" alt="Screenshot 2025-09-29 203828" src="https://github.com/user-attachments/assets/917d3acb-6631-41a6-8124-37a32d3be5fe" />



<img width="1523" height="683" alt="Screenshot 2025-09-29 203805" src="https://github.com/user-attachments/assets/1bd44c55-2887-438e-9691-fa14f106f600" />*



---

## 🧾 Conclusion
Our project represents a significant advancement in the field of **food recognition and calorie prediction** using image processing.  
By leveraging **YOLOv8** and **EfficientNetB3**, we developed a robust system capable of accurately:
- Identifying food items in images  
- Predicting their calorie content efficiently  

This integration of detection, classification, and calorie computation paves the way for smarter, AI-powered dietary tracking systems.

---

## 🚀 Future Scope
Future enhancements could include:
- Integration of **additional nutritional information** beyond calories (e.g., protein, carbs, fats)  
- Development of a **mobile or web-based interface** for real-time food calorie analysis  
- Expansion to **multi-cuisine global datasets**  
- Integration with **health tracking applications** and **IoT-based diet monitoring systems**  

---

## 🧑‍💻 Details
- **Project Name:** Food-Calorie-Analytics   
- **Models Used:** EfficientNetB3, YOLOv8  
- **Frameworks:** TensorFlow, PyTorch, OpenCV  
- **Dataset Focus:** Indian Food Classification  

---

## 🛠️ Tech Stack
- **Languages:** Python  
- **Libraries:** TensorFlow, PyTorch, OpenCV, NumPy, Pandas, Matplotlib  
- **Models:** EfficientNetB3, YOLOv8  
- **Environment:** Jupyter / Google Colab  

---
