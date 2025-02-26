# AI Chatbot using OpenAI and LangChain

This is a generative AI chatbot built using Python, leveraging OpenAI's API for natural language processing. The chatbot is designed to process and answer questions based on PDF documents. It utilizes LangChain for text processing and FAISS for vector storage.

## Features
- Upload PDF documents for processing
- Extract and split text using LangChain
- Store embeddings in FAISS for efficient retrieval
- Answer user queries using OpenAI's GPT model
- Interactive UI built with Streamlit

## Technologies Used
- **Python** (Main programming language)
- **Streamlit** (Frontend UI framework)
- **PyPDF2** (PDF text extraction)
- **LangChain** (Text processing and retrieval)
- **FAISS** (Efficient vector storage and retrieval)
- **OpenAI API** (Chat model for generating responses)

## Installation

### Prerequisites
Ensure you have Python installed on your system.

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/Anuj644/chatbot-using-generative-AI.git
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Set up OpenAI API key:
   ```sh
   export OPENAI_API_KEY='your-api-key'  # On Windows: set OPENAI_API_KEY=your-api-key
   ```

## Usage
Run the Streamlit app using:
```sh
streamlit run app.py
```

Then, open the provided URL in your browser to interact with the chatbot.

## Folder Structure
```
📂 your-repo/
 ├── 📄 app.py             # Main application file
 ├── 📂 data/             # Folder to store uploaded PDFs
 ├── 📄 requirements.txt   # List of dependencies
 ├── 📄 README.md          # Project documentation
```

## Contributing
Feel free to fork this repository and submit pull requests with improvements or new features.

## License
This project is licensed under the MIT License.

