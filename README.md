# Chat with a video using Lang Chain and OpenAI LLMs
This project utilizes Langchain, OpenAI, PyTube, Whisper, and Pinecone to process any video transcript from YouTube and engage in a conversation with the content.

## Setup
Install the required Python packages: pip install -r requirements.txt

## Set up environment variables:
Create a .env file with your OpenAI API key and Pinecone index name:

## Usage
Transcribe a YouTube video and get your questions answered:
Run the script to download audio from a YouTube video, transcribe it, split the transcription into documents, and perform document retrieval based on a question.