Automatic Image Caption Generator

This repository contains code for an automatic image caption generator implemented using deep learning techniques. The code is provided in a Jupyter Notebook format and demonstrates the end-to-end process of building and training a model to generate captions for images.

Features:

Image Feature Extraction: Utilizes a pre-trained VGG16 convolutional neural network (CNN) to extract meaningful features from images. These features serve as input to the caption generation model.

Text Preprocessing: Cleans and preprocesses caption text data, including tokenization, padding sequences, and adding start and end tags.

Model Creation: Constructs an image captioning model with an encoder-decoder architecture. The encoder utilizes the extracted image features, while the decoder employs LSTM layers to generate captions.

Model Training: Trains the model using the extracted image features and preprocessed captions. The training process involves optimizing the model's parameters to minimize a specified loss function.

Model Evaluation: Evaluates the trained model's performance using BLEU scores, a metric commonly used in natural language processing tasks, to compare generated captions with actual captions.

Real-Time Testing: Demonstrates how the trained model can be used to generate captions for real-time images captured through a webcam.

Usage:

Clone the repository:

bash
Copy code
git clone https://github.com/username/automatic-image-caption-generator.git
cd automatic-image-caption-generator
Install the required dependencies:

Copy code
pip install -r requirements.txt
Open and run the Jupyter Notebook Automatic Image Caption Generator.ipynb to explore the code, execute different cells, and understand the process of building and training the image captioning model.

Dependencies:

TensorFlow
Keras
NumPy
tqdm
nltk
Contributing:

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.
