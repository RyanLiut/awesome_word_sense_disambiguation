# Awesome-Word-Sense-Disambiguation

This repo collects AWESOME papers/books/blogs/lectures/codes about word sense disambiguation (WSD) and the phenomenon of linguistic ambiguity. This includes not only the narrow area of WSD in an engineering view but more general coverage of ambiguity in linguistics, e.g., structural/lexical ambiguity, polysemy, metaphor&metonymy, semantic changes, coreference resolution, entity linking, uncertainty, and so on. I hope such broad coverage helps us explore the topic extensively and thoroughly.

If you have any ideas for improvements, please send a message on the corresponding discussion or issues.

You may also send an email to us ([liuzhu22@mails.tsinghua.edu.cn](mailto:liuzhu22@mails.tsinghua.edu.cn)) with "[Awesome Word Sense Disambiguation]" as the subject (tell us where it was published, and send us a GitHub link and arxiv link if they are available). 

---

Tag NOTE:

`EL`: Entity Linking

`WSD`: Word Sense Disambiguation

`OOD`: out-of-distributed test, including zero/few-shot, LFS, MFS

`framework`: A new framework to define the problem

`benchmark`: A new benchmark

`application`: Applying WSD into a downstream task

`evaluation`: To evaluate WSD or use WSD to evaluate others

`method`: A method to solve an issue in WSD

`linguistics`: Related to linguistics

## Paper List

 ## 2022

1. [ExtEnD: Extractive Entity Disambiguation](https://aclanthology.org/2022.acl-long.177/)
   Edoardo Barba, Luigi Procopio, Roberto Navigli

   `ACL` \[[CODE](https://github.com/sapienzanlp/extend)\]

   `EL` `framework`

2. [DiBiMT: A Novel Benchmark for Measuring Word Sense Disambiguation Biases in Machine Translation](https://aclanthology.org/2022.acl-long.298/)
   Niccolò Campolungo, Federico Martelli, Francesco Saina, Roberto Navigli

   `ACL` \[[Website](https://nlp.uniroma1.it/dibimt/public/about)\]

   `WSD` `benchmark` `application` `evaluation`

3. [Rare and Zero-shot Word Sense Disambiguation using Z-Reweighting](https://aclanthology.org/2022.acl-long.323/)
   Ying Su, Hongming Zhang, Yangqiu Song, Tong Zhang

   `ACL` [[CODE](https://github.com/suytingwan/wsd-z-reweighting)]

   `WSD` `OOD` `method`

4. [Nibbling at the Hard Core of Word Sense Disambiguation](https://aclanthology.org/2022.acl-long.324/)
   Marco Maru, Simone Conia, Michele Bevilacqua, Roberto Navigli

   `ACL` [[CODE](https://github.com/sapienzanlp/wsd-hard-benchmark)]

   `WSD` `OOD` `evaluation` `benchmark`

5. [Detection, Disambiguation, Re-ranking: Autoregressive Entity Linking as a Multi-Task Problem](https://aclanthology.org/2022.findings-acl.156/)
   Khalil Mrini, Shaoliang Nie, Jiatao Gu, Sinong Wang, Maziar Sanjabi, Hamed Firooz

   `ACL` 

   `EL` `method`

6. [Towards Human Evaluation of Mutual Understanding in Human-Computer Spontaneous Conversation: An Empirical Study of Word Sense Disambiguation for Naturalistic Social Dialogs in American English](https://aclanthology.org/2022.humeval-1.10/)
   Alex Lưu

   `ACL` [[VIDEO](https://aclanthology.org/2022.humeval-1.10.mp4)]

   `WSD` `linguistics` `evaluation` `application`

7. [UAlberta at LSCDiscovery: Lexical Semantic Change Detection via Word Sense Disambiguation](https://aclanthology.org/2022.lchange-1.19/)
   Daniela Teodorescu, Spencer von der Ohe, Grzegorz Kondrak

   `ACL` 

   `WSD` `linguistics`

8. [Disambiguation of morpho-syntactic features of African American English – the case of habitual be](https://aclanthology.org/2022.ltedi-1.9/)
   Harrison Santiago, Joshua Martin, Sarah Moeller, Kevin Tang

   `ACL`

   `WSD` `linguistics`


## Lectures and tutorials



## Books

NOTE: From a linguistics view:

1. [An introduction to language](https://ces.wu.ac.th/news/03/n25967.pdf)

   Nina Hyams, Robert Rodman, and Victoria Fromkin

   `structural ambiguity (Ch03)` `lexical ambiguity (Ch04)`

2. Language Files: Materials for an Introduction to Language and Linguistics, 12th Edition

   `structural ambiguity (5.5.3; 9.6.2)` `lexical ambiguity (5.5.3; 9.5.6)` `translation(16.4.2)`

3. Introduction to Semantics An Essential Guide to the Composition of Meaning 

   Thomas Ede Zimmermann, and Wolfgang Sternefeld

   `structural ambiguity (Ch02)` `lexical ambiguity (Ch03)` 

NOTE: From a machine learning view:

1. Foundations of Statistical Natural Language Processing

   Christopher D. Manning and Hinrich Schütze

   `WSD (Ch07)`

## Other resources