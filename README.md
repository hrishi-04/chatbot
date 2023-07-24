# chatbot
This chatbot, designed on the Streamlit platform and powered by Lang Chain and OpenAI technologies.
It serves as a user-friendly tool to answer inquiries about Pan card documents.
By leveraging embeddings and OpenAI's language model, it delivers contextually relevant responses. 
Users can ask questions about their Pan card procedures, and the chatbot intelligently processes their queries. 
Splitting the knowledge document into smaller text chunks allows for efficient information retrieval. 
With its conversational retrieval chain and advanced language model, the chatbot ensures accurate and well-informed answers. 


# setup 
please setup the virtual environment with all the given dependencies for this repo 
ensure that the file knowledge_doc.txt and htmlTemplates.py are present in the same folder/directory as in app2.py code

# running
It is important that you run this application after getting all the files of this repo in your own directory locally 
Run it by the command - streamlit run app2.py 

# IMPORTANT - 
This program calls openai's APIs for the embeddings and the llms if possible please provide your own keys in the file named .env in the directory.
create your own .env file in your directory and copy the contents of my .env folder or provide your own keys in the same format.
This is a paid service by openAI but the cost is very minimal.
I am including my APIkey in the .env folder anyways 
