# rag-data-preprocessing.
# FAISS-Based Retrieval-Augmented Generation (RAG) System for Data Preprocessing Automation

This project implements a **Retrieval-Augmented Generation (RAG)** system for automating data preprocessing tasks. It combines a **FAISS index** for efficient document retrieval with a **TinyLLaMA GGUF model** for generating contextual responses based on retrieved knowledge.

---

## **Features**
1. **Knowledge Base Management**:
   - A structured knowledge base of preprocessing techniques.
   - Support for handling missing values, outliers, scaling, and more.
2. **FAISS Indexing**:
   - Efficient vector-based retrieval using document embeddings.
3. **Natural Language Generation**:
   - Generates responses using the **TheBloke/TinyLlama-2-1b-miniguanaco-GGUF** model.
4. **Automated Data Cleaning**:
   - Preprocessing tasks like imputation and missing value handling are applied based on generated responses.
5. **User-Friendly**:
   - Modularized code for reusability and extensibility.

---

## **Technologies Used**
- **Python**
- **FAISS**: For similarity-based document retrieval.
- **Sentence-Transformers**: For generating vector embeddings.
- **ctransformers**: To load and infer from GGUF quantized models.
- **Pandas**: For data manipulation.
- **Google Colab**: For seamless execution in a cloud environment.

---

## **Setup and Installation**

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/rag-data-preprocessing.git
cd rag-data-preprocessing
### **2. Install Required Dependencies**
```bash
pip install -r requirements.txt
