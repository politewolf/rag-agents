# 🚀 RAG Agents

This collection features over 20 unique implementations of Retrieval-Augmented Generation (RAG) and Agentic RAG patterns, ranging from simple local setups to advanced agentic workflows with reasoning.

## 📂 Featured RAG Implementations

| Category              | Implementation                                                   | Description                                                    |
| :-------------------- | :--------------------------------------------------------------- | :------------------------------------------------------------- |
| **Agentic RAG**       | [Agentic RAG with EmbeddingGemma](./agentic_rag_embedding_gemma) | Uses Google's EmbeddingGemma and Llama 3.2 via Ollama.         |
|                       | [Agentic RAG with GPT-5](./agentic_rag_gpt5)                     | Advanced agentic workflow utilizing GPT-5 (mock/early access). |
|                       | [Gemini Agentic RAG](./gemini_agentic_rag)                       | Agentic RAG powered by Google's Gemini models.                 |
|                       | [Autonomous RAG](./autonomous_rag)                               | Self-improving and autonomous retrieval agents.                |
| **Local RAG**         | [Llama 3.1 Local RAG](./llama3.1_local_rag)                      | Fully local RAG setup using Llama 3.1 and Ollama.              |
|                       | [DeepSeek Local RAG Agent](./deepseek_local_rag_agent)           | Local agent using DeepSeek Coder/V2 models.                    |
|                       | [Qwen Local RAG](./qwen_local_rag)                               | Local implementation featuring Qwen2.5 models.                 |
| **Advanced Patterns** | [Corrective RAG (CRAG)](./corrective_rag)                        | Implements self-correction mechanisms for retrieval.           |
|                       | [Agentic RAG with Reasoning](./agentic_rag_with_reasoning)       | Incorporates Chain-of-Thought reasoning into RAG.              |
|                       | [Contextual AI RAG Agent](./contextualai_rag_agent)              | Focuses on maintaining context across multi-turn interactions. |
| **Specialized RAG**   | [Vision RAG](./vision_rag)                                       | RAG for multimodal data (images and text).                     |
|                       | [Math Agent RAG](./agentic_rag_math_agent)                       | Specialized agent for solving mathematical problems with RAG.  |
|                       | [AI Blog Search](./ai_blog_search)                               | RAG-powered search engine for technical blogs.                 |
| **Search & Routing**  | [Hybrid Search RAG](./hybrid_search_rag)                         | Combines keyword (BM25) and vector search.                     |
|                       | [Database Routing RAG](./rag_database_routing)                   | Intelligent routing between different data sources.            |

## 🛠️ General Setup

Most projects in this repository utilize **Streamlit** for the UI and **Ollama** for local LLM execution.

### Prerequisites

- Python 3.9+
- [Ollama](https://ollama.com/) (for local models)
- OpenAI API Key (for GPT-based tutorials)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/politewolf/rag-agents.git
   cd rag-agents
   ```
2. Each folder contains its own requirements. Navigate to a specific tutorial and install:
   ```bash
   pip install -r requirements.txt
   ```

## 🧰 Technologies Used

- **Frameworks**: Agno, LangChain, Streamlit
- **Models**: Llama 3.1/3.2, DeepSeek, Qwen2.5, Gemini, GPT-4o
- **Vector DBs**: LanceDB, ChromaDB, FAISS
- **Embeddings**: EmbeddingGemma, OpenAI, HuggingFace

## 📜 License

This project is licensed under the MIT License.
