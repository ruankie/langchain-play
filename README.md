[![GitHub Repo stars](https://img.shields.io/github/stars/ruankie/langchain-play)](https://github.com/ruankie/langchain-play)

# 🦜🔗👾 langchain-play
This repo can be used as a template to easily set up [LangChain](https://docs.langchain.com/docs/). LangChain is a framework for developing applications powered by language models.

You can find some [examples here](./notebooks/) for getting up to speed with the basics of LangChain.

> 🏗️ Under construction. More coming soon...

## Prerequisites
1. 🐍 You will need a working install of [`conda`](https://www.anaconda.com/download#downloads).
2. 🔑 You will need an API key from OpenAI. You can create one for free [here](https://platform.openai.com/account/api-keys).

## Usage
1. Set up your API keys in a file called `.env` (see `.env.example` for an example)
2. Set up and activate conda environment
    ```bash
    conda env create -f conda.yml
    conda activate langchain
    ```
3. Check out the examples:
   - Notebooks at `./notebooks/`
   - Scripts at `./src/`

## Useful Resources
- https://python.langchain.com/en/latest/index.html
- https://platform.openai.com/account/rate-limits
- https://platform.openai.com/docs/api-reference
- https://www.youtube.com/watch?v=_v_fgW2SkkQ&list=PLqZXAkvF1bPNQER9mLmDbntNfSpzdDIU5
- https://www.youtube.com/watch?v=MlK6SIjcjE8