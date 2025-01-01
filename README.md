# SignAI
This solution detects ASL alphabet using Python, TensorFlow, Keras, and Mediapipe. The model is a Convolutional Neural Network (CNN) trained to classify grayscale images of hand signs representing the 24 letters of the ASL alphabet (excluding J adn Z) using dataset at https://huggingface.co/datasets/Marxulia/asl_sign_languages_alphabets_v03. The CNN consists of two 1D convolutional layers, each followed by dropout layers, then flattened and connected to dense layers, with a final softmax layer for multi-class classification.

### Install packages
` !pip install -r requirements.txt `

### Requirements
A camera for real time detection. 
