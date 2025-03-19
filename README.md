## A data-driven investigation of euphemistic language: Comparing the usage of "slave" and "servant" in 19th century newspapers
This repository contains materials for "A data-driven investigation of euphemistic language: Comparing the usage of "slave" and "servant" in 19th century newspapers."

[Paper](https://arxiv.org/abs/2402.02572)

## Citation

:warning:
<mark style='background-color:red'>
<span style='color:red'>
*Warning: This paper contains examples of offensive language targeting marginalized populations.*
</span>
</mark>

```
@inproceedings{park2025euphemistic,
  title={A Data-driven Investigation of Euphemistic Language: Comparing the usage of "slave" and "servant" in 19th century US newspapers},
  author={Park, Jaihyun and Cordell, Ryan},
  booktitle={The 5th International Conference on Natural Language Processing for Digital Humanities},
  year={2025}
}
```
## Abstract
This study investigates the usage of “slave” and “servant” in the 19th century US newspapers using computational methods. While both terms were used to refer to enslaved African Americans, they were used in distinct ways. In the Chronicling America corpus, we included possible OCR errors by using FastText embedding and excluded text reprints to consider text reprint culture in the 19th century. Word2vec embedding was used to find semantically close words to “slave” and “servant” and log-odds ratio was calculated to identify over-represented discourse words in the Southern and Northern newspapers. We found that “slave” is associated with socio-economic, legal, and administrative words, however, “servant” is linked to religious words in the Northern newspapers while Southern newspapers associated “servant” with domestic and familial words. We further found that slave discourse words in Southern newspapers are more prevalent in Northern newspapers while servant discourse words from each side are prevalent in their own region. This study contributes to the understanding of how newspapers created different discourses around enslaved African Americans in the 19th century US.

## RQ 1: What are the words that are most similar to "slave" and "servant" in the corpus of Southern and Northern newspapers?
The code for this research question is available in the [RQ1-word2vec-token.ipynb](https://github.com/park-jay/slavery-discourse/blob/main/RQ1.ipynb)

## RQ 2: How prevalent are the discourse words from the Southern and Northern newspapers in the entire corpus?
The code for this research question is available in the [RQ2-log-odds-token.ipynb](https://github.com/park-jay/slavery-discourse/blob/main/RQ2.ipynb) 