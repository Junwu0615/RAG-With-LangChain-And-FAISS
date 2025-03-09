<a href='https://github.com/Junwu0615/RAG-With-LangChain-And-FAISS'><img alt='GitHub Views' src='https://views.whatilearened.today/views/github/Junwu0615/RAG-With-LangChain-And-FAISS.svg'> 
<a href='https://github.com/Junwu0615/RAG-With-LangChain-And-FAISS'><img alt='GitHub Clones' src='https://img.shields.io/badge/dynamic/json?color=success&label=Clone&query=count_total&url=https://gist.githubusercontent.com/Junwu0615/4809a357894e05e277dd8c3c3e278ce8/raw/RAG-With-LangChain-And-FAISS_clone.json&logo=github'> <br>
[![](https://img.shields.io/badge/Project-LLM_API-blue.svg?style=plastic)](https://github.com/Junwu0615/RAG-With-LangChain-And-FAISS)
[![](https://img.shields.io/badge/Project-RAG-blue.svg?style=plastic)](https://github.com/Junwu0615/RAG-With-LangChain-And-FAISS)
[![](https://img.shields.io/badge/Language-Python_3.12.0-blue.svg?style=plastic)](https://www.python.org/) <br>
[![](https://img.shields.io/badge/Package-LangChain_0.3.19-green.svg?style=plastic)](https://pypi.org/project/langchain/) 
[![](https://img.shields.io/badge/Package-FAISS_CPU_1.10.0-green.svg?style=plastic)](https://pypi.org/project/faiss-cpu/) 
[![](https://img.shields.io/badge/Package-Google_Generativeai_0.8.4-green.svg?style=plastic)](https://pypi.org/project/google-generativeai/) <br> 
<br>

## *⭐ 用 LangChain + FAISS 實作 RAG ⭐*

### *A.　Current Progress*
|項目|敘述|完成時間|
|:--:|:--|:--:|
| 專案上架 | - | 2025-02-28 |
| Google Gemini | 用 Gemini 實作 RAG | 2025-02-28 |
| OpenAI ChatGPT | 用 ChatGPT 實作 RAG | 2024-03-09 |
| MediaTek Breeze | 用 Breeze 實作 RAG | - |
| Meta LLama | 用 LLama 實作 RAG | - |
| Fine-tung Embedding | 嘗試不同 Embedding | - |
| Fine-tung Vector DB | 嘗試不同 Vector DB : ChromaDB | - |
| Other | 連接 Google Cloud Vertex AI 來增強檢索能力 | - |

<br>

### *B.　RAG Definition*
- #### *RAG : Retrieval-Augmented Generation*
- #### *實現方式 : LLM API + Vector Database + Word Embeddings = RAG System*
  - #### *LLM API : 負責生成回答*
  - #### *Vector Database : 負責存儲並檢索相關知識*
    - #### [*FAISS*](https://huggingface.co/learn/nlp-course/zh-TW/chapter5/6)
    - #### [*ChromaDB*](https://cookbook.chromadb.dev/core/install/)
  - #### *Word Embeddings : 負責將文本轉換為向量，讓系統能夠計算相似性*
- #### *RAG 可讓 LLM 生成更準確的回答，但依舊有幻覺可能性*
- #### *此法非涉及訓練相關，依舊是以 Prompt Engineering 工程角度來解決問題*

<br>

### *C.　Showcase Results*
```bash
jupyter nbconvert --execute --to html ???.ipynb
```
- #### [*Google Gemini + FAISS*](https://junwu0615.github.io/RAG-With-LangChain-And-FAISS/RAG-Gemini.html)
- #### [*OpenAI ChatGPT + FAISS*](https://junwu0615.github.io/RAG-With-LangChain-And-FAISS/RAG-GPT.html)
- #### *Breeze2 + FAISS*
- #### *LLama2 + FAISS*