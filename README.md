# RAG


## How to install virtual env using UV

>> pip install uv
Requirement already satisfied: uv in /Users/apple/miniforge3/lib/python3.12/site-packages (0.10.2)
>> uv init
Initialized project `rag`
>> uv venv .venv
Using CPython 3.12.12 interpreter at: /Users/apple/miniforge3/bin/python3
Creating virtual environment at: .venv
Activate with: source .venv/bin/activate
>> source .venv/bin/activate
(.venv) (base) 

## For installing packages using uv ->

(.venv) (base) >> uv add dotenv
Resolved 3 packages in 151ms
Prepared 2 packages in 39ms
Installed 2 packages in 4ms
 + dotenv==0.9.9
 + python-dotenv==1.2.2

>> uv add langchain_groq langchain_community langchain_core langchain-huggingface langchain_google_genai faiss-cpu