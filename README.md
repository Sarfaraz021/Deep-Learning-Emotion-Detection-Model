# Deep-Learning-Emotion-Detection-Model

This project aims to detect emotions from speech using deep learning models. The project includes models such as CNN, ResNet, and Transformer, trained on various datasets.

## Project Structure

## Dataset

The datasets used for training the models can be found in the `Dataset links.txt` file. Here are the links:

1. [Papers with Code - Speech Emotion Recognition Datasets](https://paperswithcode.com/task/speech-emotion-recognition#datasets)
2. [CREMA-D Audio Sample](https://github.com/CheyneyComputerScience/CREMA-D/blob/master/AudioWAV/1001_IWL_HAP_XX.wav)

## Models

### CNN Model

The CNN model is stored in the `CNN Model/` directory as `my_cnn_model.h5`.

### ResNet Model

The ResNet model is stored in the `ResNet Model/` directory as `my_resnet_model.h5`.

### Transformer Model

The Transformer model is stored in the `Transformer Model/` directory as `my_transformer_model.h5`.

## Usage

To use the models, follow these steps:

1. **Clone the repository:**

   ```sh
   git clone <repository-url>
   cd Deep-Learning-Emotion-Detection-Model
   ```

2. **Install the required dependencies:**

   ```sh
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
   Open `models.ipynb` in Jupyter Notebook or Jupyter Lab to see the model training and evaluation process.

4. **Load and use the models:**
   You can load the models using the following code snippets:

   ```python
   from tensorflow.keras.models import load_model

   # Load CNN model
   cnn_model = load_model('CNN Model/my_cnn_model.h5')

   # Load ResNet model
   resnet_model = load_model('ResNet Model/my_resnet_model.h5')

   # Load Transformer model
   transformer_model = load_model('Transformer Model/my_transformer_model.h5')
   ```

## Evaluation

The evaluation of the models is documented in the `Models Evaluation.docx` file located in the `Deleivered/` directory.

## Sample Data

Sample data for testing can be found in the `sample data/` directory.

## Speech Recognition Presentation

A presentation on speech recognition is available in the `Speech Recognition - Maha-.pptx` file.

## Contributors

- Sarfaraz Ahmed and Maha Alq

## License

This project is licensed under the MIT License.
