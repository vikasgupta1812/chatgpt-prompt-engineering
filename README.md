# ChatGPT Prompt Engineering for Developers
Jupyter code notebooks of "ChatGPT Prompt Engineering for Developers" by DeepLearning.AI and OpenAI.

In ChatGPT Prompt Engineering for Developers, you will learn how to use a large language model (LLM) to quickly build new and powerful applications.  Using the OpenAI API, you’ll be able to quickly build capabilities that learn to innovate and create value in ways that were cost-prohibitive, highly technical, or simply impossible before now.

This short course taught by Isa Fulford (OpenAI) and Andrew Ng (DeepLearning.AI) will describe how LLMs work, provide best practices for prompt engineering, and show how LLM APIs can be used in applications for a variety of tasks, including:

- Summarizing (e.g., summarizing user reviews for brevity)
- Inferring (e.g., sentiment classification, topic extraction)
- Transforming text (e.g., translation, spelling & grammar correction)
- Expanding (e.g., automatically writing emails)

In addition, you’ll learn two key principles for writing effective prompts, how to systematically engineer good prompts, and also learn to build a custom chatbot. 

All concepts are illustrated with numerous examples, which you can play with directly in our Jupyter notebook environment to get hands-on experience with prompt engineering. 

| **notebook** | **open in colab** |
|:------------|:-------------------------------------------------:|
| [1-guidelines](https://github.com/vikasgupta1812/chatgpt-prompt-engineering/blob/main/1-guidelines.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vikasgupta1812/chatgpt-prompt-engineering/blob/main/1-guidelines.ipynb)|
| [2-iterative](https://github.com/vikasgupta1812/chatgpt-prompt-engineering/blob/main/2-iterative.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vikasgupta1812/chatgpt-prompt-engineering/blob/main/2-iterative.ipynb)|
| [3-summarizing](https://github.com/vikasgupta1812/chatgpt-prompt-engineering/blob/main/3-summarizing.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vikasgupta1812/chatgpt-prompt-engineering/blob/main/3-summarizing.ipynb)|
| [4-inferring](https://github.com/vikasgupta1812/chatgpt-prompt-engineering/blob/main/4-inferring.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vikasgupta1812/chatgpt-prompt-engineering/blob/main/4-inferring.ipynb)|
| [5-transforming](https://github.com/vikasgupta1812/chatgpt-prompt-engineering/blob/main/5-transforming.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vikasgupta1812/chatgpt-prompt-engineering/blob/main/5-transforming.ipynb)|
| [6-expanding](https://github.com/vikasgupta1812/chatgpt-prompt-engineering/blob/main/6-expanding.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vikasgupta1812/chatgpt-prompt-engineering/blob/main/6-expanding.ipynb)|
| [7-chatbot](https://github.com/vikasgupta1812/chatgpt-prompt-engineering/blob/main/7-chatbot.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vikasgupta1812/chatgpt-prompt-engineering/blob/main/7-chatbot.ipynb)|





# Launch jupyter server 

https://github.dev/vikasgupta1812/chatgpt-prompt-engineering

```
jupyter notebook --no-browser --NotebookApp.allow_origin_pat=https://.*vscode-cdn\.net
```


```
jupyter notebook \
    --NotebookApp.allow_origin='https://colab.research.google.com' \
    --port=8888 \
    --NotebookApp.port_retries=0
```    

```
jupyter notebook ^
    --NotebookApp.allow_origin="https://colab.research.google.com" ^
    --port=8888 ^
    --NotebookApp.port_retries=0
```