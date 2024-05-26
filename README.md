# Image classification Project

This repository contains a image classification project where we have resolved the problem using four different approaches. Each approach is implemented in a separate Jupyter notebook.

## Approach 1

The first approach uses a fine-tuned ResNet18 model. The model is trained on a custom dataset and the best model weights are saved for future use. The code for this approach can be found in the Jupyter notebook `finetune_notebook.ipynb`.

## Approach 2

The second approach uses a transfer learning technique with MobileNetV2 as the feature extractor. The code for this approach can be found in the Jupyter notebook `transfer_notebook.ipynb`.

## Approach 3

The third approach uses a custom VGG11 model trained from scratch. The code for this approach can be found in the Jupyter notebook `scratch_notebook.ipynb`.

## Approach 4

The fourth approach uses the Vision Transformer (ViT) model from Google. The code for this approach can be found in the Jupyter notebook `Image_Classification_using_Hugging_Face.ipynb`.

## Evaluation

After implementing the four approaches, we evaluate them using a separate Jupyter notebook. This notebook loads the models trained in each approach and uses them to make predictions on a test dataset. The results are then saved to a CSV file. The code for the evaluation can be found in the Jupyter notebook `Evaluation.ipynb`.

## Requirements

You can install these libraries using pip:

     ```
     pip install -r requirements.txt
     ```
