---
layout: page
title: BabyLM
description: Training sample efficient language models on developmentally plausible corpora
img: assets/img/data_scale.png
importance: 1
category: work
related_publications: true
---

Humans are remarkably efficient language learners compared to language models. 
It would take a human a million years to accumulate as much linguistic input as most popular large language models, 
yet we learn language in just a few years. 
[BabyLM](babylm.github.io) is a competition and workshop devoted to data-efficient language learning. 
How do humans acquire language from so little input? How can we build more data-efficient language models? 
How do we design language models to be better cognitive models?
The competition's goal is to challenge the community to answers these questions.
We also aim to democratize research into LM pretraining, which has recently become increasingly concentrated
in a few large industry groups.
While a small academic group will not build the next ChatGPT, there are still valuable research questions
about pretraining that we can address with a small budget.

In 2023, I co-founded and co-organized the BabyLM Challenge with a group of amazing collaborators, now including:
- Leshem Choshen (IBM Research, MIT)
- Ryan Cotterell (ETH Zurich)
- Michael Hu (NYU)
- Tal Linzen (NYU)
- Aaron Mueller (Northeastern)
- Candace Ross (Meta AI)
- Alex Warstadt (ETH Zurich, UCSD)
- Ethan Wilcox (ETH Zurich, Georgetown)
- Adina Williams (Meta AI)
- Chengxu Zhuang (MIT)

The competition was the shared task for [CoNLL 2023](https://www.conll.org/2023), 
and we had 31 talks and posters presented at CoNLL in Singapore!
Prior to organizing the challenge, I worked on training and evaluating data-limited language models
{% cite warstadt2020learning %} {% cite zhang2021when %}, 
and I published a position piece arguing for the value of data-limited models to cognitive science {% cite warstadt2022what %}.
We published our proceedings {% cite warstadt2023babylm %}, 
and we summarized the findings of all the submissions in a review article {% cite warstadt2023findings %}.
I also contributed to submissions trying to incorporate visual input {% cite amariucai2023acquiring %}
and auditory input {% cite wolf2023whisbert %} into the training of LMs.
More recently, some of the organizers have published a position piece 
arguing for the value of small language models {% cite wilcox2024bigger %}.
The 2024 BabyLM Challenge saw the addition of a Multimodal Track.
It will be collocated with CoNLL in Miami.
