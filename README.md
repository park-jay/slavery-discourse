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

## RQ 1: How different are the semantic meaning of ``coolie`` in each State?
The code for this research question is available in the [RQ1-word2vec-token.ipynb](https://github.com/park-jay/coolie/blob/main/RQ1-word2vec-token.ipynb)

## RQ 2: What are the words over-represented in the newspapers between then-Confederate States and then-Union States?
The code for this research question is available in the [RQ2-log-odds-token.ipynb](https://github.com/park-jay/coolie/blob/main/RQ2-log-odds-token.ipynb) 

Please note that [RQ2-redo-log-odds-token.ipynb](https://github.com/park-jay/coolie/blob/main/RQ2-redo-log-odds-token.ipynb) has been modified to group the States into slave-States and free-States, not then-Confederate States and then-Union States.

## RQ 3: What ``coolie`` stories are reprinted and what are their characteristics?
The code for this research question is available in the [RQ3-reprint-viz.ipynb](https://github.com/park-jay/coolie/blob/main/RQ3-reprint-viz.ipynb)
