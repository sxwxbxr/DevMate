# DevMate
Lokaler KI Helfer fuer Programmieren mit Kontext aus eigenen Repos und Docs.

## Ziel
Fragen beantworten Code erklaeren und Beispiele generieren auf Basis lokaler Wissensbasis.

## Features
* Embedding Index aus Repos und Markdown
* Frage Antwort ueber lokales LLM oder API
* VS Code Extension fuer Inline Hilfe
* Quellenangaben

## Tech Stack
* Python FastAPI
* llama cpp python oder OpenAI API optional
* ChromaDB oder FAISS
* VS Code Extension TypeScript

## Kritische Packages
* fastapi
* langchain
* chromadb
* llama cpp python
* tiktoken optional
* pyyaml

## Env Variablen
* MODEL_PATH oder OPENAI_API_KEY

## API
* POST ingest
* POST ask
* GET sources

## Setup
* uvicorn main
* code extension im Ordner extension

## Tests
* Retrieval Recall fuer Samples

## CI
* Build Index gegen Beispiel Repo

## Security
* Nur lokale Pfade whitelisten

## Roadmap
* Multi Repo Kontexte
* Inline Code Actions

## Lizenz
Apache 2
