# Ironhack AI Engineering Bootcamp: Labs

**My solutions to the weekly labs of the Ironhack AI Engineering Bootcamp (2026), from Python basics to multi-agent LLM systems.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)

> **In short:** this repository bundles the hands-on exercises that took me from Python fundamentals through classical machine learning, deep learning and NLP to LLM fine-tuning, LangChain agents and RAG evaluation. The exercises come from Ironhack's curriculum; the solutions are my own work.
>
> For complete, end-to-end projects, see the pinned repositories on [my profile](https://github.com/DarmontDomienAntwerpen).

---

## Learning path

| Week | Topic | Highlights |
|---|---|---|
| [01](week-01-python) | Python for data | Functions, OOP, error handling, NumPy, pandas |
| [02](week-02-machine-learning) | Machine learning | Linear & logistic regression, decision trees, SVM, k-means, model evaluation |
| [03](week-03-neural-networks) | Deep learning | Neural networks and CNNs with Keras (MNIST, CIFAR-10) |
| [04](week-04-nlp) | Natural language processing | Text preprocessing, regex, embeddings, text generation, fake-news classifier |
| [05](week-05-sql-and-llm-finetuning) | SQL, prompting & fine-tuning | SQL, text-to-SQL, prompt engineering, LoRA / QLoRA / prompt tuning with PEFT |
| 06 | MLOps | Deployment (group work, not included) |
| [07](week-07-langchain-agents) | LangChain & agents | Chains, tools, vector stores, multi-query retrieval, BabyAGI, multi-agent bidding |
| [08](week-08-multimodal-rag-and-evaluation) | Multimodal RAG & evaluation | CLIP image search, multimodal RAG with Chroma, LCEL, LangSmith evaluation |

## Running a notebook

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install jupyter pandas numpy scikit-learn matplotlib seaborn
jupyter lab
```
Each lab lists its own extra libraries in its first cells. Labs that call an LLM read the key from the `OPENAI_API_KEY` environment variable.

## Author
**Domien Darmont**, AI Engineer, Antwerp, Belgium
GitHub: [@DarmontDomienAntwerpen](https://github.com/DarmontDomienAntwerpen)
