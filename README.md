# Chatbot

<h2>Chatbots - Test cases</h2>
<h4>Listing various chatbots or Q/A bots build under different requirements and application methods</h4></n>
<h4><b>1. File name -  Rag_chatbot</b></h4></n>
<h6>This is the basic Q/A RAG based chatbot project focusing on data ingestion types ,Embeddings and Vector Database </h6>
<p>1.This Chatbot is build using 3 Data Ingestion techniques using langchain_community.document_loaders :-</p></n>
<p>i.TextLoader</p></n>
<p>ii.PdfLoader</p></n>
<p>iii.Website Loader</p></n>
<p>2.These input data is combined into single input and which is then transformed ,chunked and embedded. Used HuggingfaceEmbeddings , OpenAIEmbeddings</p></n>
<p>3.To store the embeddings in vector database  -ChromaDB , FAISS </p>

&nbsp;&nbsp;
<h4><b>2. File name - Chatbot_store_history </b></h4></n>
<h6>Chatbot that stores the chat history for reference and can answer the relevant questions using LLM model </h6>
