# Sinhala-NLP-SriLanka-Constitution-Chatbot
Sinhala-NLP-Constitution-Chatbot is an AI-powered system that provides answers based on the Sri Lankan Constitution using NLP techniques. It applies Sinhala tokenization, word embeddings, and retrieval-augmented generation (RAG) with FAISS to retrieve and generate context-aware responses, making constitutional knowledge more accessible.
# Sinhala-NLP-Constitution-Chatbot

## Introduction
Sinhala-NLP-Constitution-Chatbot is an AI-powered chatbot designed to provide answers based on the **Sri Lankan Constitution** using **natural language processing (NLP) techniques**. It combines **Sinhala tokenization, word embeddings, and retrieval-augmented generation (RAG) with FAISS** to fetch and generate accurate legal information. This project aims to improve access to constitutional knowledge in Sinhala.

## Features
- **Sinhala Tokenization & Embeddings** – Utilizes **BPE, Word2Vec, and FastText** for efficient Sinhala text processing.
- **Retrieval-Augmented Generation (RAG)** – Uses **FAISS** to retrieve relevant constitutional content.
- **Conversational AI** – Provides interactive responses based on retrieved legal information.
- **Optimized Tokenization** – Evaluates different tokenization methods for improved performance.
- **Support for Morphologically Rich Sinhala Text** – Handles the complexity of Sinhala language effectively.

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Required Python libraries (install using `requirements.txt`)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Sinhala-NLP-Constitution-Chatbot.git
   cd Sinhala-NLP-Constitution-Chatbot
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download and preprocess the dataset.
4. Train or load the **Word2Vec, FastText**, and **RAG models**.
5. Run the chatbot:
   ```bash
   python chatbot.py
   ```

## Usage
- Input a question related to the **Sri Lankan Constitution** in Sinhala.
- The chatbot tokenizes, retrieves relevant sections, and generates responses.
- Provides detailed legal references in **Sinhala**.

## Model Details
- **Tokenization:** Implements **Byte Pair Encoding (BPE), Word2Vec, and FastText** for effective processing.
- **Word Embeddings:** Trains and utilizes **Word2Vec and FastText** to capture contextual meaning.
- **Retrieval System:** Uses **FAISS-based vector search** for efficient knowledge retrieval.
- **Chatbot Architecture:** Combines **retrieval-based and generative methods** for accurate responses.

## Future Improvements
- **Enhancing the RAG pipeline** for better contextual retrieval.
- **Expanding the knowledge base** with more legal documents.
- **Deploying the chatbot as a web API or mobile application.**

## License
This project is open-source and licensed under the **MIT License**.

## Contributing
Contributions are welcome! Feel free to submit issues and pull requests.

## Contact
For questions or collaborations, reach out via [your contact email or GitHub profile].

