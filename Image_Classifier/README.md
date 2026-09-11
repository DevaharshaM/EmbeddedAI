# Image Classifier — Edge AI Exploration

Investigate how a useful image-classification model can be progressively optimized for deployment on resource-constrained embedded hardware while maintaining acceptable accuracy.

## Initial Task

Classify images into:

- Apple
- Banana
- Orange

## Target Hardware

AI-Thinker ESP32-CAM

## Exploration

The model is developed and evaluated in Google Colab and progressively optimized through:

**FP32 → FP16 → INT8**

The experiments investigate the trade-off between classification accuracy and embedded resource constraints.

## Resources

- [Dataset](https://github.com/DevaharshaM/EmbeddedAI/blob/inception/Image_Classifier/Fruits_Dataset.zip)
- [Colab Notebook](https://github.com/DevaharshaM/EmbeddedAI/blob/inception/Image_Classifier/Image_Classifier_EdgeAI.ipynb)
