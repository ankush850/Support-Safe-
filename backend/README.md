# 🚀 Getting Started (Local Development)

### 1. Activate Virtual Environment (Windows)
```bash
.\.venv\Scripts\Activate
```

# Install Dependencies
```
pip install -r requirementx.txt
```


 Run the Backend Server
```bash
fastapi dev backend/main.py
```

API Documentation
```
Open in browser:
http://127.0.0.1:8000/docs
```

Deployment (Render)

Install Dependencies
```bash
pip install -r backend/requirements.txt
```

Run Server
```bash
uvicorn backend.main:app --host 0.0.0.0 --port 9000
```

### Project Structure
```
ProjectX/
├── backend/
│   ├── main.py
│   └── requirements.txt
├── .venv/
├── requirementx.txt
└── README.md
```

## Notes
Create .venv before activating it

Use requirementx.txt for development

Use backend/requirements.txt for deployment

Local server runs on port 8000

Production server runs on port 9000
