# PDFChat
This is a simple application that uses OpenAI's GPT-3.5-turbo to generate a conversation based on the text in a PDF file. The application is built using Streamlit and the PDF is converted to text using PyPDF2. The data from the PDF is indexed onto a vector database FAISS from where the closest match is found and the conversation is generated using OpenAI's Davinci engine.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/vikrambharadwaj1995/PDFChat
   cd into your directory/ open with vscode
   ```
2. Create a Virtual Environment:
    ```shell
    python -m venv env
    ```
3. Install the required dependencies:

   ```shell
   pip install -r requirements.txt
   ```
4. Create OpenAI API Key and add it to your .env file:
   [openai](https://platform.openai.com/)
   
5. Run the application:

   ```shell
   streamlit run App.py
   ```

## Next Steps
Will try replicating the same with LlaMa.
