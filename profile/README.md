<p align="center">
  <a href="https://meetdewey.com">
    <img src="logo.png" alt="Dewey" width="120" />
  </a>
</p>

## Dewey

  Real-time document backend for AI applications. Upload a document collection and Dewey handles conversion, section
  extraction, chunking, and embedding. All immediately queryable via REST API, TypeScript/Python SDKs, or directly inside
   Claude, ChatGPT, and Cursor via MCP.

  **[meetdewey.com](https://meetdewey.com)** · **[Product](https://meetdewey.com/product)** · **[Docs](https://meetdewey.com/docs)** ·
  **[Pricing](https://meetdewey.com/pricing)**

  ---

  ### Open-source packages

  | Package | Description |
  |---|---|
  | [`@meetdewey/mcp`](https://github.com/meetdewey/mcp) | MCP server — use your document collections in Claude, ChatGPT, and Cursor |
  | [`@meetdewey/sdk`](https://github.com/meetdewey/typescript-sdk) | Official TypeScript SDK |
  | [`meetdewey`](https://github.com/meetdewey/python-sdk) | Official Python SDK |
  | [`langchain-dewey`](https://github.com/meetdewey/langchain-dewey) | LangChain integration — retriever, vector store, and research tool |
  | [`llama-index-retrievers-dewey`](https://github.com/meetdewey/llama-index-retrievers-dewey) | LlamaIndex integration — retriever for hybrid search and section-aware retrieval |
  | [`@meetdewey/vercel-ai`](https://github.com/meetdewey/vercel-ai-dewey) | Vercel AI SDK integration — retrieval and research tools |
  | [`dewey-haystack`](https://github.com/meetdewey/dewey-haystack) | Haystack integration — document store, retriever, and research component |
  | [`streamlit-demo`](https://github.com/meetdewey/streamlit-demo) | Streamlit demo app — build a document Q&A UI in minutes |

  ### Quick start

  ```bash
  # MCP — add to Claude Desktop, ChatGPT, or Cursor
  npx -y @meetdewey/mcp

  # TypeScript
  npm install @meetdewey/sdk

  # Python
  pip install meetdewey

  # LangChain
  pip install langchain-dewey

  # LlamaIndex
  pip install llama-index-retrievers-dewey

  # Vercel AI SDK
  npm install @meetdewey/vercel-ai

  # Haystack
  pip install dewey-haystack
  ```

  Sign up at [meetdewey.com](https://meetdewey.com) to get an API key. Free tier available, no credit card required.
