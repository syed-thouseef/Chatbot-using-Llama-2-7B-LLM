# Chatbot-using-Llama-2-7B-LLM
A simple comparison between Basic and Advanced Chatbot was performed using the Llama 2 7B Large Language Model (LLM).Loaded the model and tokenizer by setting up the environment with Hugging Face transformers, PyTorch and accelerators. Generated responses by creating the Llama pipeline and used Gradio Chat Interface for a robust communication between
the user and the chatbot



## Introduction

In this Colab Notebook, we are going to chat with Llama-2 7B LLM.

## Workflow
1. **Installations**: We'll begin by setting up our environment with the required libraries.
2. **Prerequisites**: Ensure we have access to the Llama-2 7B model on Hugging Face.
3. **Loading the Model & Tokenizer**: Retrieve the model and tokenizer for our session.
4. **Creating the Llama Pipeline**: Prepare our model for generating responses.
5. **Interacting with Llama through Gradio's Chat Interface**: Prompt the model for answers and explore its capabilities.

Note: Enable the runtime to GPU in order to execute the notebook.

## Installations

Before we proceed, we need to ensure that the essential libraries are installed:
- `Hugging Face Transformers`: Provides us with a straightforward way to use pre-trained models.
- `PyTorch`: Serves as the backbone for deep learning operations.
- `Accelerate`: Optimizes PyTorch operations, especially on GPU.



