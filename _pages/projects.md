---
layout: page
permalink: /projects/
title: Projects
description: 
nav: true
nav_order: 5
---

Content: 

* [Research projects](#ongoingproj)
* [Thesis projects](#thesisproj)

At MaiNLP we aim to make NLP models more robust, so that they can deal better with underlying shifts in data due to language variation.


<h2 class="category"><a name="ongoingproj">On-going research projects</a></h2>

The following lists selected on-going research projects at MaiNLP, including selected publications:

### <a name="multivalue">DFF Sapere Aude Project MultiVaLUe: Multilingual Variety-aware Language Understanding Technology</a>

Intelligent machines that understand natural language texts are the Holy Grail of Artificial Intelligence. If achieved, they can automatically extract useful information from big messy text collections. Many challenges must be overcome first. To alleviate the scarcity of resources and broaden the scope to Danish and other small languages, we will unify two strands of research, transfer learning and weak supervision, with the aim to design cross-domain and cross-lingual algorithms that extract information more robustly under minimal guidance. In this project we work on two concrete applications: cross-lingual syntactic parsing (and representation learning on the linguistic manifold) and cross-domain information extraction.

Selected publications:
- [Müller-Eberstein, van der Goot & Plank, 2021. Genre as Weak Supervision for Cross-lingual Dependency Parsing. In EMNLP.](https://aclanthology.org/2021.emnlp-main.393/)
- [Müller-Eberstein, van der Goot & Plank, 2022. Spectral Probing. In EMNLP.](https://arxiv.org/abs/2210.11860)
- [Bassignana & Plank, 2022. CrossRE: A Cross-Domain Dataset for Relation Extraction. In EMNLP Findings.](https://arxiv.org/abs/2210.09345)
- [Bassignana & Plank, 2022. What Do You Mean by Relation Extraction? A Survey on Datasets and Study on Scientific Relation Classification. In ACL SRW.](https://aclanthology.org/2022.acl-srw.7/)

### <a name="multiskill">DFF Project thematic AI, MultiSkill: Multilingual Information Extraction for Job Posting Analysis</a>

Job markets are about to undergo profound changes in the years to come. The skills required to perform most jobs will shift significantly. This is due to a series of interrelated developments in technology, migration and digitization. As skills change, we are facing increasing needs for quicker and better hiring to better match people to jobs. Big multilingual job vacancy data are emerging on a variety and multitude of platforms. Such big data can provide insights on labor market skill set demands. This project is centered around computational job market analysis, to reliably perform high-precision information extraction on targeted domain data.

Selected publications:
- [Zhang, Jensen, Sonniks & Plank, 2022. SkillSpan: Hard and Soft Skill Extraction from English Job Postings. In NAACL.](https://aclanthology.org/2022.naacl-main.366/)
- [Zhang, Jensen & Plank 2021. Kompetencer: Fine-grained Skill Classification in Danish Job Postings via Distant Supervision and Transfer Learning. In LREC.](https://aclanthology.org/2022.lrec-1.46/)
 

### <a name="ercdialect">ERC Consolidator grant DIALECT: Natural Language Understanding for non-standard languages and dialects</a>

Dialects are ubiquitous and for many speakers are part of everyday life. They carry important social and communicative functions. Yet, dialects and non-standard languages in general are a blind spot in research on Natural Language Understanding (NLU). Despite recent breakthroughs, NLU still fails to take linguistic diversity into account. This lack of modeling language variation results in biased language models with high error rates on dialect data. This failure excludes millions of speakers today and prevents the development of future technology that can adapt to such users.

To account for linguistic diversity, a paradigm shift is needed: Away from data-hungry algorithms with passive learning from large data and single ground truth labels, which are known to be biased. To go past current learning practices, the key is to tackle variation at both ends: in input data and label bias. With DIALECT, I propose such an integrated approach, to devise algorithms which aid transfer from rich variability in inputs, and interactive learning which integrates human uncertainty in labels. This will reduce the need for data and enable better adaptation and generalization.

Advances in salient areas of deep learning research now make it possible to tackle this challenge. DIALECT’s objectives are to devise a) new algorithms and insights to address extremely scarce data setups and biased labels; b) novel representations which integrate auxiliary sources of information such as complement text data with speech; and c) new datasets with conversational data in its most natural form.

By integrating dialectal variation into models able to learn from scarce data and biased labels, the foundations will be established for fairer and more accurate NLU to break down language and literary barriers.

Selected publications:
- [Plank, 2016. What to do about non-standard (or non-canonical) language in NLP. In KONVENS.](https://arxiv.org/abs/1608.07836)
- [Plank, 2022. The 'Problem' of Human Label Variation: On Ground Truth in Data, Modeling and Evaluation. In EMNLP.](https://arxiv.org/abs/2211.02570)
- [Baan, Aziz, Plank & Fernandez 2022.  Stop Measuring Calibration When Humans Disagree. In EMNLP.](https://arxiv.org/abs/2210.16133)
- [Blaschke, Schütze & Plank, 2023. A Survey of Corpora for Germanic Low-Resource Languages and Dialects. In NoDaLiDa.](https://arxiv.org/abs/2304.09805)


### Applications for PhD, Postdoc and student assistant positions

Interested in PhD, Postdoc or student assistants jobs?  <a href="/jobs">→Open positions</a>

<br>
<br>


<h2 class="category"><a name="thesisproj">Thesis projects</a></h2>

Interested in doing your MSc or BSc thesis with us? We offer several BSc and MSc thesis topics at MaiNLP.
 
Currently, the following research vectors characterize broad topics in which we offer MSc and BSc thesis projects. We provide a (non-exhaustive) list of  research projects within each vector. We are also interested to supervise projects related to the [Research projects](#ongoingproj) indicated above. You are welcome to send us your own project proposal. We recommend to check out the suggested/selected publications to get inspired.

Unless otherwise specified, all projects can be either at the MSc or BSc level. The exact scope of the project will be determined in a meeting before the start of the project. 

*Important note for summer semester 2023*: We do not supervise industrial MSc/BSc thesis project (Industrieabschlussarbeiten) this semester. 

Regularly <b>check back for updates</b> on thesis project suggestions. 

News:

- 2023, March 7: All thesis applications are closed. 
- 2023, Feb 28: MSc project applications are closed. Updated projects. BSc applications are still open
- 2023, Feb 21: Slight update on projects 
- 2023, Feb 17: :hourglass_flowing_sand: denotes that projects are currently reserved
- 2023, Feb 6: :sparkles: more thesis projects posted, MSc/BSc level indicators added


Legend:
- :hourglass_flowing_sand: topic currently reserved
- - ~~strikethrough~~: topic no longer available



### V1: Learning from Limited Data (Low-resource, NLP for Dialects, Multilinguality, Transfer)

#### Selected research projects 

- :hourglass_flowing_sand: *Slot and Intent Detection for Low-Resource Dialects.* Digital assistants are becoming wide-spread, yet current technology covers only a limited set of languages.  How can we best do zero-shot transfer to low-resource language variants without standard orthography? [Reference: van der Goot et al., 2021](https://aclanthology.org/2021.naacl-main.197.pdf) and [VarDial 2023 SID4LR](https://sites.google.com/view/vardial-2023/shared-tasks). Create a new evaluation dataset of a low-resource language variant you speak, and investigate how to best transfer to it. Topics: Transfer Learning, Cross-linguality, Dataset annotation (Particularly suited for students interested in covering their own language or dialect not yet covered by existing systems including local dialects, e.g. Bavarian, Austrian, Low Saxon or others). Level: MSc or BSc. 

- *Adopting Information Retrieval Models for Rare Terms.* Neural ranking models have shown impressive results on general retrieval benchmarks, however, domain specific retrieval and representing rare terms are still an open challenge [(Thakur et al., 2021)](https://arxiv.org/abs/2104.08663). In this thesis, the goal is to explore strategies for rewriting queries and documents with the help of text simplification models or external resources such as WordNet or Wikipedia in order to improve their performance in domain transfer. Level: MSc.

- :hourglass_flowing_sand:  *Dialect identification on social media.*  How can we robustly distinguish between closely-related dialects on social media like Twitter? For students interested in creation of a gold standard and classification. Reference (for Italian and Swiss German): [Aepli et al., 2022](https://aclanthology.org/2022.vardial-1.1.pdf), [Aepli and Hollenstein, 2014](https://noe-eva.github.io/publication/noah2015/) Level: BSc.

- :hourglass_flowing_sand: *Germanic Dialect identification across genres.*  How can we robustly distinguish between closely-related Germanic dialects across text types?  German wikipedias exist, but how well does a model trained on Wikipedia transfer to another text type like social media? For students interested in transfer learning and creation of a gold standard for dialect text classification. Reference: [Siewert et al., 2020](https://aclanthology.org/2020.vardial-1.3.pdf) and references above, [Aepli et al., 2022](https://aclanthology.org/2022.vardial-1.1.pdf), [Aepli and Hollenstein, 2014](https://noe-eva.github.io/publication/noah2015/). Level: MSc (preferred) or BSc.

- :hourglass_flowing_sand: *Geolocation of Linguistic Variation in Italy.* (Reference: [GeoLingIt](https://sites.google.com/view/geolingit/)). For students interested in linguistic variation, particularly in Italian language varieties. Participation in a shared task and research paper writing. Level: MSc.

- :hourglass_flowing_sand: *NLP methods for Folk Songs Lyrics.*  Folk music is an essential element of any culture. This project seeks to apply NLP techniques to study folk music of the German-speaking countries with a special focus on song lyrics written in dialect. You will start with building a pipeline for large-scale lyrics collection. Next, you will conduct a comprehensive analysis of song lyrics including (but not limited to): discovering most popular lyrical themes, studying rhymes and the figurative speech used in lyrics. Level: BSc or MSc.

- *Code-switching usage in German social media.* Code-switching is a language phenomenon that occurs when a multilingual speaker alternates multiple languages in a single utterance. This project studies when and why people mix high-standard German with its dialects when writing on social media. The ultimate goal is to explore contexts and grammar structures in which code-switching is mostly used. To this end, a pipeline for user-generated data collection and labeling should be developed along with learnable approaches to code-switching detection. Level: BSc or MSc.

- ~~*Probing large multlingual language models for cross-model alignment.* How similarly is linguistic information represented across models? Data: Any linguistically-motived dataset, ideally multilingual (e.g., multilingual syntactic parsing Universal Dependencies by Nivre et al., 2020) + a diverse selection of pre-trained language models. Method: Encode the same raw data + probe for linguistically-motivated tasks. Compare embeddings and probes for the same data across models.
Evaluation: Quantitative metric used by the relevant dataset(s) / Qualitative analysis. [See references of MultiVaLUe project](#multivalue) Level: MSc.~~

- *German dialects in Wikipedia.* German dialects have unique representations in Wikipedia: there are Wiki’s written in Bavarian, Low Saxon, and several other dialects. At the first glance, these Wiki’s may look like a straightforward translation from German, but it is not the case. In this project we aim to study, what are the theme differences between these Wikipedia and if there are any biases towards cultural and geographical phenomena. Last, but not least, the edit history allows us to explore how the Wikipedia authors deal with the lack of standardized orthography and how they develop spelling rules on their own. Level: BSc or MSc.

- *Large Language Models for low-resource NLP revisited.* At the moment, large language models (LLMs) are all the hype, but do we actually need them for low-resource tasks? In this project, the student compares LLM fine-tuning with computationally cheaper ways of training a model for a low-resource language variety and a NLP task (any classification task or a sequence labeling task). Level: BSc or MSc.

- *Lexicon-based data synthesis for low-resource NLP.*  Systematically make use of those digital dialect dictionaries. This project starts out as a preliminary study on what kinds of usable dictionaries we can find, and then we look at how useful it is to use them to generate faux-dialectal training data.  Level: BSc or MSc.

- *Learning Task Representations.* We are often interested in transferring NLP/IR models to datasets for which we have little or no label annotations available. In such a zero-shot setting its possible to transfer a model from a single related task or a set of related tasks. Representing tasks and measuring task similarity is an open challenge and active research field, the goal of this thesis is to explore approaches for deriving task representations and evaluating their effectiveness in a multi-task setting. Level: MSc.

- :hourglass_flowing_sand: *Machine Translation Error Propagation on Cross-lingual Retrieval.* 
Machine Translation (MT) is frequently used to bridge the gap in cross-lingual information retrieval (CLIR). MT models typically used to translate training data or to translate queries at test time. Recent work has focused on hallucinations of MT models, referring to the phenomenon where translations are, e.g., completely unrelated to the input text. The goal of this thesis is to systematically and broadly analyze different types of MT error propagation with respect to different languages and their impact on CLIR. (proficiency in multiple languages is desired for students who would like to do this project). Level: BSc or MSc.


### V2: High-Quality Information Extraction in Targeted Domains

#### Selected research projects

- :hourglass_flowing_sand:  *Cross-domain Relation extraction.* Extracting structured information such as bornIn(person, location) is central for knowledge base population. Yet current extraction technology is limited to a few text domains and semantic relations. How can we adapt relation extractors to generalize better across different text domains or different relation sets? [Seereferences of MultiVaLUe project](#multivalue). Level: BSc or MSc.

- :hourglass_flowing_sand: *Computational Job Market Analysis.* Extraction of skills from job postings, multlinguality. We are particularly interested in in-depth analysis of existing data and models, or comparisons of different approaches, or extending skill extraction or classification to Germanic and other languages.  [See references of MultiSkill project](#multiskill). Also [Bhola et al., 2020](https://aclanthology.org/2020.coling-main.513.pdf) and [Gnehm et al. 2021](https://www.zora.uzh.ch/id/eprint/230653/1/2022.nlpcss_1.2.pdf). Level: BSc or MSc.
 
- :hourglass_flowing_sand: *Information extraction for finding arguments for pain-awareness of other species.* The fact that non-human animals can feel pain is a strong factor in our ethical and legal considerations involving them. However, it is yet not fully understood which species can perceive pain. Birch et al. (2021) have developed a framework of 8 criteria that suggest sentience of pain in other species, that has recently been used by the UK government to adjust animal welfare regulations. To make a case that a specific species can feel pain, researchers have to go through the literature by hand and find studies that investigate one or more of the 8 criteria (Gibbons et al., 2022). The goal of this project is to develop an information extraction method that supports this process by extracting study information on these 8 criteria automatically. The project would consist of deriving a small evaluation corpus from Gibbons et al., 2022 and then evaluate few-shot learning methods for information extraction on the corpus. [References: Birch, Jonathan, et al. “Review of the evidence of sentience in cephalopod molluscs and decapod crustaceans.” (2021),
M Gibbons, et al. “Can insects feel pain? A review of the neural and behavioural evidence” (2022) Advances in Insect Physiology 63, 155-229].  Level: BSc or MSc (preferred).

- :hourglass_flowing_sand: *Adapt NER Tools to novel entities with gazetteers.* 
Named Entity Recognition (NER) tools are trained on a corpus and then deployed as static resources. When novel entities emerge after deployment, then such tools have problems detecting them (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9014470/). For instance, the state-of-the-art biomedical NER tool HunFlair (https://academic.oup.com/bioinformatics/article/37/17/2792/6122692) has difficulties in reliably detecting concepts related to COVID, because it was trained before the pandemic. In this project, we will develop a novel NER method that allows to easily integrate knowledge emerging entities after training. Level: BSc or MSc.

- :hourglass_flowing_sand: *Automated Evaluation of Biomedical Relation Extraction Models.*
It is an open question how useful information extraction models are for Biological research. The gold standard evaluation is to ask experts for their manual assessment, which is costly and limited to small-scale case studies. However, biological relations have the unique advantage that researchers verify them in biochemical experiments and store the results in large databases. In this project, we will exploit these databases to conduct the first large-scale comparison of different state-of-the-art relation extraction models in terms of usefulness for biological research.  Level: BSc or MSc.

 
### V3: Natural Language Understanding, Semantic & Pragmatics

#### Selected research projects

- :hourglass_flowing_sand: *Prominent entities in text summarization.* One important factor in summarizing a document is identifying the prominent entities within the document. Here is an example from the CNN summarization dataset: Two selected paragraphs:
[Alonso] has been training hard for [his] planned comeback at the Malaysian Grand Prix in nine days and used the {McLaren} simulator to hone [his] mental preparations.
The CNN-sponsored team announced the news on Twitter, showing {McLaren} sporting director Eric Boullier and [Alonso] at the team’s headquarters in Woking, England.
Reference summary:
[Fernando Alonso] steps up comeback preparations in {McLaren} simulator
What linguistic phenomena contribute to the prominence of entities in a document? For example, would coreference chain and discourse relation help? Are summarization strategies the same across different genres and languages?
Build an NLP model that predicts the prominent entities in a document and evaluate accordingly based on reference summaries.
Start with the CNN/DM dataset. Project can be extended to other genres and languages. Level: BSc or MSc.

- :hourglass_flowing_sand: *Understanding Indirect Answers.* Indirect answers are replies to polar questions without explicit use
of Yes/No clues. Example: Q: Do you wanna crash on the couch? A: I gotta go home sometime. Indirect answers are natural in human dialogue, but very difficult for a conversational AI system. Build an NLP model that improves automatic understanding of indirect
questions in English. Project can be extended to multlingual/transfer learning. Reference: [Louis et al., 2020](https://aclanthology.org/2020.emnlp-main.601/) and [Damgaard et al., 2021](https://aclanthology.org/2021.codi-main.1/)  Level: BSc or MSc.

- ~~*Does ChatGPT understand formal logic and common sense?* Problem Definition: Recent evidence has shown that large generative language models (GLMs) such as ChatGPT and you.com/chat fall short in logical reasoning. For example, “Mike’s mum had 4 kids; 3 of them are Luis, Drake, and Matilda. What is the name of the 4th kid?”, ChatGPT’s response was “It is not possible to determine the name of the fourth child without more information” [0]. In addition to this, we are interested common sense logic. For example, do GLMs find “John put a turkey into a fridge” more plausible than “John put an elephant into the fridge”? [1]. To this end, the task is to use existing datasets such as SemEval2020-Task-4 [2] and SNLI [3] for probing GLMs. Goal: The goal of this thesis is to get a better understanding of logic abilities of large GLMs by constructing an evaluation dataset and conducting a systematic comparison between different publicly available chatbots. Requirements: This thesis is ideal for students with prior knowledge in first order predicate logic and requires proficiency in Python and one Deep Learning Framework. 
References:
[0] https://arxiv.org/pdf/2302.03494.pdf
[1] https://aclanthology.org/2020.semeval-1.39.pdf
[2] https://github.com/wangcunxiang/SemEval2020-Task4-Commonsense-Validation-and-Explanation
[3] https://nlp.stanford.edu/projects/snli/
Level: BSc~~

- :hourglass_flowing_sand: *Scientific Analysis Tool.* The goal of this project is to use off-the-shelf NLP models for citation analysis, semantic search and text summarization to build a tool that (semi-)automates the process of synthesizing and summarizing a line of research. This involves identifying the citation purpose and aggregating/summarizing information across multiple papers. Strong knowledge in Python required, knowledge in web crawling beneficial. Level: BSc

### V4: Human-centric Natural Language Understanding: Uncertainty, Perception, Vision, Interpretability

Some general references for this section:
References: [Plank, 2016.](https://arxiv.org/abs/1608.07836), [Jensen and Plank, 2022](https://aclanthology.org/2022.lrec-1.161/), [Plank, 2022 EMNLP](https://arxiv.org/abs/2211.02570) 

#### Selected research projects 

- ~~*Prediction of Human Label Variation.* Human annotators notoriously disagree when labeling objects. This human label variation remains an understudied problem. Can we detect data that triggers high disagreement? And on the contrary, can we detect instances that are easy and reliably labeled? References: [Plank, 2022 EMNLP](https://arxiv.org/abs/2211.02570), [Zhou et al. 2022](https://aclanthology.org/2022.findings-acl.79.pdf) and [Siddiqui et al., 2022](https://arxiv.org/pdf/2209.10015.pdf).  Level: MSc.~~

- *In-context learning from human disagreement on subjective tasks.* 
Aggregating annotations via majority vote could lead to ignoring the opinions of minority groups, especially on subjective tasks. Learning from individual annotators shows a better result on subjective classification tasks such as hate speech detection and emotion detection than from the majority vote (Davani et al., 2022). In this project, we want to investigate the potential of learning from individual annotators in an in-context learning setting. How can the model learn from the disagreement between annotators by instruction tuning and prompting? How do we design such instructions?
References: [Davani et al., 2022](https://aclanthology.org/2022.tacl-1.6/), [Schick et al., 2021](https://arxiv.org/abs/2001.07676) and [Mishra et al., 2022](https://aclanthology.org/2022.acl-long.244.pdf). Level: MSc.


- *Active learning for Vision Question Answering with Large Pretrained Models.*
There were several attempts on active learning for VQA [1],[2]. However, these models are small in size and were trained from scratch. Large Pre-trained Models have achieved great success in unimodality (language or vision) and multimodality (vision-language) settings [3]. This project aims to deploy SOTA foundation models in the active learning framework for VQA tasks. A starting point could be re-implementing some VQA active learning works such as [1].
References:
[Deep Bayesian Active Learning for Multiple Correct Outputs](https://arxiv.org/abs/1912.01119) [1]
[Mind Your Outliers! Investigating the Negative Impact of Outliers on Active Learning for Visual Question Answering](https://aclanthology.org/2021.acl-long.564.pdf) [2]
[BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation](https://arxiv.org/abs/2201.12086) [3] Level: MSc.

- *Human vs Machine. AuTexTification: Identifying Automatically Generated Text.* Generative language models such as ChatGPT have shown impressive results on a range of NLP tasks. While those models can be used to perform useful tasks such as answering questions, writing code or translating text, they can also be used for malicious purposes such as generating hate speech, fake news, or other unfaithful text. This motivates the development of tools for detecting automatically generated text. In this thesis, the student is expected to participate in the AuTexTification shared task [0], which provides a standard benchmark for training and evaluating detection models for the languages English and Spanish. This topic is ideally suited for M.Sc. students with a strong background in Python and one Deep Learning framework. [0] https://sites.google.com/view/autextification Level: MSc. An adaptated version of this is also possible as BSc topic.

- *Learning from Disagreement by Creating Dense Multi-Annotation Dataset* 
Current deep learning approaches generally learn by modelling the hard label (majority vote) or the soft label (annotation distribution/prediction distribution from a teacher model). Can we go one step further by modelling the annotators? Davani et al., TACL 2022 shows that by modelling the individual annotators, the model's uncertainty estimation correlates well with the human annotation variation. However, for each data sample in the dataset (Gab Hate Speech), it only contains annotations from a subset of all annotators. It requires a significant amount of effort to create a "dense multi-annotation dataset". (each data has annotations from all the annotators.) Therefore, the model in Davani et al., TACL 2022 can only learn from 3 annotations at a time. Can we create such a dense annotation dataset by modelling the individual annotators? How differently will the model behave?
References: [Davani et al., TACL 2022](https://aclanthology.org/2022.tacl-1.6/), [Geva et al., EMNLP-IJCNLP 2019](https://aclanthology.org/D19-1107/). Level: BSc

- *Error Analysis of a BERT-based Search Engine*: Multi-stage ranking has become a popular paradigm in information retrieval, this approach a fast first-stage ranker generates a candidate set of documents followed by a much slower re-ranker to refine the ranking [0]. Prior work has shown that better candidate sets (higher recall) don't necessarily translate to a better final ranking [1]. The goal of this thesis is two-fold: First, we would like to perform an error analysis of linguistic triggers that cause this behavior. In the second part, the goal is to apply and interpret automatically generated explanations from tools such as DeepSHAP and LIME [2,3]. Basic knowledge in information retrieval is helpful, but not required. Level: B.Sc.
[0] https://arxiv.org/abs/1910.14424 [1] https://arxiv.org/abs/2101.08751 [2] https://arxiv.org/abs/1907.06484 [3] https://arxiv.org/abs/1602.04938
   

### How to apply for a BSc and MSc thesis project

**Important information for LMU students:** You need to apply for a MSc/BSc thesis project the latest three weeks before the thesis project registration date. Deadlines for 2023: 
* MSc students apply before **February 24, 2023** 
* BSc students apply before **March 6, 2023**

To apply, please send your application material with subject "[BSc (or MSc) thesis project at MaiNLP - inquiry [Name and which semester]" to: thesisplank@cis.lmu.de

It should contain a single pdf with the following information: 
- CV, your study program, full grade transcript
- Level: BSc or MSc thesis project
- Which theme or concrete project interests you the most (optional: we are open to project proposals related to the research vectors or on-going research projects above). If you are interested in multiple, list your preferences for up to two (ranked list: first priority, second priority)
- Languages you speak 
- Your favorite project so far, and why 
- Your knowledge and interest in data annotation, data analysis and machine learning/deep learning (including which toolkits you are familiar with)
- Whether you have access to GPU resources (and which)
- A term project report or your BSc thesis if you apply for a MSc thesis (optional)

Reach out if you have questions, using the email above. 


