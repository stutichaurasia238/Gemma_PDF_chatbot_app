# Gemma_PDF_chatbot_app

SevaDoc: AI-Powered Document Search and Answering System-

SevaDoc is an AI-powered document search and answering system built with Streamlit, leveraging Google's Generative AI Embeddings and FAISS vector search. It provides accurate responses to user queries based on a corpus of documents.

Features-
* Document Search: Find relevant documents based on user queries.
* Answer Generation: Generate accurate answers from searched documents.
* Document Similarity Search: Explore similar documents to generated answers.
* Vector Embedding: Use FAISS vector search for fast document retrieval.

Getting Started-
1. Clone the Repository : git clone https://github.com/your-username/sevadoc.git

2. Install Dependencies : pip install -r requirements.txt

3. Set Environment Variables : 
export GROQ_API_KEY=your-groq-api-key
export GOOGLE_API_KEY=your-google-api-key
(Replace your-groq-api-key and your-google-api-key with your actual API keys)

5. Run the Application : streamlit run app.py

6. Upload Documents : Upload documents to the us_census directory. SevaDoc will automatically process them.

7. Usage:
* Open http://localhost:8501 in your web browser.
* Enter your query in the input field.
* Click "Documents Embedding" to initialize the vector store.
* Click "Ask" to get an answer based on the uploaded documents.

8. Recommendations:
* Use a substantial document corpus to enhance answer accuracy.
* Experiment with different vector embedding models for optimal performance.
* Integrate SevaDoc with other AI tools for advanced document analysis.

9. Troubleshooting:
* Check Streamlit logs for application errors.
* Ensure correct API keys and environment variables.
* Optimize vector embedding or reduce document corpus size for performance

10. Contributing:
SevaDoc welcomes community contributions via pull requests.

