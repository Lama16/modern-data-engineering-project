# Modern Data Engineering for AI Systems – Final Project

## Team Members

- Lama Bin Muryihah
- Tarfah Alsharidah

---

## Project Overview

This project was completed as the final project for the **Modern Data Engineering for AI Systems** training program.

The goal of the project is to demonstrate how modern data engineering components can be integrated into a single AI data platform. The implemented pipeline follows a Lakehouse architecture and includes data ingestion, data validation using Data Contracts, DAMA-based data quality checks, data transformation through Bronze, Silver, and Gold layers, and a Retrieval-Augmented Generation (RAG) application powered by a vector database.

---


## Project Modules

### Module 1 – Data Ingestion
Simulates real-time e-commerce events and stores the raw data in the Bronze layer.

### Module 2 – Lakehouse Processing
Validates incoming data using Data Contracts and transforms it through the Bronze, Silver, and Gold layers.

### Module 3 – Data Quality
Applies DAMA data quality checks to verify completeness, accuracy, consistency, timeliness, uniqueness, and validity before serving the data.

### Module 4 – RAG Pipeline
Generates embeddings, stores them in ChromaDB, retrieves relevant information, and answers user queries using Retrieval-Augmented Generation (RAG).

### Module 5 – Pipeline Orchestration
Executes the complete workflow in sequence to simulate a production-ready AI data platform.

---

## How to Run

1. Open the notebook in Google Colab.
2. Install the required packages.
3. Run all notebook cells from top to bottom.
4. The pipeline will execute and generate the final RAG response.

---

## Repository Contents

```
Modern_Data_Engineering_Final_Project.ipynb
README.md
```
