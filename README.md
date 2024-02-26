# LLMs with RAG 

### Description 

### Requirements 

Using python 3.9.5 and some packages in requirements.txt

    langchain
    torch
    accelerate
    sentence_transformers
    streamlit_chat
    streamlit
    faiss-cpu
    tiktoken
    huggingface-hub
    pypdf
    llama-cpp-python

### Checkpoints

You can download any LLMs checkpoint. In my task, I use [Mixtral-8x7B-Instruct-v0.1-GGUF](https://huggingface.co/TheBloke/Mixtral-8x7B-Instruct-v0.1-GGUF). Create folder models and put it in that. 

### Usage

**Step 1**: Prepare Env and Checkpoint 

**Step 2**: Run the `main.py` file using the Streamlit CLI. Execute the following command:
   ```
   streamlit run app.py
   ``` 