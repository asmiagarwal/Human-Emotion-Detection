# Human-Emotion-Detection
This project focuses on detecting human emotions from images using the Emotic dataset. The goal is to classify images into different emotional categories, allowing for a better understanding of human affective states in visual data.

# Dataset
The Emotic dataset is a large-scale dataset containing images labeled with both categorical and continuous emotion labels. It includes annotations for 26 different emotional categories, making it a comprehensive resource for training emotion detection models.

# Dataset Structure
Images: Real-world images featuring people in various contexts.
Labels: Each image is annotated with multiple emotion categories (e.g., happy, sad, angry) and continuous values for valence, arousal, and dominance.
# Preprocessing
Before training the models, the images are resized, normalized, and augmented to improve model generalization.

# Model
The project explores various deep learning models, including:
1. Convolutional Neural Networks (CNNs): For feature extraction from images.
2. Pre-trained Models: Such as ResNet, VGG, or EfficientNet, fine-tuned for emotion detection.
3. Multi-label Classification: Since each image can be associated with multiple emotions.
