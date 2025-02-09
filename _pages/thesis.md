---
layout: page
permalink: /thesis/
title: Thesis
description:
nav: true
nav_order: 5
---

Interested in writing your MSc or BSc thesis with us? We offer several BSc and MSc thesis topics at MaiNLP.

Currently, the following research vectors characterize broad topics in which we offer MSc and BSc thesis projects. We provide a (non-exhaustive) list of research projects within each vector. We are also interested to supervise projects related to our [research projects](https://mainlp.github.io/projects/). You are welcome to send us your own project proposal. We recommend to check out the suggested/selected publications to get inspired.

Unless otherwise specified, all projects can be either at the MSc or BSc level. The exact scope of the project will be determined in a meeting before the start of the project.

_Important note_: We currently do not supervise industrial MSc/BSc thesis projects (Industrieabschlussarbeiten).

Regularly <b>check back here for updates</b> on thesis project suggestions.

News:

<!-- - 2024, Feb 26: Thank you all for your interest! We are closed for further thesis applications for the upcoming summer semester  -->

- 2025, Jan 27: Updated projects and application deadlines posted
- 2024, Sep 1: MSc/BSc project applications deadlines posted. See list of project below and how to apply <a href="#howtoapply">here</a>

Legend:

- :hourglass_flowing_sand: topic currently reserved
- ~~strikethrough~~ topic no longer available

<a name="howtoapply"/>
### How to apply for a BSc and MSc thesis project

**Important information for LMU students:** You need to apply for a MSc/BSc thesis project the latest three weeks before the thesis project registration date.

<!--Deadlines for the winter semester 2024-2025:

- MSc students apply before **September 4, 2024**
- BSc students apply before **September 14, 2024**
-->

Deadlines for the summer semester 2025:

- MSc students apply before **Monday February 10, 2025**
- BSc students apply before **Monday February 24, 2025**

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

**MSc/BSc thesis research vectors:**

<div class="accordion-section">
  <div class="accordion-header" onclick="toggleAccordion(this)">
    V1: NLP for Dialects, Low-resource and Multilinguality
  </div>
  <div class="accordion-content">
  {{ "### **Selected Research Projects**
- *NLP for dialectal/non-standard language data*. You are welcome to propose
thesis projects related to processing dialectal or non-standard language data.
Selected example projects are given below. Please include the following information
in your application: (1) the dialect(s)/language(s) you are interested in working with
and your familiarity with them, (2) one or more NLP tasks you would be interested in
working on, (3) links to relevant datasets (some starting points for finding datasets:
Germanic low-resource languages/dialects – [Blaschke et al. 2023](https://aclanthology.org/2023.nodalida-1.41.pdf) ([web overview](https://github.com/mainlp/germanic-lrl-corpora)),
regional languages of Italy – [Ramponi 2024](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00631/119058/Language-Varieties-of-Italy-Technology-Challenges), Arabic dialects – [Guellil et al. 2021](https://www.sciencedirect.com/science/article/pii/S1319157818310553?via%3Dihub))
and/or details on what kind of data you would like to collect/annotate, and (4) what
focus you are most interested in (modelling/engineering, linguistically motivated error
analysis, etc. – you are very welcome to pitch specific research questions here).
General reference: [Zampieri et al. 2020](https://www.cambridge.org/core/journals/natural-language-engineering/article/natural-language-processing-for-similar-languages-varieties-and-dialects-a-survey/229652C86E329F83346BB6C66B9521A6). **Level: BSc or MSc.**
- *Analyzing dialect identification systems*. How well can we automatically
discern between different closely related language varieties, and do the
features that are relevant to the success of an automatic classifier correlate
with those that linguists would describe? You can decide on the language
varieties to be included in the thesis, provided that high-quality, accessible
corpora are available. (See above for starting points for finding datasets. If
you prefer to work with a language not covered in these overviews, please
contact us early on.) You can also decide which thematic focus/foci the thesis
should have: (i) linguistic analysis of the data and classifier output; (ii)
applying interpretability methods to the classifier output (in conjunction with
focus i); (iii) comparing different kinds of input representations and ML
architectures, including speech. The specific focus and level of detail will
depend on your background and skills as well as the degree (BSc vs. MSc).
Additional references: [Gaman ea. 2020](https://aclanthology.org/2020.vardial-1.1/) and other VarDial shared task papers
for literature on automatic dialect identification, [Nerbonne ea. 2021](https://www.let.rug.nl/nerbonne/papers/Nerbonne-etal-CompDial2020.pdf) and [Wieling & Nerbonne 2015](https://www.annualreviews.org/content/journals/10.1146/annurev-linguist-030514-124930) for introductions to dialectometry; [Madsen ea.
2022](https://dl.acm.org/doi/pdf/10.1145/3546577) and [Barredo Arrieta ea. 2020](https://www.sciencedirect.com/science/article/pii/S1566253519308103) for overviews of interpretability methods. **Level: BSc or MSc.**
- :hourglass_flowing_sand: *Using LLMs for Slot and Intent Detection for Low-Resource Dialects*.
Digital assistants are becoming wide-spread, yet current technology covers
only a limited set of languages. How can we best use LLMs or linguistic
resources to improve slot and intent detection on low-resource language
variants without standard orthography? References: [van der Goot et al.,
2021](https://aclanthology.org/2021.naacl-main.197.pdf) , [VarDial 2023 SID4LR](https://sites.google.com/view/vardial-2023/shared-tasks), [Winkler et al., 2024](https://aclanthology.org/2024.lrec-main.1297.pdf), [Krückl et al., 2025](https://arxiv.org/pdf/2501.03863?). Several
directions are possible: a) Look into ways to generate and evaluate dialectal
data, or b) create a new evaluation dataset of a low-resource language
variant you speak and which is not covered yet in xSID (see papers above),
or c) finding novel ways of evaluation like LLMs vs encoder-based models.
Topics: Cross-linguality, Dataset annotation (particularly suited for students
interested in covering their own language or dialect not yet covered by
existing systems including local dialects), Evaluation. **Level: BSc or MSc.**
- *Creating a dialectal dependency treebank or POS-tagged corpus*. Create
a small Universal Dependencies (UD; [de Marneffe et al. 2021](https://direct.mit.edu/coli/article/47/2/255/98516/Universal-Dependencies)) treebank in a
dialect, regional language or other low-resource language that you are
familiar with and for which no UD corpus exists yet. For a less time-intensive
project, it is also possible to only annotate part-of-speech (POS) tags
(otherwise: POS tags + dependencies) and complement the project with
something else. This project requires a strong interest in linguistics and
syntax. You will need to read up on UD’s annotation guidelines and
independently seek out relevant linguistic literature on your chosen language.
You also evaluate parsers/POS taggers on your new dataset in a
cross-lingual transfer set-up and, time permitting, you might also train your
own parsers. Ideally, the project leads to contributing a new treebank to the
UD project. Examples of similar corpora: [Siewert et al. 2021](https://aclanthology.org/2021.konvens-1.25/), [Hollenstein &
Aepli 2014](https://aclanthology.org/W14-5310/), [Cassidy et al. 2022](https://aclanthology.org/2022.acl-long.473/), [Lusito & Maillard 2021](https://aclanthology.org/2021.udw-1.10/), [Blaschke et al. 2024](https://aclanthology.org/2024.lrec-main.953/).
[Tutorial for UD newcomers](https://unidive.lisn.upsaclay.fr/doku.php?id=other-events:webinar-1). **Level: BSc.**
- :hourglass_flowing_sand:  *Lexical Resources for Dialects*. NLP for dialect languages is an intriguing
area of research due to the lack of resources (low-resources languages) and
lack of standardization (high variance). In this project, the goal is to build
dialect dictionaries by annotating words and phrases with respect to different
linguistic properties including parts-of-speech, cases and grammatical
genders. For this, we have collected raw data in several German dialects. It is
therefore important that the student is familiar with one or more of the
following dialects: Alemannic (Alemannisch), Palatinate (Pfälzisch), North
Frisian (Nordfriesisch), Saterland Frisian (Saterfriesisch), Bavarian (Bairisch),
Low German (Niederdeutsch/Plattdeutsch), Colognian (Kölsch). The second
part consists of using these dictionaries to either 1) systematically investigate
the linguistic dialect competence of pre-trained language models or 2)
develop IR-specific resources (dialect stopword lists, dialect lemmatizers,
dialect stemmers). This project does not need access to GPUs and is **suitable for BSc and MSc students.**
- :hourglass_flowing_sand: *Transfer or translate: how to better work with dialectal data*. Demands for
generalizing NLP pipelines to dialectal data are on the rise. Given current
LLMs trained in hundreds of languages, there are two common approaches.
The first approach is to translate (or normalize) dialectal data to its
mainstream counterpart and apply pipelines to the translated mainstream
counterpart. Such an approach can benefit from the bigger amount of
unannotated and annotated data in the mainstream variant but suffers from
error propagation in the pipeline. The second transfer approach is to annotate
a small amount of dialectal data and few-shot transfer (finetune) models on
the dialect. This involves more dialectal annotation as well as collected
unannotated dialectal data. Reference: [Zampieri et al. 2020](https://helda.helsinki.fi/server/api/core/bitstreams/dd1636da-66ef-4e2d-bdb7-19c0b27080f3/content). For a BSc
thesis, you would choose an NLP task (e.g., syntactic or semantic parsing,
sentiment or stance detection, QA or summarization, etc.) and a specific
dialect, compare performances of fewshot versus translation approaches
quantitatively, and conduct a qualitative error analysis on the difficult cases.
For MSc, the research needs to scale up either to multiple dialects (in the
same or across different language families) or to multiple NLP tasks. **Level:
BSc or MSc.**
- :hourglass_flowing_sand: *To What Degree do LLMs Understand Bavarian Dialect Variants?* In this
project, we aim to comprehensively evaluate existing multilingual and
German LLMs on Bavarian dialect variants. Your task is to come up with a
set of evaluation criteria to test existing LLMs in zero-shot and few-shot
manner, starting from existing benchmarks but with the aim to go beyond
them, systematically comparing LLMs with traditional fine-tuning approaches,
and finding out when and why certain methods struggle. Techniques:
In-depth Evaluation, LLMs, Fine-tuning, Behavioral Testing. **Level: MSc.**
- *Lexical Dialect Information Retrieval*. Retrieving relevant documents
across language boundaries has been a longstanding task in the IR
community. In our recent work ([Litschko et al., 2025](https://arxiv.org/abs/2412.12806)), we focus on
cross-dialect information retrieval (CDIR), where queries are written in
standard German and documents in German dialects. Compared to
cross-lingual IR (CLIR), CDIR poses unique challenges due to the lack of
standardization. For example, models need to match the query term
München with documents containing dialect variations: Münch’n, Minkcha,
Minkn, Minchn, Mingna, Minkhn, Münchn. There are multiple thesis topics
possible here:
  1. Extend dialect IR to another language (e.g., to a Chinese or
      Arabic dialect) and evaluate different retrieval models on it. This thesis
      does not require access to GPUs and is **suitable for B.Sc. and M.Sc.**
      students.
  2. Provide an in-depth and systematic qualitative analysis of LLMs
      as dialect translation models. **Suitable for B.Sc. students.**
  3. Extend CDIR to multi-dialect retrieval, where the corpus
      contains documents in different dialects. The goal of this topic is to investigate weak vs. strong alignment of IR models ([Roy et al., 2020](https://aclanthology.org/2020.emnlp-main.477/) with respect to dialects. **Suitable for B.Sc. and M.Sc. students.**

" | markdownify }}

  </div>
</div>

<div class="accordion-section">
  <div class="accordion-header" onclick="toggleAccordion(this)">
    V2: Data-centric NLP, NLP Applications, High-Quality Information Extraction and Retrieval 
  </div>
  <div class="accordion-content">
    {{ "### **Selected Research Projects**
- :hourglass_flowing_sand: *NLP for Job Market Analysis*. Job postings are a rich resource to understand the
dynamics of the labor market including which skills are demanded, which is also
important from an educational viewpoint. Recently, the emerging line of work on
computational job market analysis or NLP for human resources has started to
provide data resources and models for automatic job market analysis, such as the
identification and extraction of skills in job postings, or the prediction of career paths.
For students interested in real-world applications, this theme provides multiple thesis
projects including but not limited to: cross-lingual or cross-domain skill and
knowledge extraction to data sources like job postings, patents or scientific articles.
Alternatively, the project could focus on career path prediction, the task of predicting
a person's next occupation based on their resume. [See references of MultiSkill
project](https://mainlp.github.io/projects/#multiskill). See also [Bhola et al., 2020](https://aclanthology.org/2020.coling-main.513.pdf), [Gnehm et al. 2021](https://www.zora.uzh.ch/id/eprint/230653/1/2022.nlpcss_1.2.pdf), [our own ESCOXLM-R model](https://aclanthology.org/2023.acl-long.662.pdf)
and the [Karrierewege dataset](https://arxiv.org/pdf/2412.14612). **Level: BSc or MSc.**
- *Climate Change Insights through NLP*. Climate change is a pressing issue
internationally that is receiving more and more attention everyday. It is influencing
regulations and decision-making in various parts of society such as politics,
agriculture, business, and it is discussed extensively on social media. For students
interested in real-world societal applications, this project aims to contribute insights
on the discussion surrounding climate change. Example projects: a) Analyzing social
media data. The data will have to be collected (potentially from existing sources),
cleaned, and analyzed using NLP techniques to examine various aspects or features
of interest such as stance, sentiment, the extraction of key players, etc. References:
[Luo et al., 2020](https://aclanthology.org/2020.findings-emnlp.296v2.pdf), [Stede & Patz, 2021](https://aclanthology.org/2021.nlp4posimpact-1.2.pdf), [Vaid et al., 2022](https://aclanthology.org/2022.acl-srw.35.pdf). **Level: BSc or MSc**.
- :hourglass_flowing_sand:  *Better Benchmarks / Mining for Errors in Annotated Datasets*. Benchmark
datasets are essential in empirical research, but even widely-used annotated
datasets contain mistakes, as annotators inevitably make mistakes (e.g. annotation
inconsistencies). There are several lines of work in this direction. On the one side,
annotation error detection methods provide a suite of methods to detect errors in
existing datasets (cf. [Klie et al. 2023](https://direct.mit.edu/coli/article/49/1/157/113280/Annotation-Error-Detection-Analyzing-the-Past-and), [Weber & Plank 2023](https://aclanthology.org/2023.findings-acl.562/), [Weber-Genzel et al.
2024](https://aclanthology.org/2024.acl-long.123.pdf) ), including tools such as data maps ([Swayamdipta et al. 2020](https://aclanthology.org/2020.emnlp-main.746.pdf)). On the other
side, there is work on inspecting existing datasets in revision efforts that exist for
English NER in the past year (cf. [Reiss et al. 2020](https://aclanthology.org/2020.conll-1.16/), [Rücker & Akbik 2023](https://aclanthology.org/2023.emnlp-main.533.pdf)). The goal
of projects on this theme can be:
  1. (**MSc level**) to investigate error detection
  methods in novel scenarios (new benchmarks, new applications, and/or create a new
  error detection dataset)
  2. (**MSc or BSc level**) extend revision efforts on NER to
  other languages. For the latter, for a BSc thesis, your task includes improving a
  benchmark dataset with iterations of sanity checks and revisions and comparing NLP
  models on the original versus revised versions. For MSc, you could extend either by incorporating Annotation Error Detection methods (see previous part) or conducting additional evaluations on multiple downstream NLP tasks.
  3. (**BSc or MSc level**)
  Checking the annotation consistency of non-standardized language data. Automatic
  methods for finding potential inconsistencies in annotations typically rely on
  consistent orthographies (e.g., detecting sequences that occur multiple times in a
  corpus but have received different annotations; [Dickinson & Meurers 2003](https://aclanthology.org/E03-1068/)). When
  text is written in a language variety without a standardized orthography, such
  methods may no longer work well because of spelling differences between the
  repeated sequences. Your task is to extend such approaches to detect errors in
  existing datasets to be more robust to orthographic variation and/or to investigate
  how well annotation error detection methods that do not directly depend on
  orthographic matches work (cf. [Klie et al. 2023](https://direct.mit.edu/coli/article/49/1/157/113280/Annotation-Error-Detection-Analyzing-the-Past-and)). The target dataset would ideally be
  one of the [dialectal datasets](https://dialect-erc.github.io/resources/) developed at the lab (this requires familiarity with
  German dialects and, depending on the dataset, an interest in syntax).
  4. (**MSc Level**) To explore the nature and consequences of annotation errors in classification
  tasks. First, you need to seek to demonstrate that annotation errors behave more like
  random noise rather than reflecting human label variation, thereby disentangling their
  influence on model training and evaluation. Building on this insight, you’re
  encouraged to develop automated methods for detecting and removing such errors.
  Preliminary experimental results from the VariErr dataset ([Weber et al., 2024](https://aclanthology.org/2024.acl-long.123/)) reveal
  two critical questions: (1) the process of self-correction is challenging for both
  humans and LLMs ([Goh et al., 2024](https://jamanetwork.com/journals/jamanetworkopen/article-abstract/2825395)), suggesting broader implications for error
  interpretation and generalization ; and (2) transitioning to datasets with extensive
  annotations and labels could mitigate the adverse effects of removing noisy labels,
  resulting in a smoother and more reliable label distribution.
- :hourglass_flowing_sand:  *Error Analysis of a BERT-based Search Engine*. Multi-stage ranking has become
a popular paradigm in information retrieval, this approach a fast first-stage ranker
generates a candidate set of documents followed by a much slower re-ranker to
refine the ranking ([Nogueira et al. 2019](https://arxiv.org/abs/1910.14424)). Prior work has shown that better candidate
sets (higher recall) don’t necessarily translate to a better final ranking ([Gao et al.
2021](https://arxiv.org/abs/2101.08751)). The goal of this thesis is two-fold: First, we would like to perform an error
analysis of linguistic triggers that cause this behavior. In the second part, the goal is
to apply and interpret automatically generated explanations from tools such as
DeepSHAP ([Fernando et al. 2019](https://arxiv.org/abs/1907.06484)) and LIME ([Riberio et al. 2016](https://arxiv.org/abs/1907.06484)). Basic knowledge
in information retrieval is helpful, but not required. **Level: B.Sc**.
- :hourglass_flowing_sand:  *Injecting Lexical Similarity Signals into Neural Information Retrieval (IR) Models*.
Early IR models rely on lexical signals (keyword matches) such as BM25, TF-IDF
and the Query Likelihood Model (QLM) between queries and documents to
determine their relevance. For a long time lexical retrieval models performed still very
competitively, outperforming neural retrieval in domain-specific settings [Thakur et al.
(2021)](https://arxiv.org/pdf/2104.08663). Reranking with cross-encoders (CE) is arguable among the most widely used
IR paradigms and frames relevance prediction as a sequence pair classification task
where inputs are constructed through concatenating query-document pairs “[CLS]
Query [SEP] Doc [SEP]”. In a recent work, [Askari et al (2023)](https://link.springer.com/chapter/10.1007/978-3-031-28244-7_5) showed that CEs
benefit from further including lexical input signals “[CLS] Query [SEP] BM25 [SEP]
Doc [SEP]”. The goal of this thesis is to conduct a systematic evaluation of additional
lexical signals (and combinations thereof) including, e.g., TF-IDF and QLM (reduced
scope, BSc) and semantic signals obtained from semantic similarity models or LLMs
(full scope, MSc). This thesis is suitable for students who do not have access to large
GPUs. **Level: BSc or MSc**.
- :hourglass_flowing_sand: *Do LLMs suffer from lexical biases in learning to rank (L2R)?* LLMs are used
ubiquitously in virtually all areas of NLP. This includes information retrieval (IR),
where LLMs are used to, e.g., judge query-document pairs to predict relevance (see
Fig. 6 in [Yutao et al. (2023)](https://arxiv.org/pdf/2308.07107)). In the context of cross-lingual IR (CLIR), we previously
showed that multilingual pre-trained language models trained on English data suffer
from monolingual overfitting [Litschko et al. (2023)](https://aclanthology.org/2023.findings-acl.193/), i.e. they are biased towards
predicting relevance based on keyword matches instead of semantic matches. We
showed that bias can be mitigated by code-switching query and document tokens.
The focus of this thesis is to (a) explore whether LLMs also suffer from monolingual
overfitting and (b) if replacing random tokens with their translations improve their
CLIR performance. This question can be investigated through the lens of prompt
engineering, in-context L2R or instruction-tuned LLMs. **Level: MSc.**
" | markdownify }}

  </div>
</div>

<div class="accordion-section">
  <div class="accordion-header" onclick="toggleAccordion(this)">
    V3: Natural Language Understanding, Semantic & Pragmatics, Computational Social Science
  </div>
  <div class="accordion-content">
    {{ "### **Selected Research Projects**
- :hourglass_flowing_sand: *Understanding Indirectness*. Indirectness involves for example indirect answers
to requests that do not explicitly contain answer clues like Yes, yeah or no. Example:
Q: Do you wanna crash on the couch? A: I gotta go home sometime. Indirect
answers are natural in human dialogue, but very difficult for a conversational AI
system. This thesis project revolves around creating technology that can better deal
with indirectness, for example by improving indirectness classifiers, creating novel
datasets or integration of context, for example by modeling longer dialogue context.
The exact project scope will be determined with the student. References: [Louis et al.,
2020](https://aclanthology.org/2020.emnlp-main.601/), [Damgaard et al., 2021](https://aclanthology.org/2021.codi-main.1/) and [Sanagavarapu et al., 2022](https://aclanthology.org/2022.naacl-main.345/), [Yusupujiang &
Ginzburg, 2023](https://aclanthology.org/2023.sigdial-1.30/), [Müller and Plank, 2024](https://aclanthology.org/2024.lrec-main.791/) **Level: MSc (preferred), BSc (possibly)**.
- :hourglass_flowing_sand: *Understanding Humor in “So Bad It’s Good”*. Humor is a complex and
multifaceted phenomenon, deeply rooted in linguistic creativity, cultural context, and
human cognition. Among its many forms, intentional “bad” writing—crafted to amuse
through its exaggerated flaws—offers a unique lens to study humor mechanisms.
The [Bulwer-Lytton Fiction Contest (BLFC)](https://www.bulwer-lytton.com/about) is an annual competition challenging
participants to compose humorously terrible opening sentences for fictional works
([The Lyttle Lytton Contest](https://adamcadre.ac/lyttle/) conveys the similar idea but limits entrants to 25 words).
Despite its lighthearted premise, the BLFC contest provides a rich corpus for
exploring how linguistic, narrative, and cultural factors converge to produce humor. In
the meantime, with the prevalent use of large language models (LLMs) and its
capability of generating (more or less) creative text (e.g. [Chakrabarty et al., CHI
2024](https://dl.acm.org/doi/10.1145/3613904.3642731), [Chen & Ding, EMNLP-findings, 2023](https://aclanthology.org/2023.findings-emnlp.858/)), a comparative study between human-
and LLM-generated entrants also adds a novel dimension to this exploration ([Horvitz
et al., ACL 2024](https://aclanthology.org/2024.acl-short.76/), [Baranov et al., EMNLP 2023](https://aclanthology.org/2023.emnlp-main.845/)). By combining computational analysis of linguistic patterns, qualitative
examination of narrative techniques, and (potentially) audience perception studies, this
thesis aims to provide insights into humor’s underlying mechanisms. This thesis project
not only contributes to linguistic and literary studies but also enhances our
understanding of how humor reflects and adapts to cultural and linguistic shifts, as well
as computational creativity, and the evolving role of AI in language generation. **Level:
MSc.**
- :hourglass_flowing_sand: *Exploring variations in discourse structures across genres and frameworks*.
Discourse structure plays a pivotal role in understanding how texts convey meaning,
organize information, and fulfill communicative goals. [The GUM corpus](https://gucorpling.org/gum/), with its
annotations in both Rhetorical Structure Theory (RST) and the Penn Discourse
Treebank (PDTB) frameworks, presents a unique opportunity to examine how
rhetorical relations vary across genres and frameworks. This thesis proposes a
comprehensive investigation into the interplay between genre-specific discourse
strategies and the theoretical underpinnings of these annotation frameworks.
Through a combination of quantitative and qualitative analyses, this research will
contribute to a deeper understanding of genre-dependent discourse patterns,
provide insights into the compatibility and limitations of RST and PDTB, and inform
the design of discourse-aware NLP systems that are robust across genres. For a
Master’s thesis project, the project should also involve an investigation of
incorporating genre-specific discourse patterns into a downstream task (e.g.,
summarization or question answering) to see if performance can be improved. **Level:
BSc or MSc**.
- *Evaluating extractive summarization with discourse features across genres*.
Rhetorical Structure Theory, or RST, which models texts hierarchically through
rhetorical relations between Elementary Discourse Units (EDUs), offers a
theoretically grounded method for identifying central discourse units (CDUs) that
represent the gist of a document. This discourse-driven perspective could provide
valuable insights for improving summarization techniques. However, CDUs are not
always synonymous with effective summaries. CDUs may not encapsulate the most
crucial content for all text genres or align with human intuitions of summary quality.
Genre effects—variations in rhetorical structures across text types—further
complicate the relationship between CDUs and summary efficacy. While prior work
(e.g., [Li et al., SIGDIAL 2016](https://aclanthology.org/W16-3617/); [Xu et al., ACL 2020](https://aclanthology.org/2020.acl-main.451/); [Hewett & Stede, COLING 2022](https://aclanthology.org/2022.coling-1.63/))
has demonstrated the utility of discourse structures for extractive or near-extractive
summarization, the specific potential of CDUs and their interaction with other salient
textual elements remains underexplored. This proposed thesis project addresses this
gap by evaluating the summarization quality of CDUs, their containing sentences,
and other salient units (e.g., sentences with different salience values) across multiple
genres. For a MSc’s level project, this thesis project is also expected to
systematically assess how RST-informed approaches compare to traditional
summarization methods and explore criteria that integrate discourse-level insights.
(For instance, [Hewett & Stede (2022)](https://aclanthology.org/2022.coling-1.63/) conducted experiments and analyses on a
German RST news dataset and showed that RST features (in particular nuclearity
and relations at the sentence-level) are informative, and they were able to transfer
these findings to various automated summarisation models.) **Level: BSc or MSc**.
- :hourglass_flowing_sand:  *Improving Automatic Text Simplification through Elaboration and Personalization*.
Automatic Text Simplification (ATS) aims to make complex texts more
understandable for different audiences, often by simplifying vocabulary and sentence
structures. However, research has shown that effective simplification often requires
elaboration — adding explanations or extra context to clarify difficult terms or
concepts ([Neha Srikanth at al., 2021](https://aclanthology.org/2024.emnlp-main.357/)) and LLMs have been shown to be limited in
the task ([Asthana, 2024](https://aclanthology.org/2024.emnlp-main.357/)). This thesis would explore ways to improve ATS by
incorporating elaboration strategies. Possible directions include: a) External
Knowledge Integration: how can external knowledge sources be used to add
elaboration and context during simplification? b) Personalization: How can
simplification techniques be personalized to specific user groups (e.g., children,
non-native speakers, or individuals with disabilities)? Other topics in the area of ATS are also possible. **Level: MSc** (projects on a
lower scope in the domain of ATS are also possible).
    " | markdownify }}
  </div>
</div>

<div class="accordion-section">
  <div class="accordion-header" onclick="toggleAccordion(this)">
    V4: Human-centric Natural Language Understanding: Uncertainty, Perception, Cognition, Vision, Social and Cultural Aware NLP, Interpretability
  </div>
  <div class="accordion-content">
    {{ "Some general references for this section: References: [Plank, 2016](https://arxiv.org/abs/1608.07836), [Plank, 2022
EMNLP](https://arxiv.org/abs/2211.02570), [Yang et al., 2024](https://arxiv.org/abs/2405.02411)

### **Selected research projects**

- :hourglass_flowing_sand: _In-context learning from human preference disagreement_. Aggregating
  annotations via majority vote could lead to ignoring the opinions of minority groups.
  Learning from individual annotators shows a better result on classification tasks such
  as hate speech detection, emotion detection and natural language inference than
  from the majority vote (Davani et al., 2022). In this project, we want to investigate the
  potential of learning from individual annotators in an in-context learning setting.
  Furthermore, we want to go beyond the classification datasets towards the human
  preference datasets. How can the model learn from the disagreement in the
  preference data in context? References: [Davani et al., 2022](https://aclanthology.org/2022.tacl-1.6/), [Chen et al.,2024](https://arxiv.org/pdf/2406.17600),
  [Zhang et al., 2024](https://arxiv.org/abs/2410.14632). **Level: MSc**.
- :hourglass_flowing_sand:  _Enhancing NLI Label Modeling with LLM-Generated Explanations: Annotation,
  Multilinguality, and Linguistic Perspectives_. Recent studies ([Chen et al., 2024a](https://aclanthology.org/2024.findings-emnlp.842/); [Chen
  et al., 2024b](https://arxiv.org/abs/2412.13942)) suggest that using human or LLM-generated explanations can help
  LLMs better model human label distributions in Natural Language Inference (NLI).
  Building on this, we propose three research directions. **Level: BSc or MSc**:
  - Annotation-focused: Develop a VariErr-like dataset ([Weber et al., 2024](https://aclanthology.org/2024.acl-long.123/))
    using LLM-generated explanations instead of human ones, with human
    annotators only validating whether the LLM explanations align with their
    reasoning. Annotators can flag cases where all LLM-generated explanations
    diverge from their intuition, significantly improving annotation efficiency.
  - Multilingual-focused: Analyze how LLM-generated label distributions vary
    across languages or incorporate multilingual explanation generation as a joint
    task.
  - Linguistic-focused: Explore existing datasets like liveNLI ([Jiang et al.,
    2023](https://aclanthology.org/2023.findings-emnlp.712/)), e-SNLI ([Camburu et al., 2018](https://proceedings.neurips.cc/paper/2018/hash/4c7a167bb329bd92580a99ce422d6fa6-Abstract.html)), and VariErr NLI ([Weber et al., 2024](https://aclanthology.org/2024.acl-long.123/)),
    where different explanations exist for the same label, to classify these
    explanations linguistically and observe the impact on LLM-generated label
    distributions.
- _Understanding disagreement in human-generated scores_. Large collections of
  human evaluations on a scale (e.g., how concrete word X is on a scale from 1 to 5)
  are crucial for modeling various linguistic phenomena (e.g., figurative language use).
  These collections typically report an average score derived from numerous
  participants. However, this method of averaging can be highly deceptive, especially
  when individual scores vary significantly and the average score converges to a
  middle-range score. This project aims to explore the characteristics of words that
  achieve mid-scale average scores, examining their lexical attributes (like frequency),
  distributional properties (such as associations with other words), and behavioral and
  cognitive aspects (for instance, emotional connotations). This study will build on the
  existing work by [Knupleš et al. (2023)](https://aclanthology.org/2023.conll-1.6/). Expected skills: regression analysis, cluster
  analysis, data visualization. **Level: MSc**.
- :hourglass_flowing_sand:  _Human-understandable descriptions of topic clusters_. Topic modelling is a core
  tool of fields like digital humanities and computational social sciences and recent
  developments like BERTTopic and SCA have made it possible to leverage word
  embeddings to find topics. These topic clusters are, however, difficult to analyse and
  additional tools like c-TF-IDF are necessary to make them human-understandable. In
  this thesis, we will implement and evaluate new techniques for describing topic
  clusters in a more robust and human-understandable way. References:
  [BERTTopic](https://maartengr.github.io/BERTopic/index.html), [SCA](https://arxiv.org/abs/2410.21054), [c-TF-IDF](https://maartengr.github.io/BERTopic/api/ctfidf.html). **Level: BSc**.
- :hourglass_flowing_sand: _Controlling models through state space analysis and manipulation_. Recent
  developments in model interpretability, often labeled as mechanistic interpretability,
  have made it possible to get a better understanding of the internal behavior of LLMs.
  In this project, we want to go one step further and leverage these insights to better
  control the output of LLMs. This project could be on a specific use case we have or
  do a more free exploration. References: [Anthropic](https://www.anthropic.com/news/golden-gate-claude), [Saphra & Wiegreffe](https://arxiv.org/abs/2410.09087), [Arditi et
  al.](https://arxiv.org/abs/2406.11717), [Singh et al.](https://dl.acm.org/doi/10.5555/3692070.3693926), **Level: MSc**.
- _Grokking_. “Grokking” [1] is a phenomenon observed when training deep neural
  networks. It is tied to the so-called double-descent curve and emergent abilities [2].
  The term describes a dynamic at train time where the model rapidly transitions from
  “memorizing” training samples to generalizing abstractions evidenced by a sharp rise
  in validation-set performance. It has been shown that for small toy-models grokking
  can be reliably triggered through a combination of weight decay and a critical dataset
  size [2]. However, the gap between these toy tasks and actual LLMs is still large. In
  this project, we want to take further steps towards exploring more complex settings
  and evaluate if grokking helps to better understand the learning processes of modern
  deep language models. References: [Power et al.](https://arxiv.org/abs/2201.02177), [Huang et al.](https://arxiv.org/abs/2402.15175), [Hupkes et al.](https://arxiv.org/abs/1908.08351v2) **Level:
  MSc**
- :hourglass_flowing_sand: _Understanding prompt instability_. It has been shown that LLMs are very unstable
  with regard to the prompts and even a small change like an inserted space or
  misspelled word can drastically change the generated output. In this project, we want
  to identify such instability situations and especially explore the reasons behind
  them. References: [Mizrahi et al.](https://aclanthology.org/2024.tacl-1.52/), [Shu et al.](https://aclanthology.org/2024.naacl-long.295/), [Zhao et al.](https://aclanthology.org/2024.findings-emnlp.412/)
  **Level: BSc or MSc**.
- _Analyzing Conditional Acceptability in Large Language Models_. This project
  explores how large language models assess the truth and acceptability of conditional
  statements (If A, then B). In cognitive psychology, there is an ongoing debate
  regarding the criteria humans use to judge the acceptability of conditionals. For
  instance, the _Conditional Probability Hypothesis_ ([Evans et al., 2003](https://psycnet.apa.org/record/2003-02055-013?doi=1); [Over et al.,
  2007](https://www.sciencedirect.com/science/article/pii/S0010028506000478?via%3Dihub)) posits that humans perceive conditional statements as acceptable when the
  conditional probability P(B|A) is sufficiently high. In contrast, other studies argue that
  conditional statements are judged acceptable when the antecedent (A) not only
  supports the consequent (B) but also increases its likelihood (P(B|A) > P(B))
  ([Douven and Verbrugge, 2012](https://www.tandfonline.com/doi/full/10.1080/13546783.2012.716009); [Skovgaard-Olsen et al., 2016](https://www.sciencedirect.com/science/article/pii/S0010027715301311?via%3Dihub)). In this project, we analyze how LLMs judge the acceptability of conditional
  statements, specifically whether they evaluate conditionals based on conditional
  probabilities alone or whether they incorporate relevance and evidential support.
  Through targeted experiments, we analyze LLM responses to a range of conditional
  statements under varying contexts, aiming to assess how LLM reasoning aligns with
  human cognitive patterns and identify opportunities to improve their processing of
  conditional logic.
  **Level: BSc or MSc**
- _Unveiling the Mechanisms of Soft Prompt Tuning in Cross-Lingual Transfer: An
  Interpretability-Driven Study_. This research aims to investigate why Soft Prompt
  Tuning (SPT) outperforms full-parameter fine-tuning (FT) in cross-lingual transfer
  tasks, where models trained in high-resource languages (e.g., English) are tested on
  low-resource languages. While SPT's superiority ([Tu et al., 2022](https://aclanthology.org/2022.findings-emnlp.401/); [Ma et al., 2023](https://aclanthology.org/2023.konvens-main.1/);
  [Park et al., 2023](https://arxiv.org/abs/2311.07820); [Philippy et al., 2024](https://aclanthology.org/2024.moomin-1.2/)) may stem from mitigating issues like
  monolingual overfitting, catastrophic forgetting, and multilingual tokenization, the
  underlying mechanisms remain unclear. Using advanced interpretability techniques
  ([Luo&Specia, 2024](https://arxiv.org/abs/2401.12874)) such as logit lens, probing tasks, and sparse autoencoders, this
  study will analyze how SPT preserves language-agnostic features, avoids common
  pitfalls of FT, and enhances cross-lingual generalization, by evaluating natural
  language understanding tasks like text classification and sequence labelling across
  diverse languages. **Level: Msc.**
- _Exploring the effectiveness and challenges of using LLM as evaluators_. Large
  Language Models (LLMs) have recently been explored as general-purpose
  evaluators for tasks such as text generation and classification. However, questions
  remain on their validity ([Bavanesco et al., 2024](https://arxiv.org/abs/2406.18403)), stability, and potential biases
  ([Panickssery et al., 2024](https://openreview.net/forum?id=4NJBV6Wp0h); [Zheng at al., 2024](https://dl.acm.org/doi/10.5555/3666122.3668142)). Specific topics in this area might
  include: a) analyzing LLM-as-evaluators sensitivity: how do slight changes in the
  input prompt, examples provided, or reference text affect the evaluation scores given
  by LLMs? b) domain and style variability: do LLMs perform consistently across
  different domains (e.g., scientific vs. literary texts) and linguistic styles (formal vs.
  informal)? How accurately do LLMs evaluate texts written by humans compared to
  those written by other machines? c) LLM biases: what biases might LLMs introduce
  in their evaluations, such as preference for verbosity, certain positions, or even their
  own training data? Related topics proposed from the student are also possible. [A
  recent survey](https://aclanthology.org/2024.emnlp-main.896.pdf) on leveraging LLMs as evaluators (for NLG tasks) was recently
  published by Li et al. **Level: MSc**.
- _Exploring Linear Directions in LLMs for Identifying Desirable Text Properties_.
  Recent studies have explored how specific properties can be captured using linear
  directions in LLM embeddings. For example, [Marks and Tegmark (2024)](https://arxiv.org/pdf/2310.06824) have found
  that true / false statements’ representations show a linear structure. [Sheng et al.
  (2024)](https://aclanthology.org/2024.emnlp-main.398.pdf) have explored a similar idea in evaluation, leveraging a linear direction to
  estimate text quality. Building on this line of work, this project aims at exploring
  whether these findings also transfer to other polar properties and to which extent
  they can be exploited for text evaluation. **Level: MSc**.
- _Gaze data for NLP_.
  The way in which our eyes move when reading a text can tell us a lot about the cognitive processes required for language understanding. For example, longer reading times indicate higher processing difficulty.
  In the past 10 years, a line of research has emerged that attempts to use gaze data obtained by eye tracking to improve NLP models for various tasks
  (e.g., [Barrett et al., 2016](https://aclanthology.org/P16-2094/), [Hollenstein & Zhang, 2019](https://aclanthology.org/N19-1001/), [Deng et al., 2023](https://aclanthology.org/2023.emnlp-main.400/), [Alaçam et al., 2024](https://aclanthology.org/2024.emnlp-main.11/)).
  A student project could involve investigating under which circumstances and for which NLP tasks gaze data can be beneficial, or whether we can achieve the same effect with artificially synthesized gaze data.
  References: [Hollenstein et al. (2019)](https://arxiv.org/abs/1904.02682), [Sood et al. (2020)](https://proceedings.neurips.cc/paper/2020/hash/460191c72f67e90150a093b4585e7eb4-Abstract.html), [Khurana et al. (2023)](https://aclanthology.org/2023.eacl-main.139/), [Bolliger et al. (2023)](https://aclanthology.org/2023.emnlp-main.960/).
  **Level: MSc**
- :hourglass_flowing_sand: _Investigating Information Asymmetry on Wikipedia_. Information asymmetry (IA)
  refers to the fact that the volume and type of information on the web varies between
  languages. For example, prior work by [Kolbitsch and Maurer (2006)](https://www.researchgate.net/profile/Josef-Kolbitsch/publication/200772707_The_Transformation_of_the_Web_How_Emerging_Communities_Shape_the_Information_We_Consume/links/00b7d52453fcba84d3000000/The-Transformation-of-the-Web-How-Emerging-Communities-Shape-the-Information-We-Consume.pdf) and [Callahan et
  al. (2011)](https://homes.luddy.indiana.edu/herring/callahan.herring.2011.pdf) find that articles about locally famous people (“local heroes”) are written in
  a more favorable way whereas articles about the same people written in other
  languages also discuss controversial aspects. As a result, monolingual search
  engines can produce culturally biased search results. The goal of this thesis is to
  investigate IA on Wikipedia. In the first part, the student is expected to devise an
  annotation schema that allows to systematically analyze IA and then use it to
  compare articles about “local heroes” in 2-3 different languages. The second part
  consists of delving deeper into measuring IA in an automated way. The student is
  expected to investigate different ways of applying unsupervised semantic similarity
  models (e.g. BERTScore proposed in [Zhang et al. (2019)](https://arxiv.org/abs/1904.09675)) or LLMs to identify IA.
  **This thesis is suitable for BSc students (under a reduced scope) and MSc students.**
  " | markdownify }}
    </div>
  </div>

<script>
function toggleAccordion(element) {
  element.classList.toggle('active');
  
  const content = element.nextElementSibling;
  content.classList.toggle('active');
  
  const allContents = document.querySelectorAll('.accordion-content');
  const allHeaders = document.querySelectorAll('.accordion-header');
  
  allContents.forEach(item => {
    if (item !== content) {
      item.classList.remove('active');
    }
  });
  
  allHeaders.forEach(header => {
    if (header !== element) {
      header.classList.remove('active');
    }
  });
}
</script>
