# DocuChat AI

## Project Description
This project is a generative AI chatbot that specializes in extracting and comprehending information from PDF documents. It allows users to upload multiple PDF files, trains on the content of those documents, and enables them to ask questions or make queries related to the PDFs' content. The chatbot leverages Langchain, PyPDF2, and Streamlit to provide an interactive and user-friendly experience.

## Overview
- Upload PDFs: Users can upload one or more PDF files to the chatbot.
- Training: The chatbot processes the PDFs using Langchain and PyPDF2 to extract textual data and generate a knowledge base.
- Chat Interface: Users can initiate conversations with the chatbot by asking questions or making inquiries within the scope of the PDF documents.
- Responses: The chatbot uses generative AI to provide meaningful responses based on the trained knowledge base.
- User-Friendly: The project is built with a user-friendly interface using Streamlit for easy interaction.

## Use Cases
The Generative AI Chatbot for PDFs has a wide range of practical applications, including:
1. **Research Assistance**: Researchers can quickly extract information from academic papers and journals, making it easier to find relevant studies and data.
2. **Legal Document Analysis**: Legal professionals can use the chatbot to review legal documents, contracts, and case law to answer specific questions.
3. **Education Support**: Students and educators can use the chatbot to better understand complex topics by asking questions about textbooks and research papers.
4. **Knowledge Base Creation**: The chatbot can be employed to generate a knowledge base from a collection of PDFs, facilitating data retrieval.
5. **Technical Documentation**: Developers and engineers can use the chatbot to search for specific information in technical manuals and documentation.
6. **Compliance and Regulatory Queries**: Compliance officers can rely on the chatbot to ensure adherence to regulations by querying compliance documents.

## Tech Stack
- **Langchain**: Langchain is used for natural language processing (NLP) tasks, including text extraction and understanding.
- **PyPDF2**: PyPDF2 is utilized to extract textual content from PDF documents.
- **Streamlit**: Streamlit is the framework used for creating a user-friendly web interface for the chatbot.
- **Generative AI**: The project incorporates generative AI techniques to generate responses based on the content of the PDFs.
- **Python**: The project is primarily developed in Python.

## Deployed Link
[Live Demo](https://docuchat-ai-sg.streamlit.app/)

## Getting Started
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/ShashankGupta10/DocuChat-AI.git
   cd DocuChat-AI
   pip install -r requirements.txt
   streamlit run app.py
