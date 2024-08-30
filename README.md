# **Summer Internship 2024 - N-gram Language Model & RAG Pipeline Chatbot**

## **Overview**
This repository contains 2 key projects that were developed during Summer Internship at the **_Digital India Bhashini Department, Digital India Corporation, Ministry of Electronics & Information Technology_** under Digital India Internship Scheme:
1. **N-gram Language Model**: A project that focuses on building and evaluating N-gram models like unigram, bigram and trigram models for language processing.
2. **RAG Pipeline Chatbot**: A chatbot that is built using the Retrieval-Augmented Generation (RAG) pipeline, integrated with a Streamlit UI for interactive use and Redis for caching.
Both projects were developed and tested on Google Colab, utilizing a **T4 GPU** for efficient computation.

## **Environment Setup Instructions**

### **Prerequisites**
- Google Account to use Google Colab
- **HuggingFace Transformers**
- **Redis**
- API keys for HuggingFace and Redis

### **Setup Steps on Google Colab**
1. **Open Google Colab**:
    - Go to [Google Colab](https://colab.research.google.com/) and log in with your Google account.
2. **Clone the Repository**:
    - In a new notebook, clone the repository:
    ```python
    !git clone https://github.com/dhruv5903/summerinternship24.git
    %cd summerinternship24
    ```
3. **Install Required Packages**:
    - Install necessary packages directly in the Colab notebook:
    ```python
    !pip install -r requirements.txt
    ```
4. **Set Up API Keys**:
    - **HuggingFace**: 
        - Create an account on [HuggingFace](https://huggingface.co/).
        - Obtain your API key and set it as an environment variable:
        ```python
        import os
        os.environ['HUGGINGFACE_API_KEY'] = 'your_huggingface_api_key'
        ```
    - **Redis**: 
        - Sign up for Redis and obtain your API key.
        - Set it as an environment variable:
        ```python
        os.environ['REDIS_API_KEY'] = 'your_redis_api_key'
        ```
5. **Enable GPU in Colab**:
    - Go to `Runtime` > `Change runtime type`.
    - Under **Hardware accelerator**, select **GPU (T4)**.

## **Running the Scripts**

### **Project 1: N-gram Language Model**
- **Notebook**: `NgramModels(Final).ipynb`
- **Purpose**: This notebook demonstrates the final implementation of the N-gram language model.
- **Steps**:
  1. Open `NgramModels(Final).ipynb` in Colab.
  2. Run the cells sequentially to build, train, and evaluate the N-gram language model.

### **Project 2: RAG Pipeline Chatbot**

#### **Step 1: Initial Development**
- **Notebook**: `TestRAG-pipeline(Draft3).ipynb`
- **Purpose**: This notebook contains the code for developing the RAG pipeline.
- **Steps**:
  1. Open `TestRAG-pipeline(Draft3).ipynb` in Colab.
  2. Run the cells to build and test the RAG pipeline model.

#### **Step 2: Final Implementation with UI**
- **Notebook**: `RAGpipelineStreamlitUI(Final).ipynb`
- **Purpose**: This notebook integrates the RAG pipeline with a Streamlit UI, allowing for an interactive chatbot experience.
- **Steps**:
  1. Open `RAGpipelineStreamlitUI(Final).ipynb` in Colab.
  2. Run the cells to start the Streamlit server and interact with the RAG chatbot through the web interface.

## **Steps to Obtain the Final Output**
1. **N-gram Model**:
   - Follow the steps in `NgramModels(Final).ipynb` to generate and evaluate the language model predictions.
2. **RAG Chatbot**:
   - Execute the `RAGpipelineStreamlitUI(Final).ipynb` notebook.
   - The final output will be an interactive chatbot interface accessible through your web browser.

## **Additional Notes**
- Ensure that all necessary API keys are correctly set up and that the required packages are installed.
- Each notebook contains comments and guidance to assist you through the processes.
