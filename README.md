## Introduction
Development of Chatbot using MCP servers (and pending: locally defined tools), in the Laravel framework.

## Protoypes
The prototypes below are the progression of the chatbot development, they can be found at `uv\src`
- `prototype1_CLI`
- `prototype2_WebIntegration`

## How to use `prototype2_WebIntegration`
- `prototype1_CLI` manual can be found in `uv\src\prototype1_CLI` (will be uploaded later)
### Create `.env` file in `uv` folder
```
LOGFIRE_TOKEN = 
GEMINI_API_KEY = 
```

### Create virtual environment and install python package dependencies
```
uv run sync
```

### At the root (the directory contains `uv` and `web`), open the project in VSC
`Ctrl + Shift + P` -> `Python: Select Interpreter` -> `Enter Interpreter Path` -> Find...(Browse) -> `uv\.venv\Scripts\python.exe`

### Run agent.py via VSC UI

### In `web`, run:
```
php artisan serve
```

### Visit the webpage
http://127.0.0.1:8000/

## Screenshot
<img width="1855" height="1019" alt="image" src="https://github.com/user-attachments/assets/922528d6-f4a7-42f8-bbaa-2cbfe45bfae4" />

