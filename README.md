

#  📄 Introduction to PageIndex

Are you frustrated with vector database retrieval accuracy for long professional documents? Traditional vector-based RAG relies on semantic *similarity* rather than true *relevance*. But **similarity ≠ relevance** — what we truly need in retrieval is **relevance**, and that requires **reasoning**. When working with professional documents that demand domain expertise and multi-step reasoning, similarity search often falls short.

Inspired by AlphaGo, we propose **[PageIndex](https://vectify.ai/pageindex)**, a **reasoning-based RAG** system that simulates how **human experts** navigate and extract knowledge from long documents through **tree search**, enabling LLMs to *think* and *reason* their way to the most relevant document sections. It performs retrieval in two steps:

1. Generate a "Table-of-Contents" **tree structure index** of documents
2. Perform reasoning-based retrieval through **tree search**

<div align="center">
    <img src="https://docs.pageindex.ai/images/cookbook/vectorless-rag.png" width="90%">
</div>

### 💡 Features 

Compared to traditional vector-based RAG, PageIndex features:
- **No Vectors Needed**: Uses document structure and LLM reasoning for retrieval.
- **No Chunking Needed**: Documents are organized into natural sections, not artificial chunks.
- **Human-like Retrieval**: Simulates how human experts navigate and extract knowledge from complex documents.
- **Transparent Retrieval Process**: Retrieval based on reasoning — say goodbye to approximate vector search ("vibe retrieval").

