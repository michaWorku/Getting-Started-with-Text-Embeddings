# [**Understanding and Applying Text Embeddings**]()  

## **Overview**  
This repository contains course materials, including **notebooks and notes**, for the **Understanding and Applying Text Embeddings** course. The course focuses on **text embeddings** and their applications in tasks such as **classification, clustering, outlier detection, and semantic search**. You'll also learn how to use **Google Cloud’s Vertex AI** and **ScaNN (Scalable Nearest Neighbors)** to build **efficient search and retrieval systems**.  

## **Course Contents**  

### [**1. Getting Started with Text Embeddings**]()  
- **Set up Google Cloud & Vertex AI**  
- **Generate text embeddings** for words and sentences  
- **Compute similarity** between sentences using cosine similarity  

### [**2. Understanding Text Embeddings**]()  
- Learn **how embeddings are computed** (simple vs. transformer-based methods)  
- Explore **text embedding applications** (classification, clustering, recommendation, and semantic search)  
- Understand **multi-modal embeddings**  

### [**3. Visualizing Embeddings**]()  
- Reduce embedding dimensions using **Principal Component Analysis (PCA)**  
- Compare sentence similarity using **cosine similarity heatmaps**  

### [**4. Applications of Embeddings**]()  
- Use **BigQuery** to fetch **Stack Overflow data**  
- Perform **clustering** using **KMeans and PCA**  
- Apply **Isolation Forest for anomaly detection**  
- Train a **Random Forest classifier** for text classification  

### [**5. Text Generation with Vertex AI**]()  
- Generate text using **LLMs**  
- Implement **question-answering systems**  
- Adjust **temperature, top-k, and top-p parameters** to control creativity  

### [**6. Building a Q&A System Using Semantic Search**]()  
- Perform **semantic search** using **text embeddings**  
- Use **ScaNN (Scalable Nearest Neighbors)** for efficient retrieval  
- Combine **LLMs with retrieved data** for conversational responses  

### [**7. Google Cloud Setup**]()  
- Create a **Google Cloud Project**  
- Set up **billing, APIs, and credentials**  
- Connect to **Vertex AI**  

## **Setup Instructions**  

### **1. Prerequisites**  
- **Google Cloud account** with billing enabled  
- **Python 3.7+** installed  
- Jupyter Notebook (recommended)  

### **2. Installation**  
1. Clone the repository:  
   ```sh
   git clone https://github.com/your-repo/text-embeddings-course.git
   cd text-embeddings-course
   ```
2. Install dependencies:  
   ```sh
   pip install -r requirements.txt
   ```

### **3. Run Notebooks**  
Launch Jupyter Notebook and open the relevant notebooks:  
```sh
jupyter notebook
```

## **Key Technologies Used**  
- **Google Cloud Vertex AI**  
- **BigQuery**  
- **ScaNN (Scalable Nearest Neighbors)**  
- **Python Libraries**: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `transformers`  
