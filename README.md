# **Intelligent BFSI Knowledge and Advisory System using RAG and Agentic RAG**


## 📖 Overview

The BFSI domain involves complex policies, regulations, and financial products that are often difficult for users to understand. Traditional AI chatbots struggle with hallucinations and lack domain grounding.

This project addresses these challenges by implementing:

* **Retrieval-Augmented Generation (RAG)** for accurate, document-grounded answers
* **Agentic RAG** for autonomous reasoning, decision-making, and self-verification

The system is fully implemented in **Jupyter Notebook** and focuses on backend intelligence without any graphical user interface.


## 🎯 Objectives

* To build a **document-based BFSI Question Answering system** using RAG
* To design an **autonomous financial advisory agent** using Agentic RAG
* To demonstrate the **difference between static retrieval and agent-driven reasoning**
* To reduce hallucinations by grounding responses in BFSI documents
* To provide an explainable and evaluator-friendly AI system


## 🧠 Project Architecture

### 1️⃣ RAG Module (Knowledge Retrieval)

* Loads BFSI documents
* Converts text into vector embeddings
* Retrieves relevant information using similarity search
* Generates answers using an LLM

### 2️⃣ Agentic RAG Module (Advisory Intelligence)

* Analyzes the user query
* Classifies the financial domain (loan, credit card, insurance, fraud)
* Retrieves relevant documents dynamically
* Generates an answer
* Performs self-verification and refinement
* Produces the final response


## 📂 Dataset Description

The dataset consists of structured BFSI-related documents stored in text format.

### Dataset Files

data/

 ├── credit_card.txt

 ├── home_loan.txt
 
 ├── personal_loan.txt
 
 ├── insurance_policy.txt
 
 └── fraud_awareness.txt

### Covered Topics

* Credit card charges and usage
* Home loan eligibility and documentation
* Personal loan features and penalties
* Insurance types and claim rules
* Banking fraud awareness and safety guidelines


## 🛠️ Technology Stack

| Component               | Technology                          |
| ----------------------- | ----------------------------------- |
| Programming Language    | Python                              |
| Development Environment | Jupyter Notebook                    |
| LLM Framework           | LangChain                           |
| Embeddings              | SentenceTransformers                |
| Vector Database         | FAISS                               |
| Language Model          | OpenAI GPT / Offline LLM (optional) |
| Data Format             | TXT / PDF                           |


## ⚙️ Implementation Details

### 🔹 RAG Implementation

* Single-pass retrieval
* FAISS-based similarity search
* LLM-generated answers using retrieved context
* Suitable for factual BFSI queries

### 🔹 Agentic RAG Implementation

* Multi-step reasoning
* Query classification and planning
* Iterative retrieval
* Answer verification and refinement
* Suitable for advisory and recommendation tasks


## 🧪 Example Queries

### RAG Queries

* “What are the charges associated with credit cards?”
* “What documents are required for a home loan?”
* “What types of insurance are available?”

### Agentic RAG Queries

* “Suggest a suitable loan for a salaried individual.”
* “How can customers protect themselves from banking fraud?”
* “Which insurance policy covers hospitalization expenses?”


## 🔍 RAG vs Agentic RAG Comparison

| Feature         | RAG                | Agentic RAG         |
| --------------- | ------------------ | ------------------- |
| Retrieval       | Single-step        | Multi-step          |
| Reasoning       | Minimal            | Advanced            |
| Autonomy        | No                 | Yes                 |
| Decision Making | No                 | Yes                 |
| Use Case        | Information lookup | Advisory & guidance |


## 📊 Results and Observations

* RAG provides fast and accurate document-grounded answers
* Agentic RAG demonstrates improved reasoning and contextual understanding
* Agentic system handles complex queries more effectively
* Retrieval grounding significantly reduces hallucinations


## 🚀 Future Enhancements

* Integration with real-time financial APIs
* Support for multilingual BFSI documents
* Addition of rule-based compliance checks
* Offline deployment using local LLMs
* Quantitative evaluation metrics for answer quality


### ⚠️ Disclaimer

This project is intended for **educational and academic purposes only**.
The system does not provide real financial, legal, or investment advice.


## 🎓 Conclusion

The project successfully demonstrates how combining **RAG and Agentic RAG** can enhance AI systems in the BFSI domain. While RAG ensures accuracy through document grounding, Agentic RAG introduces intelligence through reasoning and autonomy, making the system suitable for real-world financial decision-support scenarios.







