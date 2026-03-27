# Neoparse
Biomedical Literature Intelligence System


The repository is being prepared for public release. Final code and documentation will be available soon.

TECH STACK - Python, LangChain, ChromaDB, Sentence-Transformers, Gemini API, Streamlit 

TARGET-
~Architect end-to-end RAG pipeline over 50+ PubMed papers across TCR specificity, neoepitope cross-reactivity, and glioblastoma immunotherapy, automating literature synthesis from prior research workflows
~Engineer semantic chunking (400-token chunks, 50-token overlap) with sentence-transformer embeddings, cutting irrelevant chunk retrieval by 40% vs naive fixed-size splitting
~Eliminate citation hallucinations — baseline LLM misattributed citations in 6/10 domain queries vs 0/10 with RAG grounding over indexed biomedical corpus
~Deploy Streamlit interface with RAG vs baseline comparison across 3 embedding configs (MiniLM, BioBERT, OpenAI) for systematic retrieval quality benchmarking


### Main codebase will be added soon
