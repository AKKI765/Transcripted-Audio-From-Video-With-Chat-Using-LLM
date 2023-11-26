# Transcripted-Audio-From-Video-With-Chat-Using-LLM

To build a project chat with audio using LLM using these packages 
and libraries, you would follow these steps:
1 Install the required packages and libraries. You can do this using pip:
pip install streamlit dotenv requests pytube langchain assemblyai chromadb
2 Create a python virtual environment .venv file. Create a .env file. This file will store your environment variables, such as your 
AssemblyAI API key, Open AI Key and your ChromaDB connection string.
3 Create a Streamlit app. This app will be responsible for handling the chat 
interface and the audio processing.
4 Use the AssemblyAI API to transcribe the audio input to text.
5 Use the LangChain embedding library to convert the text to a vector.
6 Use the LLM (Open AI) to generate a response to the text input.
7 Use the AssemblyAI API to generate text-to-speech output.
8 Send the text-to-speech output to the chat interface.
