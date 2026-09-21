# It Never Hurts to Ask: Evaluating LLMs for Ontology Metadata Enrichment
Data, resources, and code for the automatic introduction of metadata by LLMs.

## Abstract 
<p style="text-align: justify;">
Ontologies provide a formal semantic representation of real-world entities and their relationships.
The quality of an ontology is not only assessed by its adoption in specific applications or as a support for a Machine Learning problem, but also by its capability of being shared, reused, and understood. These aspects of the ontologies are captured by several metrics that evaluate aspects such as FAIRness. A key role for this score is played by the metadata; i.e., data supporting the sharing, traceability, understandability, and interoperability of the introduced concepts. This metadata, although represented formally in OWL-like ontologies, does not participate in reasoning; hence, they neither introduce reasoning axioms nor raise inconsistencies. This is likely one of the reasons why the quality of these data is sometimes neglected or underestimated. In addition, the task of adding, reviewing, and understanding metadata are hard to automate, time-consuming, and require experts in the domains.

Recent research on LLMs and ontology construction led to some preliminary methodologies and evaluations on various tasks like competency questions generation and evaluation, ontology reuse, formalisation, and evaluation, but still lacks metadata management. In this paper, we propose a lightweight assessment of LLMs for metadata enrichment (or generation). The objective is twofold: (i) to understand current limitations and possibilities of LLMs to support this task, and (ii) to understand how the size of the prompt affects the quality of the result.

The idea is to increase the context by adding new axioms and capturing the variation of performance. The results suggest that heavily summarising the ontology leads to better results and that, evidently, the chosen axioms facilitate the comprehension of the context for this task. 
</p>

## Content

The repository comprises the following resources:
- [original](original) folder containing the original ontology sources;
- [pitfalls](pitfalls) folder containing the OOPS! pitfalls for every ontology;
- [reduced](reduced) containing the reduced versions of the ontologies;
- [resources](res) containing the result of the model predictions per ontology and model,
- [src](src) containing the necessary Python scripts to perform the analysis and visualise the results.

## Publications
- Davide Di Pierro, Danaï Symeonidou, and Lylia Abrouk: _It Never Hurts to Ask: Evaluating LLMs for Ontology Metadata Enrichment._  4th Workshop on Evaluation of Language Models in Knowledge Engineering @ ISWC 2026.

## Authored by:
Davide Di Pierro davide.di-pierro@umontpellier.fr <br/>
Danaï Symeonidou danai.symeonidou@inrae.fr <br/>
Lylia Abrouk lylia.abrouk@lirmm.fr <br/>
