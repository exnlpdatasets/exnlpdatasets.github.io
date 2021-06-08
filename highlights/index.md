---
layout: post
title: Highlights
---

> ...**highlights** are subsets of the input elements (either words, subwords, or full sentences) that are compact and sufficient to explain a prediction. 

## English

| Dataset                                                    | Task                     | Granurality Restriction | Collection Method | # Instances | # Explanations per Instance | Total # Annotators |
|------------------------------------------------------------|--------------------------|-------------------------|-------------------|---------------------|-------------------------------------|----------------------------|
| [MovieReviews](https://www.aclweb.org/anthology/N07-1033/) | sentiment classification | none                    | author            | 1800                | 1                                   | 1                          |
| [MovieReviews<sub>c</sub>](https://www.aclweb.org/anthology/2020.acl-main.408/) | sentiment classification | none | crowd | 200 | 2 (1 given) | 2 | 
| [SST](https://www.aclweb.org/anthology/D13-1170/) | sentiment classifcation | none | crowd | 11,855 | 3 (1 given) | n/a |
| [WikiQA](https://www.aclweb.org/anthology/D15-1237/) | open-domain QA | 	sentence | crowd + authors | 1,473 |
| [WikiAttack](https://www.aclweb.org/anthology/D18-1386/) | detecting personal attacks | none | students | 1089 | 4 (1 given) | 40 |
| [e-SNLI](https://papers.nips.cc/paper/2018/hash/4c7a167bb329bd92580a99ce422d6fa6-Abstract.html) | natural language inference | none | crowd | ~569K | 1 or 3 | 6325 |
| [MultiRC](https://www.aclweb.org/anthology/N18-1023/) |  reading comprehension QA | sentences | crowd | 5,825 | 1 | n/a | 
| [FEVER](https://www.aclweb.org/anthology/N18-1074/) | verifying claims from text | sentences | crowd | ~136K | 1 | 50 |
| [HotpotQA](https://www.aclweb.org/anthology/D18-1259/) | reading comprehension QA | sentences | crowd | 112,779 | n/a | n/a |
| [Hanselowski et al. (2019)](https://www.aclweb.org/anthology/K19-1046/) | verifying claims from text | sentences | crowd |  6,422 | varies | n/a |
| [NaturalQuestions](https://www.mitpressjournals.org/doi/full/10.1162/tacl_a_00276) | reading comprehension QA | 1 paragraph | crowd | n/a | 1 or 5 | 50 | 
| [CoQA](https://www.aclweb.org/anthology/Q19-1016/) | conversational QA | none | crowd | ~127K | 1 or 3 | n/a |
| [CoS-E v1.0](https://www.aclweb.org/anthology/P19-1487/) | commonsense QA | none | crowd | 8,560 | 1 | n/a | 
| [CoS-E v1.1](https://www.aclweb.org/anthology/P19-1487/) | comonsense QA | none | crowd | 10,962 | 1 | n/a |
| [BoolQ<sub>c</sub>](https://www.aclweb.org/anthology/2020.acl-main.408/) |   reading comprehension QA | none | crowd | 199 | 3 (1 given) | 3 |
| [EvidenceInference v1.0](https://www.aclweb.org/anthology/N19-1371/) | evidence inference | none | experts |  10,137 | 1  | 3 | 
| [EvidenceInference v1.0<sub>c</sub>](https://www.aclweb.org/anthology/2020.acl-main.408/) | evidence inference | none | experts | 125 | 1 | 4 | 
| [EvidenceInference v2.0](https://www.aclweb.org/anthology/2020.bionlp-1.13/) | evidence inference | none | experts | 2,503 | 1 | 6 | 
| [SciFact](https://www.aclweb.org/anthology/2020.emnlp-main.609/) | verifying claims from text | 1-3 sentences | experts | 995 | 1-3 | 13 | 
| [Kutlu et al. (2020)](https://www.ischool.utexas.edu/~ml/papers/kutlu_jair20.pdf) | webpage relevance ranking | 2-3 sentences | crowd | 700 | 15 | n/a |
| [Supporting Context for Ambiguous Translations (SCAT)](https://arxiv.org/abs/2105.06977) | Document-level En-Fr MT | none | experts | ~14K | 1 | 20 |   
| [ECtHR](https://www.aclweb.org/anthology/2021.naacl-main.22/) | alleged legal violation prediction | paragraphs | auto + expert | 1  | ~11K |               

## French

| Dataset                                                    | Task                     | Granurality Restriction | Collection Method | # Instances | # Explanations per Instance | Total # Annotators |
|------------------------------------------------------------|--------------------------|-------------------------|-------------------|---------------------|-------------------------------------|----------------------------|
| [Supporting Context for Ambiguous Translations (SCAT)](https://arxiv.org/abs/2105.06977) | Document-level En-Fr MT | none | experts | ~14K | 1 | 20 |          
