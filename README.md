# Machine Translation Project

This project involves implementing and comparing different models for machine translation tasks, specifically translating between German and English. The project includes three models:

1. **German to English Translation (Scratch Implementation)**
2. **English to German Translation using T5 Model (Zero Shot Prompting)**
3. **English to German Translation using Fine-tuned T5 Model**

## Models Overview

### 1. German to English Translation (Scratch Implementation)

- **Reference**: [PyTorch Translation Transformer Tutorial](https://pytorch.org/tutorials/beginner/translation_transformer.html)
- **Folder**: `MachineTranslation-Scratch`
- **Description**: This model is implemented from scratch using PyTorch's Transformer architecture. It demonstrates the fundamental steps of building and training a translation model without relying on pre-trained models.

### 2. English to German Translation using T5 Model (Zero Shot Prompting)

- **Reference**: [Hugging Face T5 Model](https://huggingface.co/google/t5-small)
- **Folder**: `MachineTranslation T5 model`
- **Description**: This model uses the T5 (Text-To-Text Transfer Transformer) pre-trained model from Hugging Face for zero-shot translation. No additional training is performed, leveraging the model's ability to translate directly with prompt engineering.

### 3. English to German Translation using Fine-tuned T5 Model

- **Reference**: [Fine-tuning T5 for Translation](https://huggingface.co/docs/transformers/tasks/translation)
- **Folder**: `Finetuned-T5-MachineTranslation`
- **Description**: This model fine-tunes the T5 model on a specific English-German translation dataset to improve translation performance. Fine-tuning adjusts the pre-trained model weights to better suit the translation task.

## Dataset

- **Source**: [Hugging Face Datasets](https://huggingface.co/docs/datasets/en/loading)
- 
**Description**: The dataset used for training and evaluation is loaded using the Hugging Face Datasets library. It includes parallel corpora for German-English translations.

## Folder Structure

- **German_to_English**: Contains the Jupyter notebook (`.ipynb`) file for the scratch implementation of the German to English translation model.
- **English_to_German_Zero_Shot**: Contains the Jupyter notebook (`.ipynb`) file for the zero-shot T5 model implementation.
- **English_to_German_Fine_Tuned**: Contains the Jupyter notebook (`.ipynb`) file for the fine-tuned T5 model implementation.

## How to Run

1. **Clone the Repository**:
   ``` git clone <repository-url> ```
   ```cd <repository-folder>```
