🚦 Traffic Sign Classification using CNN, VGG16, ResNet50, and DenseNet
This project focuses on recognizing traffic signs from the [German Traffic Sign Recognition Benchmark (GTSRB)] using deep learning models. The goal is to classify traffic signs into one of 43 categories using various architectures and data augmentation techniques.

📌 Overview
Processed and normalized over 39,000 labeled images of traffic signs into standard 32x32 RGB format.

Handled class imbalance using computed class weights to improve performance on minority sign classes.

Trained and evaluated multiple deep learning models including:

Custom CNN

VGG16 (pretrained)

ResNet50 (pretrained)

DenseNet121 (pretrained)

📊 Results Summary
Custom CNN achieved highest accuracy of 63.5%, effective for minority classes with less computational requirements.

VGG16 reached 60.2%, performed decently but required high GPU memory and training time.

DenseNet121 scored 58.3%, showed gradual improvement with better feature reuse and generalization.

ResNet50 underperformed with 51.7%, struggled with shallow input resolution (32x32) and limited training epochs.

🔧 Key Features
🧠 Deep learning architectures with transfer learning using ImageNet weights.

📈 Data augmentation with real-time image rotation, translation, and flipping using ImageDataGenerator.

⚖️ Class weighting strategy to address class imbalance.

📊 Evaluation with confusion matrix, classification report, and validation loss/accuracy curves.
