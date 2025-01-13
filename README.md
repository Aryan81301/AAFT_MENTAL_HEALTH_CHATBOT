# AAFT_MENTAL_HEALTH_CHATBOT
The AAFT Mental Health Chatbot with Multi-Purpose Work is an intelligent and interactive application designed to serve as a comprehensive assistant. It provides users with a specialized chatbot experience tailored to address mental health concerns while also offering versatile functionalities for document processing and universal search.


The chatbot described in the code is a **multi-purpose AI-driven conversational assistant** designed to cater to three main functionalities:
 **1. Mental Health Chatbot**
- **Objective:**  
  Provide support and assistance for users dealing with mental health issues such as stress, depression, and frustration.  
- **Capabilities:**  
  - **Emotional Support:** Acknowledges users' feelings and offers empathy to create a safe conversational space.  
  - **Suggested Strategies:** Recommends practical techniques such as mindfulness exercises, journaling, or breathing techniques.  
  - **Professional Help Guidance:** Encourages users to consult mental health professionals when needed.  
  - **Crisis Support:** Provides immediate helpline details if the user indicates severe distress.  
- **Additional Features:**  
  If the input query is unrelated to mental health, the chatbot redirects the user to use the "Universal Search" functionality.
 **2. PDF Chatbot**
- **Objective:**  
  Assist users in extracting and querying information from uploaded PDF documents efficiently.  
- **Capabilities:**  
  - Accepts a PDF document upload and processes its content by splitting it into manageable chunks for embedding into a **Pinecone** vector database.  
  - Utilizes embeddings and similarity search to retrieve relevant information from the document.  
  - Answers user queries related to the document with accurate and context-specific responses.  
- **Use Case:**  
  Ideal for analyzing research papers, legal documents, or reports.

3. Universal Search Chatbot**
- **Objective:**  
  Act as a general-purpose chatbot that can answer queries unrelated to mental health or PDF content by leveraging search engines.  
- **Capabilities:**  
  - Fetches real-time information from the web using the **Google Serper API** to answer user queries.  
  - Offers versatile support for queries about current events, general knowledge, and other non-specific topics.  
- **Use Case:**  
  Suitable for users looking for quick, reliable, and broad-spectrum answers.
 **Technical Overview**
- **Frameworks & Libraries:**  
  - **Streamlit:** Provides an interactive and user-friendly interface for accessing the chatbot’s features.  
  - **Pinecone:** Powers the document embedding and vector search functionality for the PDF chatbot.  
  - **LangChain:** Supports query workflows and language model interaction.  
  - **Transformers (Hugging Face):** Utilized for the summarization pipeline and response generation.  
- **APIs & Models:**  
  - **Together API & ChatTogether:** Used for language model interaction and context-based response generation.  
  - **Google Serper API:** Fetches search engine results for the Universal Search chatbot.

 **Target Audience**
- Individuals seeking mental health support or coping strategies.  
- Professionals needing document-specific insights from uploaded PDFs.  
- General users requiring real-time, web-based information for various queries.

---

This chatbot is a hybrid solution that combines mental health awareness with productivity and universal knowledge, making it a versatile tool for multiple user needs.
