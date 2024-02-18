# Mixtral8x7B-Instruct in Google Colab

## Introduction
Welcome to the Mixtral8x7B-Instruct project! This repository provides a Google Colab notebook that allows you to run Mixtral8x7B-Instruct, a language generation model, directly in your browser or on a consumer-grade GPU. This capability has been achieved by quantizing the original model in mixed precision and implementing a MoE-specific offloading strategy.

To learn more about the technical details of this model, you can refer to this website: https://huggingface.co/mistralai/Mixtral-8x7B-v0.1.

## Usage Requirements
To run the notebook effectively, you will need approximately 16 GB of VRAM and 11 GB of RAM. This is necessary for generating somewhat long texts using the model.

## Balancing RAM and GPU VRAM Usage
You can balance between RAM and GPU VRAM usage by adjusting the `offload_per_layer` variable in the notebook. Increasing this variable will decrease GPU VRAM usage while increasing RAM usage and decreasing generation speed. Conversely, decreasing it will have the opposite effect.

## Model Initialization
The notebook initializes the Mixtral8x7B-Instruct model and sets up the necessary configurations for running it efficiently. This includes importing libraries, fixing dependencies, and setting up the model for inference.

## Running the Model
Once the model is initialized, you can interact with it by providing input text prompts. The model will generate responses based on the provided input, leveraging its language generation capabilities.

Enjoy exploring Mixtral8x7B-Instruct in Google Colab and experimenting with its language generation capabilities!
