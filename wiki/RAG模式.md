# RAG 模式

RAG（Retrieval-Augmented Generation，检索增强生成）是[[AI Agent]]在生成回答前先从外部知识库检索相关信息，再把检索结果作为上下文交给大语言模型的架构模式。

其目标是利用可维护的外部资料补充模型已有知识，提高回答的相关性和准确性。RAG 通常使用[[Vector Store]]进行语义检索，也可通过[[MCP协议]]连接外部知识源或检索工具。

## 来源

- `raw/LLM_Agent_Architecture.md`

