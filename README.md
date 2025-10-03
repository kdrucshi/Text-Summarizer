# Text Summarization API (FastAPI + Docker)

🚀 A FastAPI microservice for text summarization using Hugging Face BART model.
The app is containerized with Docker for one-command deployment.

## Run Locally
uvicorn app:app --reload --port 8000

## Run with Docker
docker run -p 8000:8000 username/text-summarizer

## API Docs
Visit http://localhost:8000/docs to test the API interactively.
