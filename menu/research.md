---
layout: page
title: Research
permalink: /research
---

My research experiences have primarily focused on exploring the applications of statistical modeling to address problems in a variety of different fields.


### Gibbs Sampling for LDA and Applications to RAG (Undergraduate Thesis)

Latent Dirichlet Allocation (LDA) is one of the most popular topic-modeling algorithms in use today. In this work, I describe a method for deriving the posterior distribution used in LDA and create a hybrid model in which I combine LDA with a baseline retrieval-augmented generation (RAG) model. I find that this hybrid model outperforms the baseline RAG model in several areas including accuracy and processing time. These results highlight the potential for LDA to be incorporated in modern RAG-based models as a means of extending their performance from closed-book question answering (QA) tasks to open-domain QA tasks.

[Thesis](https://kyledtorres.github.io/pdf/Thesis.pdf), [PDF](https://kyledtorres.github.io/pdf/Final Thesis Presentation.pdf)


### AI for Justice

During the Computational and Applied Mathematics REU at UCLA, I collaborated with Mathematics Professor Deanna Needell, my peers, and the Innocence Center on a project titled "AI for Justice," aimed at developing a model to predict wrongful convictions. Our analysis incorporated topic-modeling algorithms, specifically non-negative matrix factorization (NMF) and its variations. Beyond processing the full corpus of text, we utilized ChatGPT to generate concise case summaries and analyzed the resulting vector embeddings for additional insights. To enhance classification performance, we implemented semi-supervised NMF, integrating label information within the NMF framework. I conducted the analysis using Python.


### Effect of ECMO Duration on Post-Transplant Survival

Through the USC Biostatistics and Data Science Summer Training Program, I collaborated with Biostatistics faculty and peers to analyze whether patients' time spent on ECMO (a life-support device) before heart transplant impacted post-transplant outcomes, applying models such as Cox regression and multinomial logistic regression in R.

[PDF](https://kyledtorres.github.io/pdf/Thesis.pdf)


### Analyzing Missing Data in the Stanford Open Policing Project

As part of the Summer Undergraduate Research Program (SURP) at Pomona College, I worked with a peer under the guidance of Statistics Professor Jo Hardin to research ways to characterize missing racial data in the Stanford Open Policing Project. In total, we utilized 23 municipal and state-wide datasets in our analysis. We used odds ratios as a metric to inform potential imputations for the missing racial data and created supplemental plots in R to reveal trends in the data. By the end of our research, we identified a range of possible odds ratios for each state/municipality and demonstrated the extent to which missing data could have impacted/biased the datasets as they were provided.
