## Run a local weaviate instance
Set PERSISTENCE_DATA_PATH, e.g. ./data
```bash
docker compose up -d
```

## Put into .env
- PDF_DIR: root directory for the pdf files
- CHUNK_SIZE: chunk size for sentence-transformer
- CHUNK_OVERLAP: chunk overlap for sentence-transformer
- COHERE_API_KEY
- HUGGINGFACE_API_KEY

## Run
Step through the notebook
```bash
poetry install
poetry run jupyter-lab
```
