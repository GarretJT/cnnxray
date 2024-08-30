**IMPLEMENTATION OF CONVOLUTIONAL NEURAL NETWORK (CNN) FOR CLASSIFICATION OF ILLEGAL ITEMS IN BAGGAGE X-RAY IMAGES**

Objective: 
The goal of this study is to develop and evaluate a Convolutional Neural
Network (CNN) model for enhancing the efficiency and accuracy of baggage X-ray
screening at airports. By leveraging deep learning technology, the aim is to reduce
passenger wait times and improve flight security with a high-accuracy model.

Dataset: 
The dataset used, DvXray, consists of 16,000 pairs of X-ray images, totaling
32,000 baggage X-ray images. This dataset includes 16,000 top-view baggage X-ray
images and 16,000 side-view baggage X-ray images. Each image is labeled with the
presence of illegal items and includes bounding box coordinates for each detected
item. The dataset can be accessed from the official GitHub repository here: https://github.com/Mbwslib/DvXray.

Methods: 
Preprocessed X-ray images by converting them to grayscale and resizing to
150 x 150 pixels. Flattened the images into one-dimensional vectors. Applied SVM with
various kernels (RBF, Linear, Poly, Sigmoid) for classification.

Results: 
With simple preprocessing and model architecture, the CNN model achieved a
high accuracy of 92.01% in binary classification of baggage X-ray images for illegal
items.
- Training Metrics
Loss: 0.11
Accuracy: 95.80%
- Validation Metrics:
Loss: 0.29
Accuracy: 91.36%

Conclusion: This study demonstrates the effectiveness of Convolutional Neural
Networks (CNNs) in classifying illegal items in baggage X-ray images with a high degree
of accuracy. The CNN model achieved an impressive 92.01% accuracy in distinguishing
between images containing illegal items and those that do not.
Furthermore, to mitigate overfitting observed during initial experiments, dropout
layers were introduced, although further optimization is recommended. Additionally,
the incorporation of bounding boxes is suggested to improve model performance by
enabling precise localization of illegal items within images. This supervised approach
could potentially reduce noise and enhance the model's ability to accurately predict
illegal items.
