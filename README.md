<h1 align="center">RAG</h1>

<p align="center">
  Notes, experiments, and projects on Retrieval-Augmented Generation.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat" alt="MIT License">
</p>

---

## Overview

This repository documents my work in learning Retrieval-Augmented Generation (RAG). It contains the concepts, exercises, and projects I complete as I study the subject, and serves as a practical record of that progress.

Retrieval-Augmented Generation is a technique that improves the responses of large language models by retrieving relevant information from an external knowledge source and supplying it to the model as context at the time of generation.

## Why RAG

Large language models are limited to the data they were trained on. Their knowledge becomes outdated, they have no access to private or domain-specific information, and they can produce confident answers that are not supported by facts. RAG addresses these limitations by grounding each response in retrieved source material, without the cost of retraining or fine-tuning the model. This makes it a practical foundation for applications such as enterprise search, document question answering, and customer support assistants, where accuracy and up-to-date information are essential.

## Key Concepts

| Term | Definition |
|------|------------|
| **Chunk** | A smaller segment of a source document. Documents are split into chunks so that only the most relevant portions are retrieved. |
| **Embedding** | A numerical vector that represents the meaning of a piece of text. Texts with similar meanings have embeddings that are close together. |
| **Vector Store** | A database designed to store embeddings and search them efficiently by similarity. |
| **Retriever** | The component that takes a query, searches the vector store, and returns the most relevant chunks. |
| **Context Window** | The maximum amount of text a language model can process in a single request, which limits how much retrieved content can be supplied. |

## Getting Started

**Requirements:** Python 3.10 or later.

Clone the repository:

```bash
git clone https://github.com/praneeth-cs/RAG.git
cd RAG
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
