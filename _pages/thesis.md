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

- 2026, Feb 10: MSc thesis application deadline has passed
- 2026, Jan 15: MSc/BSc project applications deadlines posted. ~~New topics currently under development, stay tuned!~~
- 2026, Jan 19: New thesis topics posted.

Legend:

- :hourglass_flowing_sand: reserved
- ~~strikethrough~~ topic no longer available

<a name="howtoapply"/>
### How to apply for a BSc and MSc thesis project

**Important information for LMU students:** You need to apply for a MSc/BSc thesis project the latest three weeks before the thesis project registration date.

<!--Deadlines for the winter semester 2024-2025:

- MSc students apply before **September 4, 2024**
- BSc students apply before **September 14, 2024**
-->

<!--Deadlines for the summer semester 2025:

- MSc students apply before **Monday February 10, 2025**
- BSc students apply before **Monday February 24, 2025**
-->

<!--
Deadlines for the winter semester 2025-2026:

- MSc students apply before **September 1, 2025**
- BSc students apply before **September 14, 2025**
-->

Deadlines for the summer semester 2025-2026:

- MSc students apply before **Monday February 9, 2026**
- BSc students apply before **Monday February 16, 2026**

To apply, please send your application material with subject "[BSc (or MSc) thesis project at MaiNLP - inquiry Name and which semester]" to: **thesisplank@cis.lmu.de**

It should contain a single pdf with the following information:

- CV, your study program, full grade transcript
- Level: BSc or MSc thesis project
- Which theme or project interests you (optional: we are open to project proposals related to the research vectors or on-going research projects). If you are interested in multiple, list your preferences for up to **four** (ranked list: first priority, second priority, third priority, fourth priority)
- Languages and dialects you speak
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
  {{ "
This research vector covers methods and resources for processing dialectal, low-resource, and multilingual language data. It focuses on improving robustness, fairness, and coverage of NLP systems across languages and varieties, including cross-lingual transfer and data-efficient learning.

### **Thesis projects**

- *Computational Dialectology.* Language usage often differs based on sociodemographic background, where linguistic differences based on the geographical origin of the speaker are typically studied in the field of dialectology. While qualitative studies into dialectal differences have yielded valuable insights into language variation, such studies often rely on labor-intensive data collection, annotation, and analysis. As such, computational approaches to dialect differences have emerged as a possible method towards the large-scale study of dialects. For students interested in this project, multiple directions are possible, including (but not limited to): (a) interpretability of what features dialect models rely on for differentiation, (b) creation of (parallel) resources for dialect continua, (c) development of new methods to quantify dialectal or sociolinguistic variation, (d) adapting existing models to better accommodate dialect variation.
**References:** [Bartelds & Wieling 2022](https://aclanthology.org/2022.naacl-main.273/), [Bafna et al. 2025](https://aclanthology.org/2025.acl-long.989/), [Shim et al. 2026](https://arxiv.org/pdf/2601.02906).
**Level: BSc or MSc.** 

- *Methods for mining low-resource parallel corpora.* Parallel corpora are critical for developing and evaluating dedicated machine translation systems, as well as general-purpose large language models capable of translation. One strategy for obtaining such corpora is to mine unstructured text corpora (typically web crawls) for parallel sentences. However, standard methods typically score candidate sentences via cosine distance of their sentence embeddings, a method which requires strong sentence encoders. Such sentence encoders are typically weaker for very low-resource languages, including language varieties such as dialects. Strategies include: bootstrapping, building classifiers, coming up with simple heuristics such as word-edit distance, or relying on meta-data like HTML tags. Depending on the student's interest and academic level, this project can focus more or less on specific directions such as: evaluating the impact of different methods, methods for scoring candidate sentences, or strategies for obtaining candidate sentences.
**References:** [Improving Parallel Sentence Mining for Low-Resource and Endangered Languages - ACL Anthology](https://aclanthology.org/2025.acl-short.17/), [Obtaining Parallel Sentences in Low-Resource Language Pairs with Minimal Supervision - PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC9365574/)
**Level: BSc or MSc.**

- *Synthetic language variation for robust NLP.* Robust NLP entails models that can process human language variation, such as dialects and other language varieties. These varieties are typically characterized by high variation due to their orthography, lexicography, syntax, each of which present challenges to NLP. Furthermore, these varieties are typically low-resourced, such that we widely rely on transfer from standard language data to language varieties in building NLP models. One strategy for improving robustness to linguistic variation is to introduce synthetic variation. This can range from naive perturbation of characters in order to induce more varied tokenization of standard training data, to targeted de-standardization of training data.
**References:** [Improving Zero-Shot Cross-lingual Transfer Between Closely Related Languages by Injecting Character-Level Noise - ACL Anthology Neural](https://aclanthology.org/2022.findings-acl.321/), [Text Normalization for Luxembourgish Using Real-Life Variation Data - ACL Anthology](https://aclanthology.org/2025.vardial-1.9/)
**Level: BSc or MSc** (scope adjusted by languages covered, and complexity of the approaches).

- *Universal Dependencies for Underrepresented Language Varieties.* Universal Dependencies (UD) provides a cross-linguistically consistent framework for syntactic annotation, yet many language varieties and genres remain underrepresented. This thesis explores how existing UD annotations for a related standard language can be adapted to support annotation of a lower-resource variety or underrepresented genre (e.g., a regional variety, informal writing, or domain-specific text). The project will involve selecting a small corpus, analyzing where standard-language annotation guidelines break down, and producing a limited but linguistically principled UD annotation or conversion strategy. Additionally, one would analyze annotation challenges and experiment with downstream UD parsing. 
**Level: BSc or MSc** (scope adjusted by dataset size and depth of linguistic analysis and experiments).


- *Cross-lingual Semantic Disagreement in Human Annotations.* Human judgments about meaning often diverge across languages. This thesis investigates such cross-lingual semantic disagreement by comparing annotations produced independently in two languages spoken by the student (e.g., German–English, Mandarin–English, Russian–German). One could choose to work on NLP tasks such as natural language inference, sentiment or stance classification, discourse relation labeling, etc. The project will involve selecting a small parallel or comparable dataset (or conducting the translation yourself), designing a controlled annotation setup, and analyzing where and why label distributions diverge across languages. The goal is not to resolve disagreements, but to characterize systematic patterns of variation and relate them to linguistic differences such as tense, aspect, definiteness, evidentiality, or pragmatic conventions. 
**Level: BSc or MSc** (scope adjusted by dataset size and depth of linguistic analysis and experiments).


- *Dialect Variation Dictionaries and Evaluation.* A large amount of culture-specific knowledge is captured in dialect corpora. However, dialects pose a challenge due to their limited resources and high variability, with words frequently spelled differently, reflecting regional pronunciations. This thesis extends our previous research on the Bavarian dialect ([Litschko et al., 2025](https://aclanthology.org/anthology-files/pdf/findings/2025.findings-emnlp.762.pdf)) by exploring another dialect. The project consists of two main components: 1) Annotating pairs of German and dialect words to determine whether they are equivalent translations. A dataset will be provided for this purpose. 2a) Evaluating the ability of LLMs to &quot;understand&quot; the dialect through translation and word-pair classification tasks, or 2b) building and evaluating a rule-based lexical normalization model ([Millour and Fort, 2019](https://hal.science/hal-02280002v1/preview/Proceedings_of_Recent_Advances_in_Natural_Language_Processing.pdf); [Weissweiler and Fraser, 2018](https://link.springer.com/chapter/10.1007/978-3-319-73706-5_8)). To successfully complete this thesis, it is essential that the student has a strong understanding of one of the following dialects: Alemannic (Alemannisch), Palatinate (Pfälzisch), North Frisian (Nordfriesisch), Saterland Frisian (Saterfriesisch), Low German (Niederdeutsch), Colognian (Kölsch). Dialects of other languages can potentially also be considered, please reach out to us. 
**Level: BSc or MSc** (adjusted scope includes dialect-specific model adaptation).

<!--
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
- :hourglass_flowing_sand: *Creating a dialectal dependency treebank or POS-tagged corpus*. Create
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


- *To What Degree do LLMs Understand Bavarian Dialect Variants?* In this
project, we aim to comprehensively evaluate existing multilingual and
German LLMs on Bavarian dialect variants. Your task is to come up with a
set of evaluation criteria to test existing LLMs in zero-shot and few-shot
manner, starting from existing benchmarks but with the aim to go beyond
them, systematically comparing LLMs with traditional fine-tuning approaches,
and finding out when and why certain methods struggle. Techniques:
In-depth Evaluation, LLMs, Fine-tuning, Behavioral Testing. **Level: MSc.**

- *Transfer or translate: how to better work with dialectal data*. Demands for
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
-->
" | markdownify }}

  </div>
</div>

<div class="accordion-section">
  <div class="accordion-header" onclick="toggleAccordion(this)">
    V2: NLP Applications, Summarization and Information Retrieval 
  </div>
  <div class="accordion-content">
    {{ "
This theme covers applied NLP methods for impactful real-world domains (e.g., climate change, labor markets, education) and core applications such as summarization, information retrieval.

### **Thesis projects**

- :hourglass_flowing_sand:  *NLP for Computational Job Market Analysis.* Job postings and career paths are a rich resource to understand the dynamics of the labor market. For example, to track how  skills demands change, how career paths are affected and how educational demands may shift. Such changes have large social implications, as they can inform strategic long-term decisions of governments to react to changing structural demands in the labor force. Recently, the emerging line of work on computational job market analysis (also known as NLP for human resources) has started to provide data resources and models for automatic job market analysis, such as the identification and extraction of skills in job postings, or the prediction of career paths. For students interested in real-world applications, this theme provides multiple thesis projects for two application domains: i) understanding skills in job postings (e.g. cross-lingual or cross-domain skill and knowledge extraction to data sources like job postings, patents or scientific articles) See references of [MultiSkill](https://mainlp.github.io/projects/#multiskill) project. See also [Bhola et al., 2020](https://aclanthology.org/2020.coling-main.513.pdf), [Gnehm et al. 2021](https://www.zora.uzh.ch/id/eprint/230653/1/2022.nlpcss_1.2.pdf), our own [ESCOXLM-R](https://aclanthology.org/2023.acl-long.662.pdf) model  or ii) career path prediction, which is the task of predicting a person's next occupation based on their resume. See the [Karrierewege](https://arxiv.org/pdf/2412.14612) paper. 
**Level: BSc or MSc.**

- *Climate Change Insights through NLP.* Climate change is a pressing global issue that is receiving more and more attention. It is influencing regulations and decision-making in various parts of society such as politics, agriculture, business, and it is discussed extensively on social media. For students interested in real-world societal applications, this project aims to contribute insights on the discussion surrounding climate change. Example projects: Analyzing social media data. The data will have to be collected (potentially from existing sources), cleaned, and analyzed using NLP techniques to examine various aspects or features of interest such as stance, sentiment, the extraction of key players, etc. **References:** [Luo et al., 2020](https://aclanthology.org/2020.findings-emnlp.296v2.pdf), [Stede & Patz, 2021](https://aclanthology.org/2021.nlp4posimpact-1.2.pdf), [Vaid et al., 2022](https://aclanthology.org/2022.acl-srw.35.pdf). 
**Level: BSc or MSc.**

- :hourglass_flowing_sand: *Multi agent debate for summarization or simplification.* Automatic summarization (or simplification) is often performed in an end-to-end manner, using a single model (e.g., an LLM). Recent work on multi-agent systems suggests that “interaction” between LLMs can improve reasoning and reduce errors. This project explores whether multi-agent debate can improve summarization (or simplification) quality by having agents summarize the same document, critique each other's summaries, and provide a final version. The project might investigate, e.g., the effect of prompting different agents with different priorities (factuality, conciseness, etc), whether debate improves performance compared to single-pass summaries and/or whether certain aggregation strategies (rounds of critique, voting, consensus-building) outperform others.
**References:** [Du et al, ICLR 2024](https://openreview.net/forum?id=QAwaaLJNCk); [Koupaee et al, NAACL 2025](https://aclanthology.org/2025.naacl-long.609.pdf?utm_source=chatgpt.com); [Wan et al., NAACL 2025](https://aclanthology.org/2025.naacl-long.498/) 
**Level: MSc** (preferred); adaptation to BSc is also possible.
Other projects in summarization or simplification (e.g., resource building, multilinguality) are also possible depending on the student interests.

- *Improving the Cross-Lingual Alignment of IR Models.* Machine Translation (MT) and Cross-Lingual Information Retrieval (CLIR) are two interconnected Natural Language Processing (NLP) tasks. In CLIR, MT is typically used to translate queries at retrieval time (translate test) or to translate training data (translate train). Recent studies have proposed a novel approach: aligning the representation spaces of MT models with those of large language models to improve their performance in multilingual NLP tasks ([Acharya et al., 2025](https://aclanthology.org/2025.naacl-long.220.pdf); [Schmidt et al., 2024](https://aclanthology.org/2024.findings-emnlp.394.pdf); [Yoon et al., 2024](https://aclanthology.org/2024.acl-long.405/)). The goal of this project is to investigate the effectiveness of aligning internal representations within LLM-based IR models, and compare their performance to translation-based methods for CLIR across both high- and low-resource languages. Depending on the student’s interests, the focus of this project can be on cross-lingual retrieval or reranking. 
**Level: MSc.**

- :hourglass_flowing_sand: *Evaluating the quality and difficulty of exam questions.* When high-stakes educational assessments (like university entrance exams) are being developed, they usually need to be piloted with a large sample of test takers to make sure that the questions are of appropriate quality and difficulty. Recently, researchers have tried to use LLMs to predict these properties automatically, either directly or by simulating test takers at various levels of ability. However, out-of-the box LLMs are not very good at this. A student project could experiment with fine-tuning LLMs to match different ability levels or to directly evaluate properties such as item difficulty, discrimination, or guessability.
**References:** [Yaneva et al. (2024)](https://aclanthology.org/2024.bea-1.39/), [Acquaye et al (2025)](https://arxiv.org/abs/2601.09953), [Liu et al. (2025)](https://doi.org/10.1111/bjet.13570), [Gorgun & Bulut (2024)](https://doi.org/10.1111/emip.12663), [Laverghetta et al. (2022)](https://doi.org/10.1007/978-3-031-04572-1_12)
**Level: MSc.**

- *Negations, uncertainty, and hypothetical or conditional statements in medical texts.* In clinical notes, these cues may alter the interpretation of a medical situation, and it is crucial to correctly identify them and their scope. This thesis will focus on how well traditional systems (e.g., [Chapman et al., 2001](https://pubmed.ncbi.nlm.nih.gov/12123149/)) and large language models perform at identifying such linguistic cues and on their scope in clinical documentation (for comparable studies cf. [Su et al. 2024](https://pmc.ncbi.nlm.nih.gov/articles/PMC12092861) and [van Es et al. 2023](https://pmc.ncbi.nlm.nih.gov/articles/PMC9830789)). Students may either rely on existing gold-standard datasets ([BioScope](https://rgai.inf.u-szeged.hu/node/105), [NUBes](https://github.com/Vicomtech/NUBes-negation-uncertainty-biomedical-corpus), [IULA](https://eines.iula.upf.edu/brat//#/NegationOnCR_IULA/negation_iac_2_corr), ...) and emphasize modeling to improve performance, or create novel annotations from accessible clinical document corpora ([MIMIC](https://physionet.org/content/mimiciv/3.1/), [Cardio:DE](https://heidata.uni-heidelberg.de/dataset.xhtml?persistentId=doi:10.11588/data/AFYQDY), ...). Cross-lingual and cross-domain transfer learning may be included, given the scope of the thesis (cf. [Almudaifer et al. 2024](https://pubmed.ncbi.nlm.nih.gov/38849884/)).
**Level: BSc or MSc.**

<!--
### **Selected Research Projects**
- :hourglass_flowing_sand:  *NLP for Job Market Analysis*. Job postings are a rich resource to understand the
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
-  *Better Benchmarks / Mining for Errors in Annotated Datasets*. Benchmark
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
-  *Error Analysis of a BERT-based Search Engine*. Multi-stage ranking has become
a popular paradigm in information retrieval, this approach a fast first-stage ranker
generates a candidate set of documents followed by a much slower re-ranker to
refine the ranking ([Nogueira et al. 2019](https://arxiv.org/abs/1910.14424)). Prior work has shown that better candidate
sets (higher recall) don’t necessarily translate to a better final ranking ([Gao et al.
2021](https://arxiv.org/abs/2101.08751)). The goal of this thesis is two-fold: First, we would like to perform an error
analysis of linguistic triggers that cause this behavior. In the second part, the goal is
to apply and interpret automatically generated explanations from tools such as
DeepSHAP ([Fernando et al. 2019](https://arxiv.org/abs/1907.06484)) and LIME ([Riberio et al. 2016](https://arxiv.org/abs/1907.06484)). Basic knowledge
in information retrieval is helpful, but not required. **Level: B.Sc**.
- *Injecting Lexical Similarity Signals into Neural Information Retrieval (IR) Models*.
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
- *Do LLMs suffer from lexical biases in learning to rank (L2R)?* LLMs are used
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
-->
" | markdownify }}

  </div>
</div>

<div class="accordion-section">
  <div class="accordion-header" onclick="toggleAccordion(this)">
    V3: Natural Language Understanding, Semantic & Pragmatics, Computational Social Science
  </div>
  <div class="accordion-content">
    {{ "
This theme covers aspects of uncertainty and ambiguity in human language and perception, including human label variation, subjective judgments, and cognitive factors affecting interpretation. It explores how NLP systems can model, reason about, and interact with uncertainty across text and multimodal settings, or how gaze data can inform modeling or evaluation, with an emphasis on human-centered evaluation and design.
    
### **Thesis projects**

- *Characterizing Ambiguity and Errors in Open-Domain QA Datasets.* Benchmark datasets are central to progress in open-domain question answering (QA), yet they often contain unresolved ambiguities or annotation errors (cf. [Klie et al. 2023](https://direct.mit.edu/coli/article/49/1/157/113280/Annotation-Error-Detection-Analyzing-the-Past-and), [Weber-Genzel et al. 2024](https://aclanthology.org/2024.acl-long.123.pdf)) that affect both model training and evaluation. This project focuses on a systematic data analysis of open-QA benchmarks like [AmbigQA](https://nlp.cs.washington.edu/ambigqa/) to characterize common sources of ambiguity (e.g., entity, event, and temporal ambiguity or underspecification, see for example [Tang et al., 2025](https://arxiv.org/pdf/2504.12113)) and may identify possible annotation errors in existing QA datasets. **BSc-level:** Using exploratory data analysis, annotation and predictive modeling with lightweight traditional interpretable classifiers, to investigate whether surface-level features can be used to identify and predict different ambiguity or error types. The outcome is a taxonomy of ambiguity and errors in open-QA datasets, empirical insights into how frequently these phenomena occur, and a prototype classifier to identify the ambiguity categories. 
**MSc-level** extensions include using LLMs for ambiguity characterization and generation and analysis of multiple interpretations ([Saparina & Lapata, 2025](https://arxiv.org/abs/2511.10453)), analyze LLM model output behavior (e.g. like in language-vision [Testoni et al., 2025](https://aclanthology.org/2025.emnlp-main.1206/) or text-based LLMs [Sedova et al, 2025](https://aclanthology.org/2024.findings-emnlp.1003/)), or alternatively, connect ambiguity characterizations identified in the first step to model-internal mechanisms like uncertainty or probing. The outcome is a taxonomy of ambiguity and errors in open-QA datasets, and an evaluation of how LLM output behavior (types of answer) or model-internal mechanisms relate to input ambiguity. 
**Level: BSc or MSc.**

- *Interpreting Visual Ambiguity:* Humans and Vision-Language Models. The objective of this thesis is to investigate ambiguity in images and to compare how humans and Vision-Language Models perceive and resolve such ambiguity. Ambiguous images often contain multiple salient elements or support multiple plausible interpretations. While humans show attention shifts depending on context, expectations, and individual differences, what models do? Depending on the student’s interests, this thesis can focus more on modeling approaches or on human strategies for processing ambiguity (e.g., through behavioral or eye-tracking experiments). **References:** [Hindennach et al., 2024](https://dl.acm.org/doi/10.1145/3649902.3656356), [Testoni et al., 2025](https://aclanthology.org/2025.emnlp-main.1206.pdf)
**Level: MSc.**

- :hourglass_flowing_sand:  *Beyond Probability Metrics:* Evaluating Free-Form Rationales for Disagreement: Current approaches to Human Label Variation (HLV) mostly treat the problem as a distribution-matching task. We evaluate models using metrics like KL-divergence or Jensen-Shannon Distance to see if the predicted probabilities align with the crowd. However, getting the numbers right doesn't mean the model understands the disagreement. A model might predict a 60/40 split for the wrong reasons, or hallucinate a conflict where none exists. As we move towards &quot;Glass-Box&quot; NLP, we need models that can explicitly justify why a sample is ambiguous through Explanations ([Chen et al. 2025a](https://aclanthology.org/2025.findings-acl.562/)) or Chain-of-Thought (CoT, [Chen et al. 2025b](https://aclanthology.org/2025.emnlp-main.1682/)).
While we have metrics for label distributions, we lack a robust framework for evaluating the quality of the reasoning behind the variation. How do we judge if a free-text explanation accurately captures a pragmatic ambiguity versus a semantic one? Does the generated CoT truly reflect the linguistic nuance that causes humans to disagree? This thesis aims to design an evaluation framework for Free-Form HLV Rationales. The student will move beyond standard overlaps (like BLEU/ROUGE) and develop metrics—potentially LLM-based or taxonomy-guided (e.g., using LITEX, [Hong et al. 2025a](https://aclanthology.org/2025.emnlp-main.1728/))—to assess: 1. Faithfulness: Does the explanation actually align with the predicted label distribution? 2. Coverage: Does the CoT capture all valid perspectives (the &quot;Yes&quot; view and the &quot;No&quot; view) or does it collapse into a single viewpoint? 3. Linguistic Validity: Can we quantify the &quot;quality&quot; of the ambiguity detection? 
**Level: MSc.**

- *Ambiguity or Preference? Disentangling Variation Sources via Personalized Modeling:* When humans disagree on an NLP task, it usually stems from two distinct sources ([Hong, 2025b](https://arxiv.org/abs/2510.16458)): Linguistic Ambiguity (the text itself is unclear/vague) or Annotator Preference (the human has specific biases, background knowledge, or subjectivity). Current HLV models tend to mix these into a single &quot;noise&quot; distribution. However, true Human-Centric NLU requires a model to know who is speaking. A sentence might be ambiguous to everyone (global uncertainty), or it might only be interpreted differently by people with specific cultural backgrounds (local preference). We currently struggle to separate &quot;what is in the text&quot; from &quot;what is in the head.&quot; Can we simulate specific human Personas to model preference? If we condition a model on a specific persona, does the variation disappear (implying the variation was preference-based) or persist (implying the variation is intrinsic ambiguity)?
This thesis explores Personalized HLV to disentangle ambiguity from preference. The student will investigate: 1. Persona Injection: Can we prompt LLMs with specific annotator profiles (e.g., &quot;skeptical linguist&quot; vs. &quot;imaginative writer&quot;) to replicate specific human biases? ([Sorensen et al. 2025](https://aclanthology.org/2025.emnlp-main.106/),[Li et al. 2025](https://arxiv.org/abs/2505.18071)) 2. Decomposition: By measuring how much the output distribution shifts when the persona changes, can we quantify the &quot;Subjectivity Score&quot; of a dataset? 3. Disentanglement: The goal is to propose a method that separates instances where clarification is needed (ambiguity) from instances where personalization is needed (preference). 
**Level: MSc.**

- *Aggregating Individual Opinions through Discourse:* Human vs. Chain-of-Thought Reasoning. Public discourse often consists of multiple, partially conflicting individual opinions that may be synthesized into a coherent collective interpretation. This thesis investigates how humans and language models differ in aggregating such opinions, with a particular focus on the role of discourse structure and reasoning strategies. These opinion pieces could come from different news agencies, Wikipedia articles, political debates, discussion forums, etc. The student will examine whether humans and LLMs preserve disagreement (e.g., minority viewpoints) and how they build argumentative structure. The study is well-suited for students interested in discourse analysis, evaluation of language models, and the representation of multiple voices.
**Level: MSc.**

- :hourglass_flowing_sand: *Synthetic data for metrics meta evaluation.* Automatic metrics (including LLMs-as-judges) are typically meta-evaluated by measuring their correlation with human scores or preferences. However, this evaluation is often global (making it difficult to diagnose when and why a metric fails), and human judgments are expensive and complex to collect. An alternative is behavioural testing, e.g., checklist-like approaches ([Ribeiro et al., ACL 2020](https://aclanthology.org/2020.acl-main.442/)), where targeted perturbations are designed to probe sensitivity to specific phenomena. This approach uses challenge sets to better understand metrics failure modes and test for specific biases. The goal of this project is to explore methods for automatically generating synthetic test sets for metric meta-evaluation, to assess their validity and limitations, and to use them to systematically benchmark evaluation metrics (including LLM-based judges). Depending on student interests, the project may focus on multilingual settings, specific evaluation dimensions (e.g., factuality or societal bias), robustness to perturbations, or other task- or domain-specific aspects. References include: [Sai et al., EMNLP 2021](https://aclanthology.org/2021.emnlp-main.575.pdf),  [Ye et al., ICLR 2025](https://iclr.cc/virtual/2025/poster/31088). 
**Level: BSc or MSc.**

- *Pseudoword generation.* Pseudowords are words that look and sound like they could exist in a particular language, but don’t actually have any meaning. Pseudowords are frequently used in (psycho)linguistic studies to investigate how humans learn and process language (e.g., [lexical decision](https://en.wikipedia.org/wiki/Lexical_decision_task)). Often, pseudowords need to fulfill certain criteria, e.g., they should appear like a specific part of speech. However, it is quite difficult to come up with good pseudowords manually. Previous approaches have often been based on phonotactic templates or Markov chains. Neural networks also have the potential to work well. A student project could involve implementing and evaluating a new pseudoword generator for a less-studied language. Depending on interest and available resources, the approach could be rule-based, or based on statistical or neural models.
**References:** [Keuleers & Brysbaert (2010)](https://doi.org/10.3758/BRM.42.3.627), [New et al. (2024)](https://doi.org/10.1177/17470218231164373)
**Level: BSc or MSc.**

- :hourglass_flowing_sand:  *Interpreting Irony in Multimodal Memes.* Internet memes are a widely used form of online communication ([Shifman, 2013](https://onlinelibrary.wiley.com/doi/full/10.1111/jcc4.12013)) and often express irony, where the literal meaning of the text or image differs from the intended message. This mismatch makes automatic meme understanding difficult, as multimodal large language models (MLLMs) may assign incorrect sentiment or intent labels when they rely on surface-level cues ([Fersini et al., 2022](https://aclanthology.org/2022.semeval-1.74/), [Nguyen et al., 2025](https://aclanthology.org/2025.acl-long.927/)). Previous research ([Ilic et al., 2018](https://aclanthology.org/W18-6202.pdf)) has studied irony and sarcasm in text and has addressed meme classification tasks ([Kiela et al., 2020](https://proceedings.nips.cc/paper_files/paper/2020/file/1b84c4cee2b8b3d823b30e2d604b1878-Paper.pdf), [Liu et al., 2022](https://aclanthology.org/2022.emnlp-main.476/)), but the specific ways in which irony arises from text, images, or their interaction are not yet fully understood. The goal of this thesis is to analyze how irony is constructed in multimodal memes and to evaluate how MLLMs detect and explain ironic meaning. Possible research directions include defining or refining a taxonomy of irony in memes, annotating or analyzing existing meme datasets, and assessing model performance in irony detection and explanation, including consistency between predicted labels and generated explanations as well as common error patterns. 
**Level: BSc**, adaptation to MSc possible.

- *Gaze data for NLP.* The way in which our eyes move when reading a text can tell us a lot about the cognitive processes required for language understanding. For example, longer reading times indicate higher processing difficulty. In the past 10 years, a line of research has emerged that attempts to use gaze data obtained by eye tracking to improve NLP models for various tasks (e.g., [Barrett et al., 2016](https://aclanthology.org/P16-2094/), [Hollenstein & Zhang, 2019](https://aclanthology.org/N19-1001/), [Deng et al., 2023](https://aclanthology.org/2023.emnlp-main.400/), [Alaçam et al., 2024](https://aclanthology.org/2024.emnlp-main.11/)). A student project could involve investigating under which circumstances and for which NLP tasks gaze data can be beneficial, or whether we can achieve the same effect with artificially synthesized gaze data. References: [Hollenstein et al. (2019)](https://arxiv.org/abs/1904.02682), [Sood et al. (2020)](https://proceedings.neurips.cc/paper/2020/hash/460191c72f67e90150a093b4585e7eb4-Abstract.html), [Khurana et al. (2023)](https://aclanthology.org/2023.eacl-main.139/), [Bolliger et al. (2023)](https://aclanthology.org/2023.emnlp-main.960/).
**Level: MSc.**

- *Tracking eye movements during annotation.* Data annotation in NLP often involves subjective judgements or depends on how the annotators understand a given text. Eye tracking can be used to measure which parts of a text people pay most attention to. We can use this information to try to explain why different annotators choose different labels for the same text, which can also inform NLP models. A student project could involve collecting eye-tracking data for an annotation task where humans are known to disagree sometimes, and/or using existing eye-tracking data to analyze and explain annotation behavior.
**References:** [Alaçam et al. (2024)](https://doi.org/10.18653/v1/2024.emnlp-main.11), [Joshi et al. (2014)](https://doi.org/10.3115/v1/p14-2007)
**Level: MSc**, BSc possible (using existing gaze data).

- *(Eye-)Tracking the processing of  visual representations of abstract concepts.* Visual representations of concrete concepts (e.g., banana) tend to be more consistent across images and interpretations than those of abstract concepts (e.g., joy), which show a lot of variability in both visual representations and semantic interpretations. This thesis investigates how humans process visual representations of abstract concepts using eye tracking techniques. By analyzing gaze patterns and attention distributions, this project aims to highlight various processing strategies associated with abstractness. **References:** [Tater et al. 2024](https://aclanthology.org/2024.emnlp-main.1203.pdf), [Tater et al. 2025](https://aclanthology.org/2025.emnlp-main.417/), [McRae et al. 2018](https://onlinelibrary.wiley.com/doi/full/10.1111/tops.12328)
**Level: MSc.**

<!--
### **Selected Research Projects**
- *Understanding Indirectness*. Indirectness involves for example indirect answers
to requests that do not explicitly contain answer clues like Yes, yeah or no. Example:
Q: Do you wanna crash on the couch? A: I gotta go home sometime. Indirect
answers are natural in human dialogue, but very difficult for a conversational AI
system. This thesis project revolves around creating technology that can better deal
with indirectness, for example by improving indirectness classifiers, creating novel
datasets or integration of context, for example by modeling longer dialogue context.
The exact project scope will be determined with the student. References: [Louis et al.,
2020](https://aclanthology.org/2020.emnlp-main.601/), [Damgaard et al., 2021](https://aclanthology.org/2021.codi-main.1/) and [Sanagavarapu et al., 2022](https://aclanthology.org/2022.naacl-main.345/), [Yusupujiang &
Ginzburg, 2023](https://aclanthology.org/2023.sigdial-1.30/), [Müller and Plank, 2024](https://aclanthology.org/2024.lrec-main.791/) **Level: MSc (preferred), BSc (possibly)**.

- *Improving Automatic Text Simplification through Elaboration and Personalization*.
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
-->
    " | markdownify }}
  </div>
</div>

<div class="accordion-section">
  <div class="accordion-header" onclick="toggleAccordion(this)">
    V4: Understanding Complex Model Behavior (LLMs/VLMs, Agents)
  </div>
  <div class="accordion-content">
    {{ "

### **Thesis projects**

- :hourglass_flowing_sand:  *Aggregation and Multi-Agent Systems.* Multi-Agent Systems (MAS) are ensembles of Language Models that solve tasks as a group. The performance of MAS improves with a higher diversity between agents and their individual solutions. However, to evaluate the performance, the models need to consent or their individual answers must be aggregated. This project offers multiple directions: either aiming at understanding the impact of aggregation on the group solution or analyzing the diversity of the individual solutions. Example projects: a) Comparing different aggregation methods and evaluating the faithfulness of LMs generating the final answer (for Master students: improving existing aggregation methods / comparing the impact on different multi-agent approaches); b) making non-aggregated solutions comprehensible for humans, e.g. through visualization, summarization, and/or formalization (for Master students: + evaluation of non-aggregated solutions / comparing different multi-agent approaches); c) other projects regarding MAS. References: [Du et al. (2024)](https://dl-acm-org.emedien.ub.uni-muenchen.de/doi/10.5555/3692070.3692537), [Casola et al. (2023)](https://aclanthology.org/2023.emnlp-main.212/), [Surowiecki (2005) (Introduction)](https://opac.ub.lmu.de/Record/3146851?sid=71261150).
**Level: BSc or MSc.**

- *Analyzing shortcut learning in VLMs across NLI and visual entailment:* Vision-language models (VLMs) achieve strong performance on many tasks, yet they can exhibit shortcut learning, where predictions rely on simple input patterns rather than on a full use of the available evidence. For LLMs, this behavior has been observed in NLI, which asks whether a hypothesis follows from a given premise. Prior work has shown that models can often solve NLI by relying mainly on cues in the hypothesis, without fully capturing the relationship between the premise and the hypothesis ([Poliak et al., 2018](https://aclanthology.org/S18-2023/), [Yuan et al., 2024](https://aclanthology.org/2024.emnlp-main.679/)). In visual entailment, the premise is an image rather than a text ([Xie et al., 2019](https://arxiv.org/abs/1901.06706), [Kayser et al., 2021](https://openaccess.thecvf.com/content/ICCV2021/papers/Kayser_E-ViL_A_Dataset_and_Benchmark_for_Natural_Language_Explanations_in_ICCV_2021_paper.pdf)). The goal of this project is to investigate whether similar shortcut behavior occurs in vision-language models when performing visual entailment, and to analyze which visual and textual information models rely on when making inferences. The scope can be adjusted for BSc or MSc, for example by varying the number of models, prompting strategies, or the depth and types of cues analyzed. 
**Level: BSc or MSc.**

- :hourglass_flowing_sand:  *Data Mining and LLM-as-a-Judge to better understand LLM behavior:* While the behavior of LLMs and their nuanced and complex output data is challenging to evaluate, data mining approaches can be leveraged to explain model behavior, to bring structure into evaluation and to gain new insights, e.g. on cultural biases or task failure [1]. In this thesis project, we want to take this approach further by evaluating the use of newly proposed data mining algorithms and/or the combination of LLM-as-a-Judge with data mining processes. The project offers the possibility to work on a technical evaluation of methods as well as develop and evaluate a new method. **References:** [1] [https://aclanthology.org/2025.acl-long.985/](https://aclanthology.org/2025.acl-long.985/)
**Level: MSc.**

- :hourglass_flowing_sand:  *Understanding Post-Training Effects Through Model Behavior Analysis and Interpretability:* Post-training has become an essential technique to adapt pretrained language models, e.g. to improve instruction following [1] or abilities for underrepresented languages [2], or to align model behavior with safety standards [3]. Correctly adapting models through post-training is, however, a complex and difficult process which can e.g. trigger broad misalignments and unexpected effects like safety failures [4]. To better control post-training, it is crucial to better understand how models change during the process.  
This thesis will study the effects of post-training through a dual lens. Through model behavior analysis tools like Spotlight [5], it will explore how a model changes with respect to non-performance metrics like gender [6] and cultural biases [7]. Using probing, logic lense or other interpretability techniques, it will then go one step further and also start explaining how these changes occur within the model. Depending on scope and resource availability, this thesis can either work with existing model (checkpoints) or post-train specific model aspects.
**References:**
[1] [Ouyang et al. (2022): Training language models to follow instructions with human feedback. arXiv 2203.02155.](https://arxiv.org/pdf/2203.02155)
[2] [Yu et al. (2026): AfriqueLLM: How Data Mixing and Model Architecture Impact Continued Pre-training for African Languages. arXiv 2601.06395.](https://arxiv.org/pdf/2601.06395)
[3] [Grattafiori et al. (2024): The Llama 3 Herd of Models. arXiv 2407.21783.](https://arxiv.org/pdf/2407.21783)
[4] [Betley et al. (2026): Training large language models on narrow tasks can lead to broad misalignment. Nature.](https://www.nature.com/articles/s41586-025-09937-5)
[5] [Hedderich et al. (2025): What’s the Difference? Supporting Users in Identifying the Effects of Prompt and Model Changes Through Token Patterns. Proceedings of ACL.](https://aclanthology.org/2025.acl-long.985.pdf)
[6] [De-Arteaga et al (2019): Bias in Bios: A Case Study of Semantic Representation Bias in High-Stakes Settings. Proceedings of the Conference on Fairness, Accountability and Transparency.](https://arxiv.org/pdf/1901.09451)
[7] [Zhao et al. (2025): MAKIEval: A Multilingual Automatic WiKidata-based Framework for Cultural Awareness Evaluation for LLMs. Findings of EMNLP.](https://aclanthology.org/2025.findings-emnlp.1256.pdf)
**Level: MSc.**

<!--    
Some general references for this section: References: [Plank, 2016](https://arxiv.org/abs/1608.07836), [Plank, 2022
EMNLP](https://arxiv.org/abs/2211.02570), [Yang et al., 2024](https://arxiv.org/abs/2405.02411)

### **Selected research projects**

-  _In-context learning from human preference disagreement_. Aggregating
  annotations via majority vote could lead to ignoring the opinions of minority groups.
  Learning from individual annotators shows a better result on classification tasks such
  as hate speech detection, emotion detection and natural language inference than
  from the majority vote (Davani et al., 2022). In this project, we want to investigate the
  potential of learning from individual annotators in an in-context learning setting.
  Furthermore, we want to go beyond the classification datasets towards the human
  preference datasets. How can the model learn from the disagreement in the
  preference data in context? References: [Davani et al., 2022](https://aclanthology.org/2022.tacl-1.6/), [Chen et al.,2024](https://arxiv.org/pdf/2406.17600),
  [Zhang et al., 2024](https://arxiv.org/abs/2410.14632). **Level: MSc**.
-  _Enhancing NLI Label Modeling with LLM-Generated Explanations: Annotation,
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
-  _Understanding disagreement in human-generated scores_. Large collections of
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
-  _Human-understandable descriptions of topic clusters_. Topic modelling is a core
  tool of fields like digital humanities and computational social sciences and recent
  developments like BERTTopic and SCA have made it possible to leverage word
  embeddings to find topics. These topic clusters are, however, difficult to analyse and
  additional tools like c-TF-IDF are necessary to make them human-understandable. In
  this thesis, we will implement and evaluate new techniques for describing topic
  clusters in a more robust and human-understandable way. References:
  [BERTTopic](https://maartengr.github.io/BERTopic/index.html), [SCA](https://arxiv.org/abs/2410.21054), [c-TF-IDF](https://maartengr.github.io/BERTopic/api/ctfidf.html). **Level: BSc**.
- _Controlling models through state space analysis and manipulation_. Recent
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
-  _Understanding prompt instability_. It has been shown that LLMs are very unstable
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
-  _Investigating Information Asymmetry on Wikipedia_. Information asymmetry (IA)
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
  --> 
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
