# Chat PDF with Gemini

This application allows users to interactively ask questions from PDF files using the Gemini model.

## Features

- Upload multiple PDF files.
- Ask questions based on the content of the uploaded PDF files.
- Receive answers to questions using the Gemini model.

## Setup

1. Install the required dependencies:

```bash
pip install -r requirements.txt
```


2. Set up Google API key:
- Obtain a Google API key and save it in a `.env` file:
  ```
  GOOGLE_API_KEY=your_api_key_here
  ```

3. Run the application:

```bash
streamlit run app.py
```


## Usage

1. Upload PDF files by clicking on the "Upload your PDF Files" button.
2. After uploading, click on the "Submit & Process" button to process the uploaded PDF files.
3. Ask questions in the text input field provided.
4. Click on the "Ask Question" button to receive answers based on the content of the uploaded PDF files.

## Dependencies

- Streamlit
- PyPDF2
- Langchain
- Google Generative AI
- FAISS
- dotenv

## Contributors

- [Pratik Nagdeve](https://github.com/pratik-nagdeve)

---
Feel free to customize this README file further based on your project's specific requirements and features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

