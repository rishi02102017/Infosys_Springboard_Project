# **RAG and AI Agents for Healthcare**

## **Project Overview**
This project, developed as part of the Infosys Springboard Internship, leverages **Retrieval-Augmented Generation (RAG)** and **AI Agents** to provide intelligent, context-aware solutions for healthcare data analysis and document-based Q&A. It combines cutting-edge natural language processing and machine learning techniques to assist healthcare professionals, researchers, and patients in retrieving and analyzing data efficiently.

---

## **Key Components**

### **1. RAG AI Chatbot**
- A conversational assistant designed to retrieve and answer healthcare-related questions from uploaded medical documents.
- **Features**:
  - **PDF Document Support**: Upload and process healthcare-related PDFs.
  - **Vector Database Integration**: FAISS is used for efficient document indexing and semantic search.
  - **RAG Framework**: Combines retrieval and generative capabilities for contextually accurate answers.
- **Technologies Used**:
  - FAISS for indexing.
  - LangChain for conversational logic.
  - Groq's Llama3-70b-8192 model.

### **2. Pandas AI Agent**
- A data analysis tool for exploring and visualizing trends in healthcare datasets.
- **Features**:
  - Automated analysis of numerical and categorical data.
  - Generating trend insights and visualizations.
- **Technologies Used**:
  - LangChain's experimental agent toolkits.
  - Pandas for data manipulation.
  - Groq's Llama3-70b-8192 model.

---

## **How It Works**

### **RAG AI Chatbot Workflow**
1. **Document Upload**: Upload healthcare-related PDFs.
2. **Data Embedding**: The content is processed, embedded, and stored in a vector database.
3. **User Query**: Users submit queries through a conversational interface.
4. **Query Matching**: Relevant content is retrieved from the vector database and presented as answers.

### **Pandas AI Agent Workflow**
1. **Dataset Input**: Analyze datasets such as patient records or medical trends.
2. **Data Processing**: Trends are detected through descriptive statistics, correlation analysis, and visualizations.
3. **Insight Delivery**: Results are presented in a user-friendly format.

---

## **Use Cases**
- **Healthcare Professionals**: Quickly retrieve protocols, guidelines, or research data.
- **Patients**: Access simplified information about symptoms, treatments, or medications.
- **Researchers**: Analyze large datasets and extract insights from medical documents.

---

## **Getting Started**

### **1. Clone the Repository**
```bash
git clone https://github.com/rishi02102017/Infosys_Springboard_Project.git
```
### **2. Navigate to the Respective Folders**

#### **RAG AI Chatbot**
- Contains the implementation of the chatbot for document-based Q&A.
- Includes the `Healthcare.pdf` dataset.

#### **Pandas AI Agent**
- Contains the code for trend analysis and insights.
- Includes the `Synthetic_Healthcare_Dataset.xlsx` dataset.

---

### **3. Install Dependencies**
Run the following command to install required Python libraries:
```bash
pip install -r requirements.txt
```

### **4. Run the Project**
- For the **RAG AI Chatbot**, open and execute the Jupyter Notebook (`.ipynb`) in the RAG folder.
- For the **Pandas AI Agent**, open and execute the Jupyter Notebook (`.ipynb`) in the Pandas folder.

---

## **Technologies Used**
- **Large Language Models (LLMs)**:
  - Groq's Llama3-70b-8192 for natural language processing.
- **Vector Databases**:
  - FAISS for embedding storage and retrieval.
- **Python Libraries**:
  - LangChain, Pandas, Matplotlib, and more.

---

## **License**
This project is licensed under the MIT License.

---

## **Contributors**
- **Jyotishman Das**: Lead Developer and Project Contributor.


