# Generative AI & Transformers Discovery

## Project Overview
This project demonstrates the use of Hugging Face Transformers for sentiment analysis, text generation, and summarization in a customer support context using the Discovery-to-Action framework.

## Setup
```bash
pip install transformers torch
Key Components

Sentiment Analysis: BERT-based model for classifying text sentiment.
Text Generation: GPT-2 for creative response drafting.
Summarization: BART/T5-based summarizer.

Business Application
Integrates into high-volume support queues to automate triage, drafting, and summarization while maintaining human oversight.
Findings

Models handle basic sentiment well but struggle with sarcasm.
Generated content requires validation to prevent hallucinations.
Pre-training builds broad knowledge; fine-tuning specializes it.

Files

: Main Jupyter Notebook with executed examples.

Project Goal Achievements

Successfully set up and ran three Hugging Face pipelines
Evaluated performance on edge cases (including sarcasm)
Explained pre-training vs fine-tuning in simple terms
Proposed a practical workflow for 1,000-ticket/day customer support
Discussed hallucinations, bias, and responsible AI usage
