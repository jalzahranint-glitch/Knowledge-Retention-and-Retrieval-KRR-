# Knowledge Retention and Retrieval (KRR)

## Overview

This project investigates two approaches for knowledge retention and retrieval in large language models:

1. LoRA-based Parametric Memory
2. Retrieval-Augmented Generation (RAG)

The system is designed for cybersecurity question answering and evaluates how effectively each approach stores and retrieves domain-specific knowledge.

## Objectives

* Fine-tune GPT-2 Medium using LoRA.
* Build a RAG pipeline using FAISS and sentence embeddings.
* Compare parametric memory and retrieval-based methods.
* Evaluate knowledge retention and answer quality on cybersecurity facts.

## Methods

### LoRA Fine-Tuning

* GPT-2 Medium
* Parameter-Efficient Fine-Tuning (PEFT)
* Low-Rank Adaptation (LoRA)

### Retrieval-Augmented Generation (RAG)

* Sentence Transformers
* FAISS Vector Database
* GPT-2 Medium for answer generation

## Dataset

A cybersecurity question-answer dataset containing domain-specific facts and answers.

## Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* PEFT (LoRA)
* Sentence Transformers
* FAISS

## Research Focus

This project explores the trade-offs between storing knowledge directly in model parameters and retrieving knowledge from external memory systems.

## Author

Jawaher Alzahrani
