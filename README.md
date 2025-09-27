Projects that I worked on for **Generative AI Product Management** certification

1. Lab2 is a **Legal Contract Analyzer.** Uses the specific contract documents with **RAG** legal analysis.
  * Transformers: This is a large and convenient package, that has many libraries for loading models from **HuggingFace**, fine tuning models, creating pipelines, loading
    tokenizers. This package is provided by Huggingface
  * faiss-cpu: This package is used for generating the faiss index using CPU, search and indexing is also done by CPU.
  * sentence-transformer: This well known package is used to transform sentences to embeddings.
  * langchain: This is yet another large and powerfull library used for many things like splitting sentences into chunks, making calls to OpenAI.
    They also have their own **FAISS** indexing library but will not use it from Langchain but the faiss library itself.
  * openai: This is used to call the openAI model.
  * python-dotenv: This is used to load all the keys in the environment from a .env file
  * PyMuPDF: This package is used for easy PDF manipulation.
  * tiktoken: This package is used to calculate the tokens in a text
