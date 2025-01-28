
# FileBot
An LLM powered FileBot Streamlit app so you can chat with your CSV files.

## Introduction
The FileBot Chat App is a Python application that allows you to chat with CSV documents. You can ask questions about the CSVs using natural language, and the application will provide relevant responses based on the content of the documents. This app utilizes a language model to generate accurate answers to your queries. Please note that the app will only respond to questions related to the loaded CSVs.

## How It Works
![Uploading image.png…](images/FileBot_flowchart.png)

The application follows these steps to provide responses to your questions:

1. CSV Loading: The app reads CSV documents and extracts their text content.

2. Text Chunking: The extracted text is divided into smaller chunks that can be processed effectively.

3. Language Model: The application utilizes a language model to generate vector representations (embeddings) of the text chunks.

4. Similarity Matching: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.

5. Response Generation: The selected chunks are passed to the language model, which generates a response based on the relevant content of the CSVs.

## To install the FileBot Chat App, please follow these steps:

1. Clone the repository to your local machine.

2. Install the required dependencies by running the following command:

```
pip install -r requirement.txt
```

## Usage
To use the FileBot App, follow these steps:

1. Ensure that you have installed the required dependencies.

2. Run the FILEBOT.py file using the Streamlit CLI. Execute the following command:

```
streamlit run FILEBOT.py
```

3. The application will launch in your default web browser, displaying the user interface.

![Uploading image.png…](images/FileBot_image1.jpeg)

4. Load CSV documents into the app by clicking on Browse_files button on the left side of the screen.

![Uploading image.png…](images/FileBot_image2.jpeg)

5. Ask questions in natural language about the loaded CSVs using the chat interface.

![Uploading image.png…](images/FileBot_image3.jpeg)

## conclusion

Leverage the power of AI to transform your local files into readily digestible content. This Python chatbot, armed with the summarizing prowess of Llama2 and the user-friendly interface of Streamlit, streamlines your workflow and unlocks valuable insights hidden within your documents. Whether you're tackling lengthy reports or condensing research papers, this AI assistant becomes your secret weapon for maximizing your productivity and extracting the essence of your local content.
