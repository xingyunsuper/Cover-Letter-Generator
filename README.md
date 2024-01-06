
# Cover Letter Generator

[Google Colab Link](https://colab.research.google.com/drive/1_kuv3Y9IySVNwS-ArkpIK7P7Ar9LLJvc#scrollTo=B4Ifj88fSTX7)

## Overview

This project aims to generate cover letters using a foundational LLM model called Mistral-7B. Mistral has demonstrated superior performance over Llama 2 in various tasks, including reasoning and inference.

## Current Progress

The project has encountered two main challenges:

1. **Limited Disk Space and Memory on Colab:**
   Due to resource constraints on Colab, executing zero-shot learning has become a challenge.

2. **Insufficient Data Samples for SFTTrainer:**
   There is a lack of data samples, preventing the generation of at least one packed sequence with SFTTrainer.

## Project Plan

1. Perform zero-shot learning to establish a baseline understanding of the model's performance.

2. Fine-tune the Mistral model with an ample amount of data samples.

3. Evaluate the model's performance to ensure its effectiveness in generating high-quality cover letters.

4. Deploy the trained model to make it accessible for generating cover letters.






