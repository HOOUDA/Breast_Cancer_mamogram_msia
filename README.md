# Breast Cancer Detection  🐍
Breast cancer is a significant global health concern, and early detection plays a crucial role in improving patient outcomes. In recent years, there has been a growing interest in leveraging advanced technologies, such as Convolutional Neural Networks (CNNs), for the detection and diagnosis of breast cancer. Mammography, as one of the most common screening methods, provides detailed images of the breast tissue. The application of CNNs to mammogram analysis in Malaysia (MSIA) holds great promise for enhancing the accuracy and efficiency of breast cancer detection.

## Dataset 📚
we collect the data from [Kaggle](https://www.kaggle.com/datasets/kmader/mias-mammography) dataset .

The mini-MIAS database of mammograms .[Link](http://peipa.essex.ac.uk/pix/mias/)

## Why we used CNN 🤖
1-Pattern Recognition and Feature Extraction: CNNs are particularly effective at recognizing intricate patterns and extracting hierarchical features from images.

2-Adaptability to Diverse Image Characteristics: Breast tissue density and other characteristics can vary among populations. CNNs are adaptable and can be trained on diverse datasets, making them suitable for accommodating variations in breast tissue composition specific to the Malaysian population.

3-Early Detection Significance: Early detection of breast cancer is critical for successful treatment and improved patient outcomes.

4-Automation and Efficiency: CNNs enable automation of the breast cancer detection process, allowing for faster and more efficient screening of mammograms.

5-Large-Scale Data Processing: CNNs are capable of handling large datasets

6-Continuous Learning and Improvement: CNNs can be designed to continuously learn and improve over time.
## Results 📊

| version | traning accuracy | test accuracy | f1 score | recall  | precision | Total Parameters|
|--------|--------------|-------------|------------|----------|-------------|-------|
|ResNet50 | 0.99 | 0.963 | 0.96 |  0.96  |0.97|47,929,410|
| VGG19 |0.99|0.96|0.97|0.97|0.96 |47,929,410|
| VGG16 |0.99|0.96|0.96|0.97|0.96 |42,619,714|


