
# AI Blog Generator using Llama2 🦙

This application uses Meta's Llama2 to generate blog posts from initial concept to final draft. Users can customize **content length**, **tone** and **style** to align with specific target audiences, whether researchers, data scientist or general readership. All done through a streamlined interface built using Streamlit.

- LLM model-> [LLama2](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/llama-2-7b-chat.ggmlv3.q8_0.bin)
- Framework-> [LangChain](https://github.com/langchain-ai/langchain)
- User Interface-> [Streamlit](https://docs.streamlit.io/)

## Demo 

https://github.com/user-attachments/assets/73db863e-69fa-4bcd-b242-a4eadb578e05

## Quick Start Guide
Install the model

[Llama2 Model](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/llama-2-7b-chat.ggmlv3.q8_0.bin)

Clone the project
```bash
  git clone https://link-to-project
```

Go to the project directory
```bash
  cd my-project
```
Run Conda command for venv on cmd
```bash
  conda create -p venv python==3.9 --y
```

Activate Conda
```bash
  conda activate venv/
```

Installing dependencies
```bash
  pip install -r requirements.txt
```

Paste the path directory of the Llama2 model
```bash
  llm = CTransformers(model=" Llama2-file-path  ")
```

You're good to go...
