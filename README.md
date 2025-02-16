CareAI - Medical Chatbot and Image Interpreter

CareAI is an AI-powered medical assistant designed to provide intelligent responses to medical queries and analyze medical images. This application leverages advanced NLP and image processing models to help users with their healthcare-related concerns.

🌟 Features

🔹 Medical Chatbot

Ask any medical-related question, and the AI will provide a relevant and informative answer.

The chatbot is powered by LangChain and Llama 2 for natural language understanding.

🔹 Medical Image Interpreter

Upload images such as X-rays or skin condition photos, and the AI will analyze them for potential abnormalities.

Uses Google Generative AI for medical image processing.

🔹 Severity Detection

The AI evaluates the risk level associated with a disease and categorizes it as High, Moderate, or Low.

For example, queries mentioning cancer are marked as high risk, while those mentioning flu are categorized as moderate risk.

🔹 Multilingual Support

The chatbot supports real-time translation of responses into different languages using Google Translate API.

🔹 History Tracking

View past interactions, including chatbot queries and image analyses.

🚀 Installation Guide

Prerequisites

Python 3.8+

Virtual Environment (Recommended)

Setup Steps

Clone the repository

git clone https://github.com/yourusername/CareAI.git
cd CareAI

Create a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

Install dependencies

pip install -r requirements.txt

🔧 Usage

To start the Streamlit app, run the following command:

streamlit run app.py

API Configuration

Make sure to set up your Google Generative AI API Key inside the script:

genai.configure(api_key="your_google_api_key")

📝 Project Structure

CareAI/
│── app.py                 # Main application script
│── requirements.txt       # Required dependencies
│── README.md              # Project documentation
│── vectorstores/          # FAISS vector database
│── models/                # Local AI models (Llama 2, etc.)
│── assets/                # Placeholder for medical images
│── utils/                 # Helper functions

🤝 Contributing

We welcome contributions! To contribute:

Fork the repository.

Create a feature branch (git checkout -b new-feature).

Commit changes (git commit -m 'Add new feature').

Push to the branch (git push origin new-feature).

Create a Pull Request.

📜 License

This project is licensed under the MIT License.
