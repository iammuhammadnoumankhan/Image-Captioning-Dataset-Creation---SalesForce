# Image Captioning Dataset Creation for Stable Diffusion Finetuning

This project demonstrates how to create an image captioning dataset that can be used for Stable Diffusion finetuning. The process use [SalesForce captioning](https://huggingface.co/Salesforce/blip-image-captioning-large) model to generate captions efficiently, even for large datasets.

## Introduction

In this project, we will:
1. Use the [SalesForce image captioning model](https://huggingface.co/Salesforce/blip-image-captioning-large) to generate captions for the images.
2. Implement efficient methods to handle large datasets.

This project is ideal for AI researchers, machine learning enthusiasts, and anyone interested in image captioning and dataset creation.

## Requirements

- Python 3.11.7
- PyTorch
- datasets
- tqdm
- pandas
- transformers
- pillow
- SalesForce Image Captioning Model

## Installation

1. Clone the repository

2. Create Virtual Environment:
   ```python -m venv myenv``` OR ```conda create --name myenv python==3.11.7```

3. Activate Virtual Environment:

    **windows:** ```.\myenv\Scripts\activate``` OR  ```conda activate myenv```
    
    **Linux:** ```source myenv/bin/activate```

4. Install the required libraries:
    ```pip install transformers datasets pandas tqdm pillow```

    Install [torch](https://pytorch.org/) from its website as per your machine specs.

## Usage

1. Create 'images' folder:
    Create images folder in a same directory where ```.ipynb``` file is located and paste all your images in it.

2. Run code cell by cell:
    Run code in .ipynb file cell by cell

3. Two Methods:
    There are two methods discuss in ```.ipynb``` file to generate captions.

## Results

The resulting captions will be stored in `captions.csv`, which can be used for Stable Diffusion finetuning.



Thank You!

[Muhammad Nouman Khan](https://www.linkedin.com/in/muhammad-nouman-khan-248530233/)
