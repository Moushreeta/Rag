**Lung Cancer Query-Answering Chatbot (RAG-based)**

This repository hosts a chatbot system capable of answering queries related to lung cancer. The system utilizes the Retrieval-Augmented Generation (RAG) framework, integrating data from various sources including government health websites such as NIH and research papers.

**Features**

**Query-Answering Capability:** The chatbot can respond to inquiries related to lung cancer, providing accurate and relevant information sourced from diverse datasets.

**Data Sources:** Information used by the chatbot is derived from reputable sources including government health websites and research papers, ensuring reliability and credibility.

**PDF Data Integration:** The system includes functionality to merge PDF files from a specified folder, enabling seamless integration of additional data sources.

**Text Chunking:** Implemented text chunking facilitates efficient processing of large documents, enhancing the system's ability to handle extensive textual data.

**Embeddings:** Leveraging Hugging Face embeddings, the chatbot is equipped with state-of-the-art natural language processing capabilities, enabling nuanced understanding of user queries.

**Chroma Database:** The system utilizes Chroma for document embedding storage and retrieval, enabling efficient and effective information retrieval.

**Getting Started**

**Prerequisites**
Ensure you have the following dependencies installed:

**PyPDF2** for PDF manipulation.

**RecursiveCharacterTextSplitter** for text chunking.

**HuggingFaceEmbeddings** for embeddings.

**Chroma** for document embedding storage and retrieval.

**Installation**

1.Clone this repository to your local machine.

git clone <repository_url>

2.Install the required Python dependencies.

pip install PyPDF2  # for PDF manipulation

pip install recursive-text-splitter  # for text chunking

pip install sentence-transformers  # for embeddings

pip install chroma  # for document embedding storage and retrieval

