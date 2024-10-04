# Melanoma Detection using Custom CNN

This project uses a custom Convolutional Neural Network (CNN) to detect melanoma in images of skin lesions among 10 classes. The **Gradio** library is used to create an interactive web app for model prediction. The model achieves an **87% accuracy** in classifying the skin lesions.

## Table of Contents
- [General Information](#general-information)
- [Algorithms Used](#algorithms-used)
- [Dataset Information](#dataset-information)
- [Steps Involved](#steps-involved)
- [Results](#results)
  - [Baseline Model](#baseline-model)
  - [Augmented Model](#augmented-model)
  - [Final Model](#final-model)
- [Conclusion](#conclusion)
- [Technologies Used](#technologies-used)
- [Contact](#contact)
- [License](#license)

## General Information

This project aims to classify different types of skin lesions to detect melanoma using deep learning. It uses a **custom CNN architecture** and tackles challenges such as **class imbalance** by augmenting data and using various image preprocessing techniques. The project also demonstrates the use of **Gradio** to deploy the trained model as a simple web interface.

## Algorithms Used
- **Convolutional Neural Network (CNN)**: A custom CNN architecture is used for feature extraction and classification of skin lesion images.

## Dataset Information

The dataset consists of **2357 images** of various skin conditions, both malignant and benign. These images are provided by the **International Skin Imaging Collaboration (ISIC)**. The dataset includes the following classes:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

The dataset is slightly imbalanced, with **melanomas** and **moles (nevi)** having a dominant number of images compared to the other classes.

## Steps Involved
1. **Data Loading**
2. **Baseline Model Building**: Construct the initial CNN model.
3. **Training and Testing the Baseline Model**
4. **Building an Augmented Model**: Add data augmentation techniques to improve generalization.
5. **Training and Testing the Augmented Model**
6. **Countering Class Imbalance with Augmentor**: Apply image augmentation specifically to balance class distribution.
7. **Building the Final Model**: Construct the final model after incorporating augmentation strategies.
8. **Training and Testing the Final Model**
9. **Verifying the Model**: Ensure model accuracy and performance on unseen data.

## Results

### Baseline Model
- The baseline model provides initial accuracy and loss metrics.
- ![Baseline Model Results](path/to/baseline_model_image.png) <!-- Replace with actual image path -->

### Augmented Model
- Data augmentation was applied to improve the model’s robustness.
- ![Augmented Model Results](path/to/augmented_model_image.png) <!-- Replace with actual image path -->

### Final Model
- The final model, incorporating all improvements, achieved **87% accuracy** and a **loss of 0.3**.
- ![Final Model Results](path/to/final_model_image.png) <!-- Replace with actual image path -->

## Conclusion
As the model's accuracy increased, the loss consistently decreased. The final model achieved **83% accuracy** and a loss of **0.5**. By augmenting the data and addressing class imbalance, the model's performance was significantly improved. The model is highly effective in predicting the class of skin lesions with high accuracy.

## Technologies Used
- **Python**
- **TensorFlow**
- **Keras**
- **Augmentor**
- **Matplotlib**
- **NumPy**
- **Gradio** (for the web app interface)

## Contact
Created by [@sanchitapatil](https://github.com/sanchitapatil) - feel free to contact me for any questions or collaboration opportunities!

## License
This project is open-source and available under the [MIT License](LICENSE).
