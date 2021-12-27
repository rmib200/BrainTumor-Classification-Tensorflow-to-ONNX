# BrainTumor-Classification-Tensorflow-to-ONNX
Training a CNN for Binary Classification of Tumors using Tensorflow and exporting the model to ONNX (Open Neural Network eXchange)

![https://github.com/rmib200/BrainTumor-Classification-Tensorflow-to-ONNX/blob/main/brain_tumor_dataset.png](https://github.com/rmib200/BrainTumor-Classification-Tensorflow-to-ONNX/blob/main/brain_tumor_dataset.png)

__Run the Project__ <br> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]( https://colab.research.google.com/github/rmib200/BrainTumor-Classification-Tensorflow-to-ONNX/blob/main/BrainTumor_Tensorflow_Classification_ONNX.ipynb)

This project is aimed to the classification of tumors in human brains 🧠 with Tensorflow using a reproducible pipeline and exporting the model using [ONNX](https://onnx.ai) for later testing in a project inside Unity that can be downloaded [here](https://github.com/rmib200/BrainTumor-Classification-Tensorflow-to-ONNX/blob/main/brain_tumor_app.rar). Just decompress the rar and run the Unity app!. 

You can use any fMRI image to test it. You can download Brain fMRI 🧠 🧠 samples [here](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)

The model uses an extremely simple architecture and few learning epochs to achieve a high degree of prediction.

The dataset and the code for the project are available as well as the [model in ONNX format](https://github.com/rmib200/BrainTumor-Classification-Tensorflow-to-ONNX/blob/main/brainTumorModel.onnx).


# Unity-App

![https://github.com/rmib200/BrainTumor-Classification-Tensorflow-to-ONNX/blob/main/main_menu.png](https://github.com/rmib200/BrainTumor-Classification-Tensorflow-to-ONNX/blob/main/main_menu.png)

You can choose an image from your device and the program will create a texture of the correct size to pass it through the Network.
![https://github.com/rmib200/BrainTumor-Classification-Tensorflow-to-ONNX/blob/main/classification_view.png](https://github.com/rmib200/BrainTumor-Classification-Tensorflow-to-ONNX/blob/main/classification_view.png)
