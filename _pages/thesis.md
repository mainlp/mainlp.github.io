---
layout: page
permalink: /thesis/
title: Thesis
description: 
nav: true
nav_order: 5
---

Interested in writing your MSc or BSc thesis with us? We offer several BSc and MSc thesis topics at MaiNLP.
 
Currently, the following research vectors characterize broad topics in which we offer MSc and BSc thesis projects. We provide a (non-exhaustive) list of  research projects within each vector. We are also interested to supervise projects related to our [research projects](https://mainlp.github.io/projects/). You are welcome to send us your own project proposal. We recommend to check out the suggested/selected publications to get inspired.

Unless otherwise specified, all projects can be either at the MSc or BSc level. The exact scope of the project will be determined in a meeting before the start of the project. 

*Important note*: We currently do not supervise industrial MSc/BSc thesis projects (Industrieabschlussarbeiten). 

Regularly <b>check back here for updates</b> on thesis project suggestions. 

News:

<!-- - 2024, Feb 26: Thank you all for your interest! We are closed for further thesis applications for the upcoming summer semester  -->
- 2024, Sep 1: MSc/BSc project applications deadlines posted. See list of project below and how to apply <a href="#howtoapply">here</a>

Legend:
- :hourglass_flowing_sand: topic currently reserved
- ~~strikethrough~~ topic no longer available

   
<a name="howtoapply"/>
### How to apply for a BSc and MSc thesis project

**Important information for LMU students:** You need to apply for a MSc/BSc thesis project the latest three weeks before the thesis project registration date. 

Deadlines for the winter semester 2024-2025: 
* MSc students apply before **September 4, 2024**
* BSc students apply before **September 14, 2024**

Deadlines for the summer semester 2025: 
* MSc students apply before **February 12, 2025**
* BSc students apply before **February 26, 2025**

<!-- 

* MSc students apply before **February 15, 2024**
* BSc students apply before **February 29, 2024**
* MSc students apply before ~~**February 24, 2023**~~ ~~**August 31, 2023**~~ (closed)
* BSc students apply before ~~**March 6, 2023**~~ ~~**September 4, 2023**~~ (closed)
-->

To apply, please send your application material with subject "[BSc (or MSc) thesis project at MaiNLP - inquiry [Name and which semester]" to: thesisplank@cis.lmu.de

It should contain a single pdf with the following information: 
- CV, your study program, full grade transcript
- Level: BSc or MSc thesis project
- Which theme or concrete project interests you the most (optional: we are open to project proposals related to the research vectors or on-going research projects). If you are interested in multiple, list your preferences for up to two (ranked list: first priority, second priority)
- Languages you speak 
- Your favorite project so far, and why 
- Your knowledge and interest in data annotation, data analysis and machine learning/deep learning (including which toolkits you are familiar with)
- Whether you have access to GPU resources (and which)
- A term project report or your BSc thesis if you apply for a MSc thesis (optional)

Reach out if you have questions, using the email above. 


MSc/BSc thesis research vectors: 

* [V1: NLP for Dialects, Multilinguality](#v1)
* [V2: High-Quality Information Extraction and Retrieval, Data-centric NLP](#v2)
* [V3: Natural Language Understanding, Semantic & Pragmatics, Computational Social Science](#v3)
* [V4: Human-centric Natural Language Understanding: Uncertainty, Perception, Cognition, Vision, Interpretability](#v4)


<a name="v1"/>
### V1: NLP for Dialects, Multilinguality

#### Selected research projects 

- *NLP for dialectal/non-standard language data.* You are welcome to propose thesis projects related to processing dialectal or non-standard language data. Selected example projects are given below. Please include the following information in your application: (1) the dialect(s)/language(s) you are interested in working with and your familiarity with them, (2) one or more NLP tasks you would be interested in working on, (3) links to relevant datasets (some starting points for finding datasets: Germanic low-resource languages/dialects – [Blaschke et al. 2023](https://aclanthology.org/2023.nodalida-1.41.pdf) ([web overview](https://github.com/mainlp/germanic-lrl-corpora)), regional languages of Italy – [Ramponi 2024](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00631/119058/Language-Varieties-of-Italy-Technology-Challenges), Arabic dialects – [Guellil et al. 2021](https://www.sciencedirect.com/science/article/pii/S1319157818310553?via%3Dihub)) and/or details on what kind of data you would like to collect/annotate, and (4) what focus you are most interested in (modelling/engineering, linguistically motivated error analysis, etc. – you are very welcome to pitch specific research questions here). General reference: [Zampieri et al. 2020](https://www.cambridge.org/core/journals/natural-language-engineering/article/abs/natural-language-processing-for-similar-languages-varieties-and-dialects-a-survey/229652C86E329F83346BB6C66B9521A6). Level: BSc or MSc.
 
  *  *Analyzing dialect identification systems.* How well can we automatically discern between different closely related language varieties, and do the features that are relevant to the success of an automatic classifier correlate with those that linguists would describe? You can decide on the language varieties to be included in the thesis, provided that high-quality, accessible corpora are available. (See above for starting points for finding datasets. If you prefer to work with a language not covered in these overviews, please contact us early on.) You can also decide which thematic focus/foci the thesis should have: (i) linguistic analysis of the data and classifier output; (ii) applying interpretability methods to the classifier output (in conjunction with focus i); (iii) comparing different kinds of input representations and ML architectures, including speech. The specific focus and level of detail will depend on your background and skills as well as the degree (BSc vs. MSc). Additional references: [Gaman ea. 2020](https://aclanthology.org/2020.vardial-1.1/) and other VarDial shared task papers for literature on automatic dialect identification, [Nerbonne ea. 2021](https://www.let.rug.nl/nerbonne/papers/Nerbonne-etal-CompDial2020.pdf) and [Wieling & Nerbonne 2015](https://www.annualreviews.org/doi/10.1146/annurev-linguist-030514-124930) for introductions to dialectometry; [Madsen ea. 2022](https://dl.acm.org/doi/pdf/10.1145/3546577) and [Barredo Arrieta ea. 2020](https://www.sciencedirect.com/science/article/abs/pii/S1566253519308103) for overviews of interpretability methods. Level: BSc or MSc.


  *  *Slot and Intent Detection for Low-Resource Dialects.* Digital assistants are becoming wide-spread, yet current technology covers only a limited set of languages.  How can we best do zero-shot transfer to low-resource language variants without standard orthography? [Reference: van der Goot et al., 2021](https://aclanthology.org/2021.naacl-main.197.pdf) and [VarDial 2023 SID4LR](https://sites.google.com/view/vardial-2023/shared-tasks). Create a new evaluation dataset of a low-resource language variant you speak, and investigate how to best transfer to it. Topics: Transfer Learning, Cross-linguality, Dataset annotation (Particularly suited for students interested in covering their own language or dialect not yet covered by existing systems including local dialects, e.g. Austrian, Low Saxon, Sardinian dialects or others). Level: MSc. 


  *  *Creating a dialectal dependency treebank or POS-tagged corpus.* Create a small Universal Dependencies (UD; [de Marneffe et al. 2021](https://direct.mit.edu/coli/article/47/2/255/98516/Universal-Dependencies)) treebank in a dialect, regional language or other low-resource language that you are familiar with. For a less time-intensive project, it is also possible to only annotate part-of-speech (POS) tags (otherwise: POS tags + dependencies) and complement the project with something else. This project requires a strong interest in linguistics and syntax. You will need to read up on UD's annotation guidelines and independently seek out relevant linguistic literature on your chosen language. You also evaluate parsers/POS taggers on your new dataset in a cross-lingual transfer set-up and, time permitting, you might also train your own parsers. Ideally, the project leads to contributing a new treebank to the UD project. Examples of similar corpora: [Siewert et al. 2021](https://aclanthology.org/2021.konvens-1.25/), [Hollenstein & Aepli 2014](https://aclanthology.org/W14-5310/), [Cassidy et al. 2022](https://aclanthology.org/2022.acl-long.473/), [Lusito & Maillard 2021](https://aclanthology.org/2021.udw-1.10/). [Tutorial for UD newcomers](https://unidive.lisn.upsaclay.fr/doku.php?id=other-events:webinar-1). Level: BSc or MSc.

  * *Lexical Resources for Dialects.* NLP for dialect languages is an intriguing area of research due to the lack of resources (low-resources languages) and lack of standardization (high variance). In this project, the goal is build dialect dictionaries by annotating words and phrases with respect to different linguistic properties including parts-of-speech, cases and grammatical genders. For this, we have collected raw data in several German dialects. It is therefore important that the student is familiar with one or more of the following dialects: Alemannic (Alemannisch), Palatinate (Pfälzisch), Frisian (Friesisch), Saterland Frisian (Saterfriesisch), Bavarian (Bairisch), Low German (Niederdeutsch/Plattdeutsch), Colognian (Kölsch). The second part consists of using these dictionaries to either 1) systematically investigate the linguistic dialect competence of pre-trained language models or 2) develop IR-specific resources (dialect stopword lists, dialect lemmatizers, dialect stemmers). This project does not need access to GPUs and is suitable for BSc and MSc students.

  *  *Transfer or translate: how to better work with dialectal data.* Demands for generalizing NLP pipelines to dialectal data are on the rise. Given current LLMs trained in hundreds of languages, there are two common approaches. The first approach is to translate (or normalize) dialectal data to its mainstream counterpart and apply pipelines to the translated mainstream counterpart. Such an approach can benefit from the bigger amount of unannotated and annotated data in the mainstream variant but suffers from error propagation in the pipeline. The second transfer approach is to annotate a small amount of dialectal data and few-shot transfer (finetune) models on the dialect. This involves more dialectal annotation as well as collected unannotated dialectal data. Reference: [Zampieri et al. 2020](https://helda.helsinki.fi/server/api/core/bitstreams/dd1636da-66ef-4e2d-bdb7-19c0b27080f3/content). For a BSc thesis, you would choose an NLP task (e.g., syntactic or semantic parsing, sentiment or stance detection,  QA or summarization, etc.) and a specific dialect, compare performances of fewshot versus translation approaches quantitatively, and conduct a qualitative error analysis on the difficult cases. For MSc, the research needs to scale up either to multiple dialects (in the same or across different language families) or to multiple NLP tasks. Level: BSc or MSc.
 
  *  *To What Degree do LLMs Understand Bavarian Dialect Variants?* In this project, we aim to comprehensively evaluate existing multilingual and German LLMs on Bavarian dialect variants. Your task is to come up with a set of evaluation criteria to test existing LLMs in zero-shot and few-shot manner, starting from existing benchmarks but with the aim to go beyond them, systematically comparing LLMs with traditional fine-tuning approaches, and finding out when and why certain methods struggle.  Techniques: In-depth Evaluation, LLMs, Fine-tuning, Behavioral Testing. Level: MSc.
 
  *  *Language Modeling of Historical Non-Standard Language Documents.* Digitalisation can provide access to valuable historical information, especially for non-standard languages and dialects. In this project, you test and build a prototype for digitalisation of historical documents using recent visual representation-based methods. The project includes: data gathering and annotation, model evaluation and improvement (e.g. by augmentation methods). References: [Salesky et al., 2021](https://aclanthology.org/2021.emnlp-main.576/), [Borenstein et al., 2023](https://aclanthology.org/2023.emnlp-main.7.pdf). Level: MSc.

    
<a name="v2"/>
### V2: High-Quality Information Extraction and Retrieval, Data-centric NLP

#### Selected research projects

- *Computational Job Market Analysis.* Job postings are a rich resource to understand the dynamics of the labor market including which skills are demanded, which is also important for an educational viewpoint. Recently, the emerging line of work on computational job market analysis or NLP for human resources has started to provide data resources and models for automatic job posting analysis, such as the identification and extraction of skills. See references of MultiSkill project. For students interested in real-world applications, this theme provides multiple thesis projects including but not limited to: an in-depth analysis of existing data set and models, researching implicit skill extraction or cross-domain transfer learning to adapt skill and knowledge extraction to data sources other than job postings like patents or scientific articles. [See references of MultiSkill project](#multiskill). See also [Bhola et al., 2020](https://aclanthology.org/2020.coling-main.513.pdf) and [Gnehm et al. 2021](https://www.zora.uzh.ch/id/eprint/230653/1/2022.nlpcss_1.2.pdf) and our [own ESCOXLM-R model](https://aclanthology.org/2023.acl-long.662.pdf). Level: BSc or MSc.

- *Climate Change Insights through NLP*. Climate change is a pressing issue internationally that is receiving more and more attention everyday. It is influencing regulations and decision-making in various parts of society such as politics, agriculture, business, and it is discussed extensively on social media. For students interested in real-world societal applications, this project aims to contribute insights on the discussion surrounding climate change on social media by examining discourse from a social media platform. The data will have to be collected (potentially from existing sources), cleaned, and analyzed using NLP techniques to examine various aspects or features of interest such as stance, sentiment, the extraction of key players, etc. References: [Luo et al., 2020](https://aclanthology.org/2020.findings-emnlp.296v2.pdf), [Stede & Patz, 2021](https://aclanthology.org/2021.nlp4posimpact-1.2.pdf), [Vaid et al., 2022](https://aclanthology.org/2022.acl-srw.35.pdf). Level: BSc or MSc.
 
- *Better Benchmarks / Mining for Errors in Annotated Datasets.* Benchmark datasets are essential in empirical research, but even widely-used annotated datasets contain mistakes, as annotators inevitably make mistakes (e.g. annotation inconsistencies). There are several lines of work in this direction. On the one site, annotation error detection methods provide a suite of methods to detect errors in existing datasets (cf. [Klie et al. 2023](https://direct.mit.edu/coli/article/49/1/157/113280/Annotation-Error-Detection-Analyzing-the-Past-and), [Weber & Plank 2023](https://aclanthology.org/2023.findings-acl.562/)), including tools such as data maps ([Swayamdipta et al. 2020](https://aclanthology.org/people/s/swabha-swayamdipta/)). On the other side, there is work on inspecting existing datasets in revision efforts that exist for English NER in the past year (cf. [Reiss et al. 2020](https://aclanthology.org/2020.conll-1.16/), [Rücker & Akbik 2023](https://aclanthology.org/2023.emnlp-main.533.pdf)). The goal of projects on this theme can be:<br/>
a) (MSc level) to investigate error detection methods in novel scenarios (new benchmarks, new applications, and/or create a new error detection dataset), <br/>
b) (MSc or BSc level) extend revision efforts on NER to other languages. For the latter, for a BSc thesis, your task includes improving a benchmark dataset with iterations of sanity checks and revisions and comparing NLP models on the original versus revised versions. For MSc, you could extend either by incorporating Annotation Error Detection methods (see previous part) or conducting additional evaluations on multiple downstream NLP tasks. <br/>
c) (MSc level) Checking the annotation consistency of non-standardized language data. Automatic methods for finding potential inconsistencies in annotations typically rely on consistent orthographies (e.g., detecting sequences that occur multiple times in a corpus but have received different annotations; [Dickinson & Meurers 2003](https://aclanthology.org/E03-1068/)). When text is written in a language variety without a standardized orthography, such methods may no longer work well because of spelling differences between the repeated sequences. Your task is to extend such approaches to detect errors in existing datasets to be more robust to orthographic variation and/or to investigate how well annotation error detection methods that do not directly depend on orthographic matches work (cf. [Klie et al. 2023](https://direct.mit.edu/coli/article/49/1/157/113280/Annotation-Error-Detection-Analyzing-the-Past-and)). The target dataset would ideally be a dialectal dataset currently under development at the lab (this requires familiarity with German dialects and an interest in syntax). 

- *Error Analysis of a BERT-based Search Engine*: Multi-stage ranking has become a popular paradigm in information retrieval, this approach a fast first-stage ranker generates a candidate set of documents followed by a much slower re-ranker to refine the ranking ([Nogueira et al. 2019](https://arxiv.org/abs/1910.14424)). Prior work has shown that better candidate sets (higher recall) don’t necessarily translate to a better final ranking ([Gao et al. 2021](https://arxiv.org/abs/2101.08751)). The goal of this thesis is two-fold: First, we would like to perform an error analysis of linguistic triggers that cause this behavior. In the second part, the goal is to apply and interpret automatically generated explanations from tools such as DeepSHAP ([Fernando et al. 2019](https://arxiv.org/abs/1907.06484)) and LIME ([Riberio et al. 2016](https://arxiv.org/abs/1907.06484)). Basic knowledge in information retrieval is helpful, but not required. Level: B.Sc. 

-  *Injecting Lexical Similarity Signals into Neural Information Retrieval (IR) Models.* Early IR models rely lexical signals (keyword matches) such as BM25, TF-IDF and the Query Likelihood Model (QLM) between queries and documents to determine their relevane. For a long time lexical retrieval models performed still very competitively, outperforming neural retrieval in domain-specific settings [Thakur et al. (2021)](https://arxiv.org/pdf/2104.08663). Reranking with cross-encoders (CE) is arguable among the most widely used IR paradigms and frames relevance prediction as a sequence pair classification task where inputs are constructed through concatenating query-document pairs "[CLS] Query [SEP] Doc [SEP]". In a recent work, [Askari et al (2023)](https://link.springer.com/chapter/10.1007/978-3-031-28244-7_5) showed that CEs benefit from further including lexical input signals "[CLS] Query [SEP] BM25 [SEP] Doc [SEP]". The goal of this thesis is to conduct a systematic evaluation of additional lexical signals (and combinations thereof) including, e.g., TF-IDF and QLM (reduced scope, BSc) and semantic signals obtained from semantic similarity models or LLMs (full scope, MSc). This thesis is suitable for students who do not have access large GPUs.  Level: BSc or MSc.

- *Investigating Information Asymmetry on Wikipedia.* Information asymmetry (IA) refers to the fact that the volume and type of information on the web varies between languages. For example, prior work by [Kolbitsch and Maurer (2006)](https://www.researchgate.net/profile/Josef-Kolbitsch/publication/200772707_The_Transformation_of_the_Web_How_Emerging_Communities_Shape_the_Information_We_Consume/links/00b7d52453fcba84d3000000/The-Transformation-of-the-Web-How-Emerging-Communities-Shape-the-Information-We-Consume.pdf) and [Callahan  et al. (2011)](https://homes.luddy.indiana.edu/herring/callahan.herring.2011.pdf) find that articles about locally famous people ("local heros") are written in a more favorable way whereas articles about the same people written in other languages also discuss controversial aspects. As a result, monolingual search engines can produce culturally biased search results. The goal of this thesis is to investigate IA on Wikipedia. In the first part, the student is expected to devise an annotation schema that allows to systematically analyze IA and then use it to compare articles about "local heroes" in 2-3 different languages. The second part consists of delving deeper into measuring IA in an automated way. The student is expected to investigate different ways of applying unsupervised semantic similarity models (e.g. BERTScore proposed in [Zhang et al. (2019)](https://arxiv.org/abs/1904.09675)) or LLMs to identify IA. This thesis is suitable for BSc students (under a reduced scope) and MSc students.  Level: BSc or MSc.

- *Do LLMs suffer from lexical biases in learning to rank (L2R)?* LLMs are used ubiquitously in virtually all areas of NLP. This includes information retrieval (IR), where LLMs are used to, e.g., judge query-document pairs to predict relevance (see Fig. 6 in [Yutao et al. (2023)](https://arxiv.org/pdf/2308.07107)). In the context of cross-lingual IR (CLIR), we previously showed that multilingual pre-trained language models trained on English data suffer from monolingual overfitting [Litschko et al. (2023)](https://aclanthology.org/2023.findings-acl.193/), i.e. they are biased towards predicting relevance based on keyword matches instead of semantic matches. We showed that bias can be mitigated by code-switching query and document tokens. The focus of this thesis is to (a) explore whether LLMs also suffer from monolingual overfitting and (b) if replacing random tokens with their translations improve their CLIR performance. This question can be investigated through the lens of prompt engineering, in-context L2R or instruction-tuned LLMs.  Level: MSc.

<a name="v3"/>
### V3: Natural Language Understanding, Semantic & Pragmatics, Computational Social Science

#### Selected research projects

- *Understanding Indirectness.* Indirectness involves for example indirect answers to requests that do not explicitly contain
answer clues like Yes, yeah or no. Example: Q: Do you wanna crash on the couch? A: I gotta go home sometime. Indirect answers are natural in human dialogue, but very difficult for a conversational AI system. This thesis project evolves around creating technology that can better deal with indirectness, for example by improving indirectness classifiers, creating novel datasets or integration of context, for example by modeling longer dialogue context. The exact project scope will be determined with the student. References: [Louis et al., 2020](https://aclanthology.org/2020.emnlp-main.601/), [Damgaard et al., 2021](https://aclanthology.org/2021.codi-main.1/) and [Sanagavarapu et al., 2022](https://aclanthology.org/2022.naacl-main.345/), [Yusupujiang & Ginzburg, 2023](https://aclanthology.org/2023.sigdial-1.30/), [Müller and Plank, 2024](https://aclanthology.org/2024.lrec-main.791/) Level: MSc (preferred), BSc (possibly).


<a name="v4"/>
### V4: Human-centric Natural Language Understanding: Uncertainty, Perception, Cognition, Vision, Interpretability

Some general references for this section:
References: [Plank, 2016.](https://arxiv.org/abs/1608.07836), [Jensen and Plank, 2022](https://aclanthology.org/2022.lrec-1.161/), [Plank, 2022 EMNLP](https://arxiv.org/abs/2211.02570) 

#### Selected research projects 

- *In-context learning from human disagreement on subjective tasks.* 
Aggregating annotations via majority vote could lead to ignoring the opinions of minority groups, especially on subjective tasks. Learning from individual annotators shows a better result on subjective classification tasks such as hate speech detection and emotion detection than from the majority vote (Davani et al., 2022). In this project, we want to investigate the potential of learning from individual annotators in an in-context learning setting. How can the model learn from the disagreement between annotators by instruction tuning and prompting? How do we design such instructions?
References: [Davani et al., 2022](https://aclanthology.org/2022.tacl-1.6/), [Schick et al., 2021](https://arxiv.org/abs/2001.07676) and [Mishra et al., 2022](https://aclanthology.org/2022.acl-long.244.pdf). Level: MSc.

- *Beyond the Multiple Choice Survey Question: Evaluating LLM's opinion in realistic settings.*  Multiple choice questions play a crucial role in LLM evaluation studies. Given an instruction and example QA pairs, the LLM is asked to pick the preferred answer, such as the MMLU benchmark ([Hendrycks et al. 2021](https://arxiv.org/abs/2009.03300)). Other than objective tasks such as math questions, survey questions are also used to evaluate LM's opinion ([Santurkar et al. 2023](https://arxiv.org/abs/2303.17548)). However, it is still unclear how well the survey question responses of the LM represent its behavior in real-world scenarios.  In this work, we want to investigate how representative the survey question evaluation result is and develop an open-ended generation task for evaluating LLM in a realistic setting. Level: BSc, MSc.

<!-- - :hourglass_flowing_sand: *Active learning for Vision Question Answering with Large Pretrained Models.* There were several attempts on active learning for VQA ([Jedoui et al. 2019](https://arxiv.org/abs/1912.01119), [Karamcheti et al. 2021](https://aclanthology.org/2021.acl-long.564.pdf)). However, these models are small in size and were trained from scratch. Large Pre-trained Models have achieved great success in unimodality (language or vision) and multimodality (vision-language) settings ([Li et al. 2022](https://arxiv.org/abs/2201.12086)). This project aims to deploy SOTA foundation models in the active learning framework for VQA tasks. A starting point could be re-implementing some VQA active learning works such as Jedoui et al. (2019). Level: MSc.
-->
<!--

- ~~*Reasoning Back to Consistency.*~~ Evaluating Causality in Large Language Models: While formal logic is monotonic, i.e. once a valid conclusion is drawn, no additional valid premise can refute it, our everyday reasoning is often non-monotonic ([Johnson-Laird & Byrne 1991](https://philpapers.org/rec/JOHD-9)). For instance, conclusions are often withdrawn based on new evidence or assumptions that do no longer hold. According to [Johnson-Laird (2011)](https://doi.org/10.1017/CBO9780511818714.007), when an inconsistency of an expected outcome is encountered, reasoning back to consistency appears to involve three main steps: detection of the inconsistency, revision of beliefs, and generation of a diagnostic explanation that resolves the inconsistency. A study by [Johnson-Laird et al. (2004)](https://doi.org/10.1037/0033-295X.111.3.640) investigates the preferences of individuals regarding diagnostic explanations for inconsistencies in reasoning. Interestingly, cause-and-effect relations play a pivotal role for the perceived plausibility of explanations, and thus are a driving aspect for our understanding of the world. In this project, we aim to replicate the study by Johnson-Laird et al. (2004) with a focus on evaluating which diagnostic explanations are considered most probable by Large Language Models (LLMs). Through this endeavor, we aim to assess whether LLMs align with the human-centric concept of causality in their reasoning processes. Level: MSc.

- ~~*Solving Murder Mysteries: An Evaluation of Causal Reasoning in Large Language Models.*~~ Large Language Models (LLMs) have shown remarkable capabilities in various domains, yet their proficiency in complex causal reasoning remains largely unexplored ([Kıcıman et al. 2023](https://doi.org/10.48550/arXiv.2305.00050), [Zečević et al. 2023](https://doi.org/10.48550/arXiv.2308.13067), [Zhang et al. 2023](https://doi.org/10.48550/arXiv.2304.05524)). This project seeks to employ a dataset of murder mystery riddles as a means to assess the causal reasoning abilities of large language models. Such riddles provide a structured yet creative way to assess how well LLMs can formulate cause-and-effect hypotheses and derive logical conclusions from observations ([Lagnado & Gerstenberg 2017](https://doi.org/10.1093/oxfordhb/9780199399550.013.30), [Sun et al. 2023](https://arxiv.org/abs/2311.09648), [Pearl 2013](https://doi.org/10.1017/CBO9780511803161)). The objectives of this study are multifaceted. Based on [Del & Fishel (2023)](https://aclanthology.org/2023.starsem-1.28/), it aims to establish a new benchmark consisting of a diverse collection of short murder mystery riddles, each characterized by a clearly defined cause-and-effect framework. Secondly, the study is designed to assess the causal reasoning and deductive problem-solving skills of LLMs. Thirdly, it seeks to identify the specific strengths and limitations of current open-source LLMs in tasks that require causal reasoning. Anticipated outcomes of this research encompass a quantitative evaluation of LLM performance in causal reasoning tasks, qualitative insights into the reasoning process, and the identification of key areas for improvement. Level: MSc.
--> 

- *Understanding disagreement in human-generated scores.* Large collections of human evaluations on a scale (e.g., how concrete word X is on a scale from 1 to 5) are crucial for modeling various linguistic phenomena (e.g., figurative language use). These collections typically report an average score derived from numerous participants. However, this method of averaging can be highly deceptive, especially when individual scores vary significantly and the average score converges to a middle-range score. This project aims to explore the characteristics of words that achieve mid-scale average scores, examining their lexical attributes (like frequency), distributional properties (such as associations with other words), and behavioral and cognitive aspects (for instance, emotional connotations). This study will build on the existing work by [Knupleš et al. (2023)](https://aclanthology.org/2023.conll-1.6/). Expected skills: regression analysis, cluster analysis, data visualization. Level: MSc.




