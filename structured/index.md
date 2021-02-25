---
layout: post
title: Structured Explanations
---

> ...**structured explanations**...describe explanations that are not entirely free-form, e.g., there are constraints placed on the explanation-creating process, such as the use of specific inference rules.

## English

| Dataset                                                    | Task                     | Explanation Type | Collection Method | # Instances | # Explanations per Instance | Total # Annotators |
|------------------------------------------------------------|--------------------------|-------------------------|-------------------|---------------------|-------------------------------------|----------------------------|
[WorldTree v1](https://www.aclweb.org/anthology/L18-1433/) | science exam QA | explanation graphs | authors | 1,680 | 1 | 4 | 
[OpenBookQA](https://www.aclweb.org/anthology/D18-1260/) | open-book science QA | 1 fact from WorldTree  | crowd | 5,957 | 1 | n/a |
[WorldTree v2](https://www.aclweb.org/anthology/2020.lrec-1.671/) | science exam QA | explanation graphs | experts |5,100 | 1 | n/a | 
[QED](https://arxiv.org/pdf/2009.06354.pdf) | reading comprehension QA | inference rules | authors | 8,991 | 1 | 3 |
[QASC](https://arxiv.org/pdf/1910.11473.pdf) | science exam QA | 2-fact chain | authors + crowd | 9,980 | 1 | 62 |
[eQASC](https://www.aclweb.org/anthology/2020.emnlp-main.10/) | science exam QA | 2-fact chain | automatic + crowd | 9,980 | ~10 | n/a | 
[eQASC + perturbed](https://www.aclweb.org/anthology/2020.emnlp-main.10/) | science exam QA | 2-fact chain | automatic + crowd | n/a | n/a | n/a | 
[eOBQA](https://www.aclweb.org/anthology/2020.emnlp-main.10/) | open-book science QA | 2-fact chain | automatic + crowd | n/a | n/a | n/a |
[Ye et al. (2020)](https://www.aclweb.org/anthology/2020.findings-emnlp.145/) | SQuAD QA | semi-structured text | crowd + authors | 164 | 1 | n/a | 
[Ye et al. (2020)](https://www.aclweb.org/anthology/2020.findings-emnlp.145/) | NaturalQuestions QA | semi-structured text | crowd + authors | 109 | 1 | n/a |
[R<sup>4</sup>C](https://www.aclweb.org/anthology/2020.acl-main.602/) | reading comprehenesion QA | chains of facts | crowd | 4,588 | 3 | 45 | 
[StrategyQA](https://arxiv.org/pdf/2101.02235.pdf) | implicit reasoning QA | reasoning steps with highlights | crowd | 2,780 | 3 | 54 |  
