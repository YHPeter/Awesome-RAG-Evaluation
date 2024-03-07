# Awesome RAG Evaluation

<p align="center"> English | <a href="README_cn.md"> 简体中文 </a></p>

The official repository for the paper: *Evaluation of Retrieval-Augmented Generation: A Survey* [Arxiv](https://arxiv.org/pdf/2405.07437). This paper has been accepted by the [2024 CCF Big Data](https://ccf.org.cn/BigData2024).

### Abstract

Retrieval-Augmented Generation (RAG) has recently gained traction in natural language processing. Numerous studies and real-world applications are leveraging its ability to enhance generative models through external information retrieval. Evaluating these RAG systems, however, poses unique challenges due to their hybrid structure and reliance on dynamic knowledge sources. To better understand these challenges, we conduct **A** **U**nified **E**valuation **P**rocess **o**f **RA**G (*Auepora*) and aim to provide a comprehensive overview of the evaluation and benchmarks of RAG systems. Specifically, we examine and compare several quantifiable metrics of the Retrieval and Generation components, such as relevance, accuracy, and faithfulness, within the current RAG benchmarks, encompassing the possible output and ground truth pairs. We then analyze the various datasets and metrics, discuss the limitations of current benchmarks, and suggest potential directions to advance the field of RAG benchmarks.


### Analysis Framework for Evaluating RAG Systems

<!-- <p align="center">
    <img src="figures/rag-structure-2.png" alt="drawing" width=70% />
</p>

* Figure 1. The structure of the RAG system with retrieval and generation components and corresponding four phrases: indexing, search, prompting, and inferencing. The pairs of EOs and GTs are highlighted in red and green, with brown dashed arrows. -->

<p align="center">
    <img src="figures/aspect-display-4.png" alt="drawing" width=90% />
</p>

* The **Target** modular of *Auepora*. The retrieval and generation components are highlighted in red and green, respectively.

### Reference Framework
<p align="center">
    <img src="figures/relative-work-2.png" alt="drawing" width=80% />
</p>

| Category | Framework | Webpage | Paper |
|---|---|---|---|
| Tool | TruEra RAG Triad | https://www.trulens.org/trulens_eval/getting_started/core_concepts/rag_triad/ | - |
| Tool | LangChain Bench. | https://langchain-ai.github.io/langchain-benchmarks/notebooks/retrieval/langchain_docs_qa.html | - |
| Tool | Databricks Eval | https://www.databricks.com/blog/LLM-auto-eval-best-practices-RAG | - |
| Benchmark | RAGAs | https://github.com/explodinggradients/ragas | https://aclanthology.org/2024.eacl-demo.16/ |
| Benchmark | RECALL | - | https://arxiv.org/abs/2311.08147 |
| Benchmark | ARES | https://github.com/stanford-futuredata/ARES | https://arxiv.org/abs/2311.09476 |
| Benchmark | RGB | https://github.com/chen700564/RGB | https://ojs.aaai.org/index.php/AAAI/article/view/29728 |
| Benchmark | MultiHop-RAG | https://github.com/yixuantt/MultiHop-RAG/ | https://arxiv.org/abs/2401.15391 |
| Benchmark | CRUD-RAG | https://github.com/IAAR-Shanghai/CRUD_RAG | https://arxiv.org/abs/2401.17043v2 |
| Benchmark | MedRag | https://github.com/Teddy-XiongGZ/MedRAG | http://arxiv.org/abs/2402.13178v2 |
| Benchmark | FeB4RAG | https://github.com/ielab/FeB4RAG | http://arxiv.org/abs/2402.11891v1 |
| Benchmark | CDQA | https://github.com/Alibaba-NLP/CDQA | https://arxiv.org/abs/2402.19248v2 |
| Benchmark | DomainRAG | https://github.com/ShootingWong/DomainRAG | https://arxiv.org/abs/2406.05654v2 |
| Benchmark | ReEval | https://autodebug-llm.github.io | https://aclanthology.org/2024.findings-naacl.85/ |
| Research | FiD-Light | - | https://doi.org/10.1145/3539618.3591687 |
| Research | Diversity Reranker | https://towardsdatascience.com/enhancing-rag-pipelines-in-haystack-45f14e2bc9f5 | - |

<!-- ### LLMs Learderboard
[LMSYS Chatbot Arena Leaderboard](https://huggingface.co/spaces/lmsys/chatbot-arena-leaderboard): https://arxiv.org/abs/2306.05685v4
[AlpacaEval Leaderboard](https://tatsu-lab.github.io/alpaca_eval/): https://arxiv.org/abs/2305.14387
[SuperCLUE](https://superclueai.com/): https://arxiv.org/abs/2307.15020 -->

### Citation

If you find this paper or repository helpful, please consider citing our work:

```
@misc{yu2024evaluation,
      title={Evaluation of Retrieval-Augmented Generation: A Survey}, 
      author={Hao Yu and Aoran Gan and Kai Zhang and Shiwei Tong and Qi Liu and Zhaofeng Liu},
      year={2024},
      eprint={2405.07437},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

### Changelog

- 2024-05-11: Initial release of the paper and repository.
- 2024-06-25: Acceptance of the paper by the 2024 CCF Big Data.
- 2024-06-30: Add two benchmarks: DomainRAG and ReEval.
- 2024-07-03: Update Arxiv version to v2.
