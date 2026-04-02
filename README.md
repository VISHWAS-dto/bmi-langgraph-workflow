# BMI Calculator using LangGraph

## Overview

This project implements a graph-based workflow using LangGraph to calculate and classify Body Mass Index (BMI). It demonstrates how stateful, multi-step pipelines can be designed using graph structures, similar to modern AI systems like Retrieval-Augmented Generation (RAG).

## Features

* Graph-based pipeline using LangGraph
* Stateful data flow using TypedDict
* Modular node-based architecture
* Clear separation of computation and logic

## Workflow

1. Accept user input (weight and height)
2. Compute BMI using a dedicated node
3. Classify BMI into categories (Underweight, Normal, Overweight, Obese)

## Tech Stack

* Python
* LangGraph
* LangChain

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

## Output Example

* BMI Value (e.g., 23.4)
* Category (e.g., Normal)

## Key Concepts Demonstrated

* Graph-based workflow orchestration
* State management across nodes
* Pipeline design for multi-step processing
* Foundation for building AI systems like RAG pipelines

## Future Improvements

* Integrate LLM for personalized health insights
* Convert workflow into a REST API using FastAPI
* Extend pipeline with external data sources (RAG)
* Add input validation and error handling

## Author 
Vishwas Shankar  
Aspiring Data Scientist | ML & RAG Enthusiast, 
# linkedin
https://www.linkedin.com/in/vishwas-kori/
