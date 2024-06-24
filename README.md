<h1>SevaDoc: AI-Powered Document Search and Answering System</h1> <p align="center"> <img src="https://github.com/stutichaurasia238/Gemma_PDF_chatbot_app/assets/145449188/5667270d-4437-4f0c-8192-97512f17a79f" alt="SevaDoc Opening Image"> </p>
SevaDoc is a cutting-edge document search and answering system built with Streamlit, leveraging Google's Generative AI Embeddings and FAISS vector search. It provides accurate responses to user queries based on a corpus of documents.

<h2>Key Features</h2>
Document Search: Find relevant documents based on user queries.Document Search

Answer Generation: Generate accurate answers from searched documents.Answer Generation

Document Similarity Search: Explore similar documents to generated answers.Document Similarity Search

Vector Embedding: Use FAISS vector search for fast document retrieval.Vector Embedding

<h2>Getting Started</h2>
Clone the Repository
git clone https://github.com/your-username/sevadoc.git

Install Dependencies
pip install -r requirements.txt

Libraries
Streamlit: For its ease of use and flexibility in building and deploying web applications.
LangChain Library: For its ability to generate accurate and relevant answers based on the searched documents.
FAISS: For its fast and efficient document retrieval capabilities.
Google's Generative AI Embeddings: For its ability to generate high-quality vector embeddings of documents.
Groq: For its ability to efficiently query and index the document corpus.
Gemma model: For its ability to generate accurate and relevant answers.
Set Environment Variables

Open In Editor
Edit
Copy code
export GROQ_API_KEY=your-groq-api-key
export GOOGLE_API_KEY=your-google-api-key
Replace your-groq-api-key and your-google-api-key with your actual API keys.

Run the Application
streamlit run app.py

Upload Documents
Upload documents to the us_census directory. SevaDoc will automatically process them.

Usage
Open http://localhost:8501 in your web browser.
Enter your query in the input field.
Click "Documents Embedding" to initialize the vector store.
Click "Ask" to get an answer based on the uploaded documents.
<h2>Recommendations</h2>
Use a substantial document corpus to enhance answer accuracy.
Experiment with different vector embedding models for optimal performance.
Integrate SevaDoc with other AI tools for advanced document analysis.
<h2>Troubleshooting</h2>
Check Streamlit logs for application errors.
Ensure correct API keys and environment variables.
Optimize vector embedding or reduce document corpus size for performance.
<h2>Contributing</h2>
SevaDoc welcomes community contributions via pull requests.
