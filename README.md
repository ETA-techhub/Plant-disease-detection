# Plant-disease-detection 🌿🔬

This repository contains Python implementations for detecting plant diseases using deep learning techniques. The focus is on improving classification accuracy and enhancing training datasets using advanced augmentation methods like Generative Adversarial Networks (GANs).

## 📁 Project Structure

- `cassava_test_folder.py`:  
  Performs basic classification of cassava leaf diseases using a CNN model. This script includes data preprocessing and model evaluation.

- `cassava_test_tuned.py`:  
  An optimized version of the test script, incorporating model tuning, regularization, and improved performance metrics.

- `gan_to_enlarge_training_data.py`:  
  Implements a GAN-based approach to augment the training dataset by generating synthetic plant leaf images, improving model robustness.

## 🧠 Key Technologies

- Convolutional Neural Networks (CNN)
- Generative Adversarial Networks (GAN)
- TensorFlow / Keras / PyTorch (based on implementation)
- Image augmentation and preprocessing techniques

## 📊 Datasets

This project uses the **Cassava Leaf Disease Dataset**. The dataset includes images labeled with different types of cassava plant diseases. For optimal results, ensure your dataset is properly structured and preprocessed before training.

## 🚀 Future Improvements

- Incorporate fine-grained GANs for localized augmentation
- Expand support to other crops (e.g., tomatoes, grapes)
- Real-time prediction using Edge AI devices (e.g., ESP32 + camera module)

## 📄 License

This project is open-source and available under the MIT License.

---

Would you like me to tailor this description more specifically to your dataset or add any citations/acknowledgments?
