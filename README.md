# Demo
https://github.com/user-attachments/assets/e277ef08-c77a-4fe1-a1a4-decb2c0916e0

# RAG Performance Evaluation using TruLens

## Project Overview

This project aims to evaluate the performance of Retrieval-Augmented Generation (RAG) models using TruLens across various embedding models. The evaluation involves assessing the Context Relevance, Answer Relevance and Groundedness of the RAG models with latency.
Through this one can determine which embedding model perform best of the document.

## Table of Contents

- [Installation](#installation)
- [Evaluation Metrics](#evaluation-metrics)

## Installation

### Prerequisites

- Python 3.8 or higher

### Clone the Repository

```bash
git clone https://github.com/alphaace001/RAG-Evaluation.git
cd rag-trulens-evaluation
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Evaluation Metrics

The performance of RAG models will be evaluated based on the following metrics:

- **Context Relevance**: The relevance between the Query and Context Retrieved.
- **Answer Relevance**: How relevant the responses are to the queries.
- **Latency**: The time taken to generate the responses.
- **Groundedness**: A measure the hallucination in the answer generated


