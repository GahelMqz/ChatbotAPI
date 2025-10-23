cd .\rag_api\

pip install -r requirements.txt

.venv\Scripts\Activate.ps1

uvicorn app:app --reload --host 0.0.0.0 --port 8000


# http://localhost:8000/docs