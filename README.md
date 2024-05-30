# Medical-Chatbot

## Techstack Used:

- Llama2 (LLM model)
- Python
- LangChain
- ChromaDB

## How to run?

Clone the repository:

Project Repo: https://github.com/chiragsinghvi01/Medical-Chatbot.git

## STEPS: 

### Step 01: Create a conda environment after opening the repository

Open Git Bash terminal in your project folder and run this commands:

```bash
conda create -n medicalchatbot python -y
```

```bash
conda activate medicalchatbot
```

NOte: If you are not able to create the environment, run the command shown below first and then run the above commands.

```bash
source activate base
```
### Step 02: Install the requirements

```bash
pip install -r requirements.txt
```
Note: If you are having trouble while installing llama-cpp-python, and it's throwing error like - 'build wheel creation failed', then you can run the below code to install a pre-built wheel which will let you install llama-cpp.

```bash
pip install llama-cpp-python \
  --extra-index-url https://abetlen.github.io/llama-cpp-python/whl/cpu
```

## Download the LLM Model:

Model:
```bash
TheBloke/Llama-2-7B-Chat-GGUF
```

Model_basename:

```bash
llama-2-7b-chat.Q4_K_M.gguf
```

From the following link:

https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGUF/blob/main/llama-2-7b-chat.Q4_K_M.gguf
