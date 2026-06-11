[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/cTz6p1BO)


# Fine-Tuning and RAG-Based Medical Assistant

## Introduction

This notebook demonstrates the implementation of two important concepts in Generative AI:

1. Retrieval-Augmented Generation (RAG)
2. Fine-Tuning using LoRA

The goal is to create a simple medical company assistant that can answer questions based on company-specific information and also explore how a language model can be fine-tuned on custom data.

---

## Objectives

* Understand how RAG works.
* Learn how vector databases store document embeddings.
* Use FAISS for similarity search.
* Generate responses using an LLM through Groq.
* Fine-tune TinyLlama using LoRA.
* Compare retrieval-based and fine-tuned approaches.

---

## Tools and Libraries Used

* Python
* LangChain
* FAISS
* Hugging Face Transformers
* PEFT (LoRA)
* TinyLlama-1.1B-Chat
* Groq API
* Sentence Transformers

---

## Workflow

### Part 1: Retrieval-Augmented Generation (RAG)

1. Load company documents.
2. Split documents into smaller chunks.
3. Generate embeddings for each chunk.
4. Store embeddings in a FAISS vector database.
5. Retrieve relevant information based on user queries.
6. Generate context-aware responses using an LLM.

### Part 2: Fine-Tuning

1. Load the TinyLlama model.
2. Apply 4-bit quantization for efficient training.
3. Configure LoRA adapters.
4. Prepare a custom dataset.
5. Train the model on domain-specific data.
6. Save the fine-tuned model.

---

## Key Learning Outcomes

Through this notebook, I learned:

* The difference between RAG and Fine-Tuning.
* How embeddings are generated and used.
* How vector databases improve information retrieval.
* How LoRA enables parameter-efficient fine-tuning.
* How modern AI assistants are built using LLMs.

---

## Results

The RAG system was able to retrieve relevant information from company documents and provide context-aware responses. The fine-tuning section demonstrated how a pre-trained language model can be adapted to a specific domain using a small dataset and limited computational resources.

---

## Conclusion

This project helped me gain practical experience with Retrieval-Augmented Generation (RAG), vector databases, embeddings, and parameter-efficient fine-tuning. These techniques are widely used in modern AI applications to improve the performance and customization of large language models.

---

## Author

Rithish Barath

B.E. - CSE [ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING]


