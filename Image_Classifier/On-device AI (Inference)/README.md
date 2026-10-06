# Image Classifier — On-device AI Inference

Investigate how an image-classification model can be prepared for direct inference on resource-constrained embedded hardware while maintaining useful classification accuracy.

## Initial Task

Classify images into:

- Apple
- Banana
- Orange

## Target Hardware

AI-Thinker ESP32-CAM

## Exploration

The model is developed and evaluated in Google Colab and converted to a **full INT8 TensorFlow Lite model** for deployment-oriented inference.

The exploration investigates:

- INT8 weight and activation representation
- Model size
- Parameter count
- Activation memory
- Target-device resource constraints
- Classification accuracy

## Resources

- [Dataset](https://github.com/DevaharshaM/EmbeddedAI/blob/inception/Image_Classifier/Datasets/Fruits_Dataset_100x100.zip)
- [Colab Notebook](https://github.com/DevaharshaM/EmbeddedAI/blob/inception/Image_Classifier/On-device%20AI%20(Inference)/Image_Classifier_OnDeviceAIInference.ipynb)