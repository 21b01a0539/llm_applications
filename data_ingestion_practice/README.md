# 📥 Data Ingestion with LangChain Document Loaders

This project leverages **LangChain's document loaders** to ingest data from multiple sources, making it easier to build flexible and scalable language model applications.

🔗 **Official Docs:** [LangChain Document Loaders](https://python.langchain.com/v0.2/docs/integrations/document_loaders/)

---

## ✅ Supported Document Sources

LangChain supports ingestion from various sources including:

- **Local Files:** `.txt`, `.pdf`, `.docx`, `.csv`, etc.
- **Web Pages:** Using `WebBaseLoader` or `AsyncHtmlLoader`.
- **Cloud Platforms:** Google Drive, AWS S3, Notion, etc.
- **APIs and Databases:** SQL, MongoDB, REST APIs.
- **Third-Party Apps:** Slack, Confluence, etc.

---

## ✂️ Text Splitters

Text splitters are used to divide long documents into manageable chunks suitable for embedding and querying. This is crucial for effective retrieval in large documents.

🔗 **Official Docs:** [LangChain Text Splitters](https://python.langchain.com/docs/concepts/text_splitters/)

### Common Text Splitters:
- **CharacterTextSplitter:** Splits based on character count.
- **RecursiveCharacterTextSplitter:** Smarter splitting that tries different strategies hierarchically (e.g., splitting by paragraph, then sentence, then word).
- **TokenTextSplitter:** Splits text based on token limits (useful with models like OpenAI or HuggingFace).
- **MarkdownHeaderTextSplitter:** Splits based on markdown headers.
- **HTMLHeaderTextSplitter:** Tailored for structured HTML content.

---

## 🧠 Embedding Techniques

Embedding models convert chunks of text into vector representations, enabling semantic search and similarity-based retrieval.

🔗 **Official Docs:** [LangChain Text Embedding](https://python.langchain.com/docs/integrations/text_embedding/)
