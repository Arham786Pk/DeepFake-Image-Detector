DeepFake Image Detector
This project is designed to detect DeepFake images using deep learning. It takes an input image, processes it, and predicts whether the image is Real or Fake with a confidence score.

Key Features
✅ Uses ResNet-50 – A deep convolutional neural network (CNN) known for strong image classification capabilities.
✅ Pre-trained on ImageNet – Leverages pre-learned features for better accuracy.
✅ Fine-Tuned for DeepFake Detection – Modifies the final layers for binary classification (Real vs. Fake).
✅ Data Augmentation – Applies transformations like flips, rotations, and color jittering for robustness.
✅ Training & Validation – Uses an 80-20 dataset split to improve model generalization.
✅ Gradio Web Interface – Allows users to upload images and get predictions in real-time.

How It Works
Preprocess Image – Resizes and normalizes input images.
Model Prediction – Uses a fine-tuned ResNet-50 model to classify the image.
Confidence Scores – Provides probabilities for Real and Fake categories.
Visualization – Displays analyzed image and prediction results.
This tool helps in identifying AI-generated images and can be used for research, security, and media verification. 🚀
