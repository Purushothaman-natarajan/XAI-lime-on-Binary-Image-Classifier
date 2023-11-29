# XAI - LIME: Binary Dog and Cat Image Classifier Model

This project aims to provide transparent and interpretable explanations for the predictions made by the binary image classifier. You can find the model implementation, along with an interactive explanation using LIME, in this repository.

## Repository Overview

This repository contains the following components:

1. **Binary Image Classifier Model**: The core binary dog and cat image classifier model developed using deep learning techniques. You can find the model implementation in the `model` directory. For more details, please refer to the [model implementation](https://github.com/Purushothaman-natarajan/Binary-Image-Classification/).

2. **Explainability using LIME**: The implementation of Local Interpretable Model-agnostic Explanations (LIME) to explain the predictions made by the binary classifier. LIME helps in understanding and interpreting the model's decisions at the local level. You can find the LIME implementation in the `explanation` directory. For more details, please refer to the [explanation implementation](https://github.com/Purushothaman-natarajan/Binary-Image-Classification/).

## Implementation Details

In this project, we imported the pre-trained binary image classifier model directly from the local directory. The model was developed using state-of-the-art deep learning techniques and trained on a dataset containing dog and cat images.

### Model Evaluation

To demonstrate the model's performance, we randomly selected a set of dog and cat images from the dataset. The model accurately predicted the class labels for these images, showcasing its effectiveness in binary image classification tasks.

### LIME Explainer

We utilized the LIME explainer to provide interpretable explanations for the model's predictions. LIME generates local explanations for individual predictions, helping users understand why a specific prediction was made. These explanations are crucial for building trust in machine learning models and ensuring transparency in decision-making processes.

## Results

Below is an example result from the LIME explainer:

![LIME Explanation](https://github.com/Purushothaman-natarajan/XAI-lime-on-Binary-Image-Classifier/blob/3a70e7e18bb0c111d0fdb1fd981cf741cb6139bf/lime_cat.png)

In this visualization, the LIME explainer highlights the important regions in the input image that contributed to the model's prediction. The color-coded heatmap indicates the significance of each pixel in the prediction process, offering valuable insights into the model's decision-making process.

Your feedback is highly appreciated and will help improve this project.

Thank you for your interest in the XAI - LIME binary dog and cat image classifier model! Happy coding! 🐾🐱🐶
