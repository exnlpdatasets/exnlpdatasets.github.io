---
layout: post
title: Free-Text Explanations
---

> **Free-text explanations** are free-form textual justifications that are not constrained to the instance inputs. 

## English

### Textual tasks 

| Dataset                                                    | Task                | Collection Method | # Instances | # Explanations per Instance | Total # Annotators |
|------------------------------------------------------------|-------------------------|-------------------|---------------------|-------------------------------------|----------------------------|
[Jansen et al. (2016)](https://www.aclweb.org/anthology/C16-1278/) | science exam QA | authors | 363 | 1 | 4 |
[Ling et al. (2017)](https://www.aclweb.org/anthology/P17-1015/) | solving algebraic word problems | automatic + crowd | ~101K | 1 | n/a | 
[Srivastava et al. (2017)](https://www.aclweb.org/anthology/D17-1161/) | detecting phishing emails | crowd + authors | 7 | 30-35 | 146 | 
[BabbleLabble](https://www.aclweb.org/anthology/P18-1175/) | relation extraction | students + authors | 200 | 1 | 10 |
[e-SNLI](https://papers.nips.cc/paper/2018/hash/4c7a167bb329bd92580a99ce422d6fa6-Abstract.html) | natural language inference | crowd | ~569K | 1 or 3 | 6325 | 
[LIAR-PLUS](https://www.aclweb.org/anthology/W18-5513/) | verifying claims from text | automatic | 12, 836 | 1 | n/a | 
[CoS-E v1.0](https://www.aclweb.org/anthology/P19-1487/) | commonsense QA | crowd | 8,560 | 1 | n/a |
[CoS-E v1.1](https://www.aclweb.org/anthology/P19-1487/) | commonsense QA | crowd | 10,962 | 1 | n/a | 
[ECQA](https://aclanthology.org/2021.acl-long.238/) | commonsense QA | crowd | 10,962 | 1 | n/a |
[Sen-Making](https://www.aclweb.org/anthology/P19-1393/) | commonsense validation | students + authors | 2,021 | 1 | 7 |               
[ChangeMyView](https://www.aclweb.org/anthology/D19-1289/) | argument persuasiveness | crowd | 37,718 | 1 | n/a |       
[WinoWhy](https://www.aclweb.org/anthology/2020.acl-main.508/) | pronoun coreference resolution | crowd | 273 | 5 | n/a | 
[SBIC](https://www.aclweb.org/anthology/2020.acl-main.486/) | social bias inference | crowd | 48,923 | 1-3 | n/a | 
[PubHealth](https://www.aclweb.org/anthology/2020.emnlp-main.623/) | verifying claims from text | automatic 11,832 | 1 | n/a | 
[Wang et al. (2020)](https://arxiv.org/pdf/1911.01352.pdf) | relation extraction | crowd + authors | 373 | 1 | n/a |
[Wang et al. (2020)](https://arxiv.org/pdf/1911.01352.pdf) | sentiment classification | crowd + authors | 85 | 1 | n/a | 
[e-delta-NLI](https://arxiv.org/abs/2012.08012) | defeasible natural language inference | automatic | 92,298 | ~8 | n/a | 
[COPA-SSE (Semi-Structured Explanations for COPA)](https://github.com/a-brassard/copa-sse) | Balanced COPA (commonsense QA, causal reasoning) | semi-structured\* | crowd | 1,500 | 4-9 (9747 total) |  N/A |

\* ConceptNet-like triples with free-form head and tail concepts. The author class this as structured but it's not very rigid and can also be used as free text.

### Multimodal tasks 

| Dataset                                                    | Task                | Collection Method | # Instances | # Explanations per Instance | Total # Annotators |
|------------------------------------------------------------|-------------------------|-------------------|---------------------|-------------------------------------|----------------------------|
[BDD-X](https://arxiv.org/abs/1807.11546) | vehicle control for self-driving cars | crowd | ~26K | 1 | n/a | 
[VQA-E](https://arxiv.org/abs/1803.07464) | visual QA | automatic |  ~270K | 1 | n/a | 
[VQA-X](https://openaccess.thecvf.com/content_cvpr_2018/papers/Park_Multimodal_Explanations_Justifying_CVPR_2018_paper.pdf) | visual QA | crowd | 28,180 | 1 0r 3 | n/a | 
[ACT-X](https://openaccess.thecvf.com/content_cvpr_2018/papers/Park_Multimodal_Explanations_Justifying_CVPR_2018_paper.pdf) | activity recognition | crowd | 18,030 | 3 | n/a |
[Ehsan et al. (2019)](https://arxiv.org/abs/1901.03729) | playing arcade games | crowd | 2000 | 1 | 60 | 
[VCR](https://visualcommonsense.com/) | visual commonsense reasning | crowd | ~290K | 1 | n/a| 
[e-SNLI-VE](https://arxiv.org/abs/2004.03744) | visual-textual entailment | crowd | 11,335 | 3 | n/a |
[ESPRIT](https://www.aclweb.org/anthology/2020.acl-main.706/) | reasoning about qualitative physics | crowd | 2441 | 2 | n/a |
[VLEP](https://www.aclweb.org/anthology/2020.emnlp-main.706/) | future event prediction | automatic + crowd | 28,726 | 1 | n/a | 
[EMU](https://arxiv.org/abs/2012.04726) | reasoning about manipulated images | crowd | 48K | n/a | n/a |

## Multiple Languages


| Dataset                                                    | Task                | Collection Method | # Instances | # Explanations per Instance | Total # Annotators |
|------------------------------------------------------------|-------------------------|-------------------|---------------------|-------------------------------------|----------------------------|
| [E-KAR](https://aclanthology.org/2022.findings-acl.311/) | analogical reasoning | crowd | 1,655 (in Chinese); 1,251 (in English) | 5 | N/A | 
