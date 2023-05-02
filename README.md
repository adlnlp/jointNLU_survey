## A tutorial based on our survey paper

Where is Natural Language Understanding in 2023?

Presented at:
<p><a href="https://www2023.thewebconf.org/" title="ACM's The Web Conference 2023, Austin TX">ACM's The Web Conference 2023 (WWW 2023'), Austin TX</a></p>


# The tutorial

When a human speaks to a machine how does the latter elicit meaning from the communication? This is an important AI task as it enables the machine to construct a sensible answer or perform a useful action for the human. Meaning is represented at the sentence level, identification of which is known as intent detection, and at the word level, a labelling task called slot filling. This dual level joint task requires innovative thinking about natural language and deep learning network design and as a result many approaches have been tried. 

In this tutorial we will discuss how the joint task is set up and introduce some NLP and Deep Learning basics. We will cover the datasets, experiments and metrics used in the field. We will describe how the machine uses the latest NLP and Deep Learning techniques to address the task, including recurrent and non-recurrent (attention based Transformer) networks and pre-trained models (e.g. BERT). We will then look in detail at a network that allows the two levels of the task to explicitly interact to boost performance. We will do a code walk through of a Python notebook for this model and attendees will have an opportunity to do some light coding tasks on this model to further their understanding.

Watch our tutorial teaser video here:
<p><a href="https://www.youtube.com/watch?v=ovw7093ogeI" title="WWW (The Web Conference) '23 NLU Tutorial">WWW (The Web Conference) '23 NLU Tutorial</a></p>

Please find the tutorial slides available in the file "NLU WWW 2023 Tutorial.pdf" in this repository.

# The paper 

In 2022 we published a survey paper in the journal ACM Computing Surveys upon which the tutorial is based. 

The paper can be found here:
<p><a href="https://doi.acm.org?doi=3547138" title="A Survey of Joint Intent Detection and Slot Filling Models in Natural Language Understanding">A Survey of Joint Intent Detection and Slot Filling Models in Natural Language Understanding</a></p>

# Citation

```
@article{10.1145/3547138,
          author = {Weld, Henry and Huang, Xiaoqi and Long, Siqu and Poon, Josiah and Han, Soyeon Caren},
          title = {A Survey of Joint Intent Detection and Slot Filling Models in Natural Language Understanding},
          year = {2022},
          issue_date = {August 2023},
          publisher = {Association for Computing Machinery},
          address = {New York, NY, USA},
          volume = {55},
          number = {8},
          issn = {0360-0300},
          url = {https://doi.org/10.1145/3547138},
          doi = {10.1145/3547138},
          abstract = {Intent classification, to identify the speaker’s intention, and slot filling, to label each token with a semantic type, are critical                         tasks in natural language understanding. Traditionally the two tasks have been addressed independently. More recently joint models that                       address the two tasks together have achieved state-of-the-art performance for each task and have shown there exists a strong                                 relationship between the two. In this survey, we bring the coverage of methods up to 2021 including the many applications of deep                             learning in the field. As well as a technological survey, we look at issues addressed in the joint task and the approaches designed to                       address these issues. We cover datasets, evaluation metrics, and experiment design and supply a summary of reported performance on the                       standard datasets.},
          journal = {ACM Computing Surveys},
          month = {dec},
          articleno = {156},
          numpages = {38},
          keywords = {slot labelling, natural language understanding, Intent detection}
}
```

<B>NLP basics</B> 
Tokenisation, word embeddings, sentence embeddings, pre-trained models, BERT

<B>Deep learning basics</B>  
RNN, transformer

<B>Tasks</B> 
<B>Semantic frame</B> 
<B>Intent detection</B>  - classification
<B>Slot filling</B>  - tokenisation, IOB tagging, sequence tagging

<B>Datasets</B> 
ATIS, SNIPS, others

<B>Metrics</B> 
Accuracy, precision, recall, f1, span based f1

<B>Joint models</B> 
RNN, capsule, memory networks, bi-directinal

<B>Bi-ED model</B> 
Overview, code walkthrough, some tasks for them to do


# Github links

Slot-Gated Modeling for Joint Slot Filling and Intent Prediction (2018) by Goo et al.
https://github.com/MiuLab/SlotGated-SLU

A Self-Attentive Model with Gate Mechanism for Spoken Language Understanding (2018) by Li et al.
https://github.com/NinedayWang/Self-Attentive-and-Gated-SLU

A Bi-model based RNN Semantic Frame Parsing Model for Intent Detection and Slot Filling (2018) by Wang et al.
https://github.com/ray075hl/Bi-Model-Intent-And-Slot

A Stack-Propagation Framework with Token-Level Intent Detection for Spoken Language Understanding (2019) by Qin et al.
https://github.com/LeePleased/StackPropagation-SLU

BERT for Joint Intent Classification and Slot Filling (2019) by Chen et al.
https://github.com/monologg/JointBERT
