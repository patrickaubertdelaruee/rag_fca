## Put into .env
- PDF_DIR: root directory for the pdf files
- CHUNK_SIZE: chunk size for sentence-transformer
- CHUNK_OVERLAP: chunk overlap for sentence-transformer
- COHERE_API_KEY (only if using this llm)
- HUGGINGFACE_API_KEY (only if using models from here)

## Run a local weaviate and ollama instance
```bash
docker compose up -d
```

## Run
Step through the notebook
```bash
poetry install --no-root
poetry run jupyter-lab
```
