# Shadow-Localization-in-Thermal-imaging


## 📌 Project Overview
Shadow localization in thermal images is a deep learning-based project aimed at accurately detecting shadows in thermal imagery. Shadows can cause significant errors in various computer vision applications, such as thermal-based object detection and leakage detection systems. This project leverages convolutional neural networks (CNNs) to improve shadow detection accuracy and minimize misclassifications.
![image](https://github.com/user-attachments/assets/357e4ebb-e885-4a20-8b8c-7e01e0ae10ec)


## 🛠️ How It Works
The project involves training and evaluating three different deep learning models to segment shadows in thermal images:

1. **U-Net** : The initial model used for shadow detection. It provides a good baseline but struggles with misclassifications, particularly with dark regions such as the sky and ground.
2. **U-Net with Spatial Attention** : This improved version enhances the model's focus on shadow regions by adding spatial attention layers.
3. **U-Net++** : A more advanced architecture that refines the segmentation accuracy by incorporating a more complex nested skip connection structure.

### 📂 Dataset & Preprocessing
- Thermal images were annotated and preprocessed using the **Roboflow platform**.
- Additional input features, such as **edge map features and directional features**, were used to improve performance.
- A **multiclass labeling approach** was explored to distinguish between sky, shadow, and other regions, assigning **higher weight to shadows** during training.

## 📊 Model Performance
- The U-Net++ model showed the best performance in accurately localizing shadows. ✅
- Spatial attention helped reduce false positives in darker non-shadow areas. 🎯

## 🔗 Accessing the Models & Code
Due to large file sizes, the trained models are not uploaded to GitHub. You can access them via the following Google Drive link:

**https://drive.google.com/drive/folders/1jwSzYfx3MMwLIII5FDqSA4237P4xdlfI**  🌐

## 🖼️ Screenshots
 screenshots of the model outputs, dataset, and training process are available in the repository. These images provide a visual understanding of how the models perform shadow localization!
![image](https://github.com/user-attachments/assets/1612ff2d-4e1b-4885-8147-b87a19d847a5)


## 🌍 Real-World Application
This project was developed to address real-world shadow detection issues faced by **NorAlta** in their leakage detection model. Improved shadow localization enhances the accuracy of their thermal-based analysis, preventing errors caused by shadows. 🏭

## 🚀 Future Work
- Implementing additional **post-processing techniques** to refine segmentation results. 🛠️
- Exploring **semi-supervised learning** to improve performance with limited labeled data. 📈
- Expanding the dataset to include **more diverse shadow conditions**.

  
## 👨‍💻 Contributors
- **Parth Patel** ([GitHub](https://github.com/patelparth2401))
- **Kushal ShahPatel** ([GitHub](https://github.com/kushal600))


