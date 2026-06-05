# RAG

## How to Install Virtual Environment Using UV

### 1. Install UV

```bash
pip install uv
```

### 2. Initialize Project

```bash
uv init
```

Output:

```text
Initialized project rag
```

### 3. Create Virtual Environment

```bash
uv venv .venv
```

Output:

```text
Using CPython 3.12.12 interpreter at: /Users/apple/miniforge3/bin/python3

Creating virtual environment at: .venv

Activate with:
source .venv/bin/activate
```

### 4. Activate Virtual Environment

```bash
source .venv/bin/activate
```

Output:

```text
(.venv) (base)
```

---

## Installing Packages Using UV

### Install dotenv

```bash
uv add dotenv
```

Output:

```text
Resolved 3 packages in 151ms
Prepared 2 packages in 39ms
Installed 2 packages in 4ms

dotenv==0.9.9
python-dotenv==1.2.2
```

### Install LangChain Dependencies

```bash
uv add langchain_groq \
       langchain_community \
       langchain_core \
       langchain-huggingface \
       langchain_google_genai \
       faiss-cpu \
       pypdf
```

---

## Run the Application

```bash
python app.py
```
