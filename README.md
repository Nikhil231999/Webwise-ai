# WebWise AI 🌐

An AI-powered research assistant that answers questions using content extracted from user-provided URLs.

### Features
- Process multiple website URLs
- Ask questions in natural language
- Retrieve relevant content using RAG
- Generate context-grounded answers using an LLM
- Display source links for answers

### Tech Stack
Python · Streamlit · LangChain · ChromaDB · Hugging Face Embeddings · Groq LLM

### Run Locally
1. Clone this repository.
2. Install dependencies:
   `pip install -r requirements.txt`
3. Add your `GROQ_API_KEY` to a `.env` file.
4. Start the application:
   `streamlit run main.py`

### Note
Website access depends on the source site's permissions and content availability.
