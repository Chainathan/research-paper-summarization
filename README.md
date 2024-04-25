# Research Paper Summarization

This project focuses on the summarization of research papers, particularly targeting the abstract section generation. Please note that this project is still under development.

## Overview:

The project utilizes a hybrid approach combining both extractive and abstractive summarization techniques to handle long document contexts effectively.

## Key Features:

- **Hybrid Summarization**: Combining extractive and abstractive methods for summarization.
- **Model Finetuning**: Fine-tuned Mistral 7B, Ilama 2-7B, Gemma 7B specifically for summarization tasks.
- **Dataset**: Subset of 25k research papers from arXiv for training and evaluation.

## Usage:

1. **Data Input**: Provide research papers or documents for summarization.
2. **Summarization Process**: Utilize the hybrid summarization approach to generate abstracts.
3. **Model Evaluation**: Assess the quality of generated abstracts against ground truth summaries.

## Dependencies:

- Python 3.x
- PyTorch
- Transformers library
- arXix machine learning research papers dataset

## Future Work:

- Further refinement of summarization techniques.
- Integration of more datasets for diverse summarization tasks.
