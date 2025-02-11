# Medical ChatBot

A RAG (Retrieval-Augmented Generation) application created using LangChain, OpenAI, and Pinecone VectorDB.

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`OPENAI API KEY = "YOUR OPENAI API KAY"`

`PINECONE API KEY = "YOUR PINECONE API KEY"`


## Run Locally

Clone the project

```bash
  git clone https://github.com/kmsingh056/Medical_chatbot_genai
```

Go to the project directory

```bash
  cd Medical_chatbot_genai
```
Install conda environment

```bash
  conda create -n medicalbot python=3.12 -y
```
```bash
  conda activate medicalbot
```
Install dependencies

```bash
  pip install -r requirements.txt
```
```bash
  python store_index.py
```

Start the server

```bash
  python app.py
```


## Screenshots

![App Screenshot](https://github.com/kmsingh056/Medical_chatbot_genai/blob/main/static/Screenshot%20from%202025-02-11%2017-15-58.png?raw=true)

![App Screenshot](https://github.com/kmsingh056/Medical_chatbot_genai/blob/main/static/Screenshot%20from%202025-02-11%2017-15-44.png?raw=true)

