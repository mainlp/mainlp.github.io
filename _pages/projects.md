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

 <a href="https://twitter.com/NLPnorth/status/1613906442955919362"><img class="avatar" src="/assets/img/max_ling_var.jpg" alt="Linguistic variation and NLP. Credits: Max Mueller-Eberstein" width="500px" height="auto" /></a>


<h2 class="category"><a name="ongoingproj">On-going research projects</a></h2>

The following lists selected on-going research projects at MaiNLP, including selected publications:

### <a name="multivalue">DFF Sapere Aude Project MultiVaLUe: Multilingual Variety-aware Language Understanding Technology</a>

Intelligent machines that understand natural language texts are the Holy Grail of Artificial Intelligence. If achieved, they can automatically extract useful information from big messy text collections. Many challenges must be overcome first. To alleviate the scarcity of resources and broaden the scope to Danish and other small languages, we will unify two strands of research, transfer learning and weak supervision, with the aim to design cross-domain and cross-lingual algorithms that extract information more robustly under minimal guidance. In this project we work on two concrete applications: cross-lingual syntactic parsing (and representation learning on the linguistic manifold) and cross-domain information extraction.

Selected publications:
- [Müller-Eberstein, van der Goot, Plank, 2021. Genre as Weak Supervision for Cross-lingual Dependency Parsing. In EMNLP.](https://aclanthology.org/2021.emnlp-main.393/)
- [Müller-Eberstein, van der Goot, Plank, 2022. Spectral Probing. In EMNLP.](https://arxiv.org/abs/2210.11860)
- [Bassignana & Plank, 2022. CrossRE: A Cross-Domain Dataset for Relation Extraction. In EMNLP Findings.](https://arxiv.org/abs/2210.09345)
- [Bassignana & Plank, 2022. What Do You Mean by Relation Extraction? A Survey on Datasets and Study on Scientific Relation Classification. In ACL SRW.](https://aclanthology.org/2022.acl-srw.7/)

### <a name="multiskill">DFF Project thematic AI, MultiSkill: Multilingual Information Extraction for Job Posting Analysis</a>

Job markets are about to undergo profound changes in the years to come. The skills required to perform most jobs will shift significantly. This is due to a series of interrelated developments in technology, migration and digitization. As skills change, we are facing increasing needs for quicker and better hiring to better match people to jobs. Big multilingual job vacancy data are emerging on a variety and multitude of platforms. Such big data can provide insights on labor market skill set demands. This project is centered around computational job market analysis, to reliably perform high-precision information extraction on targeted domain data.

Selected publications:
- [Zhang, Jensen, Sonniks, Plank, 2022. SkillSpan: Hard and Soft Skill Extraction from English Job Postings. In NAACL.](https://aclanthology.org/2022.naacl-main.366/)
- [Zhang, Jensen, Plank, 2021. Kompetencer: Fine-grained Skill Classification in Danish Job Postings via Distant Supervision and Transfer Learning. In LREC.](https://aclanthology.org/2022.lrec-1.46/)
 

### <a name="ercdialect">ERC Consolidator grant DIALECT: Natural Language Understanding for non-standard languages and dialects</a>

Dialects are ubiquitous and for many speakers are part of everyday life. They carry important social and communicative functions. Yet, dialects and non-standard languages in general are a blind spot in research on Natural Language Understanding (NLU). Despite recent breakthroughs, NLU still fails to take linguistic diversity into account. This lack of modeling language variation results in biased language models with high error rates on dialect data. This failure excludes millions of speakers today and prevents the development of future technology that can adapt to such users.

To account for linguistic diversity, a paradigm shift is needed: Away from data-hungry algorithms with passive learning from large data and single ground truth labels, which are known to be biased. To go past current learning practices, the key is to tackle variation at both ends: in input data and label bias. With DIALECT, I propose such an integrated approach, to devise algorithms which aid transfer from rich variability in inputs, and interactive learning which integrates human uncertainty in labels. This will reduce the need for data and enable better adaptation and generalization.

Advances in salient areas of deep learning research now make it possible to tackle this challenge. DIALECT’s objectives are to devise a) new algorithms and insights to address extremely scarce data setups and biased labels; b) novel representations which integrate auxiliary sources of information such as complement text data with speech; and c) new datasets with conversational data in its most natural form.

By integrating dialectal variation into models able to learn from scarce data and biased labels, the foundations will be established for fairer and more accurate NLU to break down language and literary barriers.

Selected publications:
- [Plank, 2016. What to do about non-standard (or non-canonical) language in NLP. In KONVENS.](https://arxiv.org/abs/1608.07836)
- [Plank, 2022. The 'Problem' of Human Label Variation: On Ground Truth in Data, Modeling and Evaluation. In EMNLP.](https://arxiv.org/abs/2211.02570)
- [Baan, Aziz, Plank, Fernandez.  Stop Measuring Calibration When Humans Disagree. In EMNLP.](https://arxiv.org/abs/2210.16133)


### Applications for PhD, Postdoc and student assistant positions

Interested in PhD, Postdoc or student assistants jobs?  <a href="/jobs">→Open positions</a>

<br>
<br>


<h2 class="category"><a name="thesisproj">Thesis projects</a></h2>

Interested in doing your MSc or BSc thesis with us? We offer several BSc and MSc thesis topics at MaiNLP.
 
Currently, the following research vectors characterize broad topics in which we offer MSc and BSc thesis projects. We provide a (non-exhaustive) list of  research projects within each vector. We are also interested to supervise projects related to the [Research projects](#ongoingproj) indicated above. We recommend to check out the suggested/selected publications.

Unless otherwise specified, all projects can be either at the MSc or BSc level. The exact scope of the project will be determined in a meeting before the start of the project. 

Regularly <b>check back for updates</b> on thesis project suggestions. 



### V1: Learning from Limited Data (Low-resource, NLP for Dialects, Multilinguality)

#### Selected research projects 

- *Slot and Intent Detection for Low Resource Language Variants.* Digital assistants are becoming wide-spread, yet current technology covers only a limited set of languages.  How can we best do zero-shot transfer to low-resource language variants without standard orthography? [Reference: van der Goot et al., 2021](https://aclanthology.org/2021.naacl-main.197.pdf) Topics: Transfer Learning, Cross-linguality, Possibility to extend to a new low-resource language or dialect (Do you speak a language or dialect not yet covered, e.g. Bavarian, Austrian, Low Saxon or others?)

- *Adopting Information Retrieval Models for Rare Terms.* Neural ranking models have shown impressive results on general retrieval benchmarks, however, domain specific retrieval and representing rare terms are still an open challenge (Thakur et al., 2021). In this thesis, the goal is to explore strategies for rewriting queries and documents with the help of text simplification models or external resources such as WordNet or Wikipedia in order to improve their performance in domain transfer. [Reference: Thakur et al., 2021. BEIR: A Heterogeneous Benchmark for Zero-shot Evaluation of Information Retrieval Models]. 

- *Dialect identification.*  How can we robustly distinguish between closely-related dialects?  German dialect identification across genres. (Data collection, modeling). For students interested in creation of a gold standard and classification. Reference (for Italian and Swiss German): [Aepli et al., 2022](https://aclanthology.org/2022.vardial-1.1.pdf), [Aepli and Hollenstein, 2014](https://noe-eva.github.io/publication/noah2015/)

- *Geolocation of Linguistic Variation in Italy* (BSc level). (Reference: [GeoLingIt](https://sites.google.com/view/geolingit/)). For students interested in linguistic variation. Participation shared task.

- *NLP methods for Folk Songs Lyrics.*  Folk music is an essential element of any culture. This project seeks to apply NLP techniques to study folk music of the German-speaking countries with a special focus on song lyrics written in dialect. You will start with building a pipeline for large-scale lyrics collection. Next, you will conduct a comprehensive analysis of song lyrics including (but not limited to): discovering most popular lyrical themes, studying rhymes and the figurative speech used in lyrics.

- *Code-switching usage in German social media.* Code-switching is a language phenomenon that occurs when a multilingual speaker alternates multiple languages in a single utterance. This project studies when and why people mix high-standard German with its dialects when writing on social media. The ultimate goal is to explore contexts and grammar structures in which code-switching is mostly used. To this end, a pipeline for user-generated data collection and labeling should be developed along with learnable approaches to code-switching detection.

- *Cross-model Alignment.* How similarly is linguistic information represented across models? Data: Any linguistically-motived dataset, ideally multilingual (e.g., multilingual syntactic parsing Universal Dependencies by Nivre et al., 2020) + a diverse selection of pre-trained language models. Method: Encode the same raw data + probe for linguistically-motivated tasks. Compare embeddings and probes for the same data across models.
Evaluation: Quantitative metric used by the relevant dataset(s) / Qualitative analysis. [See references of MultiVaLUe project](#multivalue)

- *German dialects in Wikipedia*. German dialects have unique representation in Wikipedia: there are Wiki’s written in Bavarian, Low Saxon, and several other dialects. At the first glance, these Wiki’s may look like a straightforward translation from German, but it is not the case. In this project we aim to study, what are the theme differences between these Wikipedia and if there are any biases towards cultural and geographical phenomena. Last, but not least, the edit history allows us to explore how the Wikipedia authors deal with the lack of standardized orthography and how they develop spelling rules on their own.


### V2: High-Quality Information Extraction in Targeted Domains

#### Selected research projects

- *Cross-domain Relation extraction.* Extracting structured information such as bornIn(person, location) is central for knowledge base population. Yet current extraction technology is limited to a few text domains and semantic relations. How can we adapt relation extractors to generalize better across different text domains or different relation sets? [See references of MultiVaLUe project](#multivalue)

- *Computational Job Market Analysis.* Extraction of skills from job postings, multlinguality. We are particularly interested in extending this work to German and other languages.  [See references of MultiSkill project](#multiskill)
 
- *Information extraction for finding arguments for pain-awareness of other species.* The fact that non-human animals can feel pain is a strong factor in our ethical and legal considerations involving them. However, it is yet not fully understood which species can perceive pain. Birch et al. (2021) have developed a framework of 8 criteria that suggest sentience of pain in other species, that has recently been used by the UK government to adjust animal welfare regulations. To make a case that a specific species can feel pain, researchers have to go through the literature by hand and find studies that investigate one or more of the 8 criteria (Gibbons et al., 2022). The goal of this project is to develop an information extraction method that supports this process by extracting study information on these 8 criteria automatically. The project would consist of deriving a small evaluation corpus from Gibbons et al., 2022 and then evaluate few-shot learning methods for information extraction on the corpus. [References: Birch, Jonathan, et al. “Review of the evidence of sentience in cephalopod molluscs and decapod crustaceans.” (2021),
M Gibbons, et al. “Can insects feel pain? A review of the neural and behavioural evidence” (2022) Advances in Insect Physiology 63, 155-229]. 

 
### V3: Natural Language Understanding, Semantic & Pragmatics

#### Selected research projects

- *Prominent entities in text summarization.* One important factor in summarizing a document is identifying the prominent entities within the document. Here is an example from the CNN summarization dataset: Two selected paragraphs:
[Alonso] has been training hard for [his] planned comeback at the Malaysian Grand Prix in nine days and used the {McLaren} simulator to hone [his] mental preparations.
The CNN-sponsored team announced the news on Twitter, showing {McLaren} sporting director Eric Boullier and [Alonso] at the team’s headquarters in Woking, England.
Reference summary:
[Fernando Alonso] steps up comeback preparations in {McLaren} simulator
What linguistic phenomena contribute to the prominence of entities in a document? For example, would coreference chain and discourse relation help? Are summarization strategies the same across different genres and languages?
Build an NLP model that predicts the prominent entities in a document and evaluate accordingly based on reference summaries.
Start with the CNN/DM dataset. Project can be extended to other genres and languages.

- *Understanding Indirect Answers.* Indirect answers are replies to polar questions without explicit use
of Yes/No clues. Example: Q: Do you wanna crash on the couch? A: I gotta go home sometime. Indirect answers are natural in human dialogue, but very difficult for a conversational AI system. Build an NLP model that improves automatic understanding of indirect
questions in English. Project can be extended to multlingual/transfer learning. Reference: [Louis et al., 2020](https://aclanthology.org/2020.emnlp-main.601/) and [Damgaard et al., 2021](https://aclanthology.org/2021.codi-main.1/)


### V4: Human-centric Natural Language Understanding: Uncertainty, Perception, Vision

#### Selected research projects

- *Prediction of Human Label Variation.* Human annotators notoriously disagree when labeling objects. This human label variation remains an understudied problem. Can we detect data that triggers high disagreement? References: [Plank, 2022 EMNLP](https://arxiv.org/abs/2211.02570), and [Zhou et al. 2022](https://aclanthology.org/2022.findings-acl.79.pdf)

- *Evaluation of language and vision models*. Analysis of image captioning or visual question answering models.  References: [Jensen and Plank, 2022](https://aclanthology.org/2022.lrec-1.161/)


Check back on projects related to language and vision, learning from fortuitious data incl. human data and human-in-the loop learning. 
For inspiration, see also [Plank, 2016.](https://arxiv.org/abs/1608.07836)


   

### How to apply for a BSc and MSc thesis project

**Important information for CIS LMU students:** You need to apply for a MSc/BSc thesis project the latest three weeks before the thesis project registration date. Deadlines for 2023: 
* MSc students apply before **February 24, 2023**
* BSc students apply before **March 6, 2023**

To apply, please send your application material with subject "[BSc (or MSc) thesis project at MaiNLP - inquiry [Name and which semester]" to: thesisplank@cis.lmu.de

It should contain a single pdf with the following information: 
- CV, your study program, full grade transcript
- Level: BSc or MSc thesis project
- Which theme or concrete project interests you the most (optional: we are open to project proposals related to the research vectors or on-going research projects above)
- Languages you speak 
- Your favorite project so far, and why 
- Your knowledge and interest in data annotation, data analysis and machine learning/deep learning (including which toolkits you are familiar with)
- Whether you have access to GPU resources (and which)
- A term project report or your BSc thesis if you apply for a MSc thesis (optional)

Reach out if you have questions, using the email above. 


