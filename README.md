# Text Summarization using Pegasus Model

This repository contains code for text summarization using the Pegasus model from the Hugging Face Transformers library. The model is fine-tuned on a dataset consisting of newspaper articles to generate concise summaries.

## Overview

The project aims to utilize the Pegasus model, a variant of the Transformer architecture, for the task of abstractive text summarization. The summarization process involves taking longer documents as input and generating shorter summaries that capture the key information from the original text.

## Dataset

The dataset used for training and evaluation consists of newspaper articles. Each article contains metadata such as the newspaper name, publication date, headline, content, and a pre-written summary.

## Methodology

1. **Data Preprocessing**: The dataset is preprocessed to clean and tokenize the text data, which is then formatted as input for the Pegasus model.

2. **Fine-tuning**: The pre-trained Pegasus model is fine-tuned on the newspaper articles dataset using techniques such as maximum likelihood estimation and teacher forcing.

3. **Summarization**: The fine-tuned model is used to generate summaries for new input articles. The generated summaries are evaluated using ROUGE scores to assess their quality and effectiveness.

4. **Analysis**: The ROUGE scores are analyzed to gain insights into the performance of the summarization model. Various metrics such as ROUGE-1, ROUGE-2, and ROUGE-L are computed and visualized to understand the model's strengths and weaknesses.

## Results

The summarization model achieves competitive ROUGE scores, indicating its effectiveness in generating informative and concise summaries. Further analysis reveals areas for improvement and potential avenues for future research.

## Usage

To use the summarization model:

1. Install the required dependencies: `pip install -r requirements.txt`.
2. The Pegasus model on the dataset.
3. Generate summaries for new articles using the model.
4. Evaluate the generated summaries using ROUGE scores.

## Acknowledgments

- The Pegasus model implementation is based on the Hugging Face Transformers library.
- The dataset used for training and evaluation is sourced from Newspaper Archives.