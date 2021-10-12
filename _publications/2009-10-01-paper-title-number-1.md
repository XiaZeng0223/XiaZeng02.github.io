---
authors: "Xia Zeng, Arkaitz Zubiaga"
title: "QMUL-SDS at SCIVER: Step-by-Step Binary Classification for Scientific Claim Verification"
collection: publications
permalink: https://aclanthology.org/2021.sdp-1.15
excerpt: 'In this paper, we propose an approach that performs scientific claim verification by doing binary classifications step-by-step.'
date: 2021-06-10
venue: 'Proceedings of the Second Workshop on Scholarly Document Processing'
paperurl: 'https://aclanthology.org/2021.sdp-1.15.pdf'
citation: @inproceedings{zeng-zubiaga-2021-qmul,
    title = "{QMUL}-{SDS} at {SCIVER}: Step-by-Step Binary Classification for Scientific Claim Verification",
    author = "Zeng, Xia  and
      Zubiaga, Arkaitz",
    booktitle = "Proceedings of the Second Workshop on Scholarly Document Processing",
    month = jun,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.sdp-1.15",
    doi = "10.18653/v1/2021.sdp-1.15",
    pages = "116--123",
    abstract = "Scientific claim verification is a unique challenge that is attracting increasing interest. The SCIVER shared task offers a benchmark scenario to test and compare claim verification approaches by participating teams and consists in three steps: relevant abstract selection, rationale selection and label prediction. In this paper, we present team QMUL-SDS{'}s participation in the shared task. We propose an approach that performs scientific claim verification by doing binary classifications step-by-step. We trained a BioBERT-large classifier to select abstracts based on pairwise relevance assessments for each {\textless}claim, title of the abstract{\textgreater} and continued to train it to select rationales out of each retrieved abstract based on {\textless}claim, sentence{\textgreater}. We then propose a two-step setting for label prediction, i.e. first predicting {``}NOT{\_}ENOUGH{\_}INFO{''} or {``}ENOUGH{\_}INFO{''}, then label those marked as {``}ENOUGH{\_}INFO{''} as either {``}SUPPORT{''} or {``}CONTRADICT{''}. Compared to the baseline system, we achieve substantial improvements on the dev set. As a result, our team is the No. 4 team on the leaderboard.",
}
---
