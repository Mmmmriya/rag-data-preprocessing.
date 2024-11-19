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
## **Setup and Usage in Google Colab**

### **1. Open the Colab File**
Upload the provided `.ipynb` Colab notebook file to Google Colab or start a new notebook and paste the cleaned code.

### **2. Install Required Libraries**
Run the following command in the first cell to install dependencies:
```bash
!pip install faiss-cpu sentence-transformers transformers ctransformers

---

### **3. Download the Model**

Download the TinyLLaMA GGUF model from Hugging Face:
wget https://huggingface.co/TheBloke/Tinyllama-2-1b-miniguanaco-GGUF/resolve/main/tinyllama-2-1b-miniguanaco.Q4_K_M.gguf -O tinyllama-gguf-model.gguf

Make sure the model file is saved in your Colab environment for use.

### **4. Upload Knowledge Base**
Create a JSON file named knowledge_base.json containing structured preprocessing techniques.
Use the Colab file upload feature to upload the knowledge base into the environment.






