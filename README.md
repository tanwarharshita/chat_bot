# CHAT BOT FOR UNI OF EXETER
Chatbot using Retrieval Augmented Generation with Astra DB and the OpenAI Chat Model.
# Build your own RAG Chatbot
1) It leverages DataStax RAGStack, which is a curated stack of the best open-source software for easing implementation of the RAG pattern in production-ready applications that use Astra Vector DB or Apache Cassandra as a vector store.
2) Uses OpenAI's Large Language Models for Q&A style chatbots
3) Uses Streamlit to easily deploy the awesome app to the internet for everyone to see!
4) Combines with the Astra DB Vector Store for additional context related to the University of Exeter
5) Designed for the use of the undergraduate student to ask questions provided by a pdf document. It contains information about the university, its locations, contact informations, term dates, various courses offered for 2024-25 applicants.
# Python environments
In case you want to run all of the above locally, it's useful to create a *Virtual Environment*. Use the below to set it up:
```
python3 -m venv myenv
```
Then activate it as follows:
```
source myenv/bin/activate   # on Linux/Mac
myenv\Scripts\activate.bat  # on Windows
```
Now you can start installing packages:
```
pip3 install -r requirements.txt
```
In order to check which packages have been installed:
```
pip3 freeze
```
Which you can save to requirements.txt if you want:
```
pip3 freeze > requirements.txt
```
