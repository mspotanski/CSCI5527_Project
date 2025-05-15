# CSCI5527_Project

This project was centered around using LLMs to trick Image Classifiers by learning what perturbations can be done to images to maximize loss.

When running this code in Colab, make sure to register for a HuggingFace token, upload the pretrained weights into your workspace in Colab, and on HuggingFace request access to the Llama 3 models from Meta.


# How to run once HuggingFace is setup
- Download finetuned ResNet model weights: https://github.com/mspotanski/CSCI5527_Project/blob/main/model/resnet18_ImageNette.pth
- Go to Google Colab, File > Open Notebook > GitHub
  - Input this URL: https://github.com/mspotanski/CSCI5527_Project/blob/main/code/LLM_ImageNette.ipynb
- In the Notebook go Files > Upload > the downloaded weights from the first step
- Run notebook
