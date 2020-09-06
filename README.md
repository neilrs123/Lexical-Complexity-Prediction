# Lexical-Complexity-Prediction
Course Project for CS779: Statistical Natural Language Processing

Working on  SemEval 2021 (Task 1): [LCP Shared Task 2021](https://sites.google.com/view/lcpsharedtask2021)

Lexical complexity plays a crucial role in reading comprehension. Predicting lexical complexity accurately can enable a system to better guide a user to an appropriate text, or tailor a text to their needs. NLP systems have been developed to simplify texts for second language learners, native speakers with low literacy levels, and people with reading disabilities. 

The dataset provided is an augmented version of CompLex, a multi-domain English dataset with sentences annotated using a 5-point Likert scale (1-5) described in [Shardlow et al. (2020)](https://arxiv.org/pdf/2003.07008.pdf). The task is to predict the complexity value of words in context. 

Likert Scale:
The complexity scores (1-5) in LCP 2021 correspond to the following:
1. Very Easy: Very familiar words: mapped to 0
2. Easy: An annotator was aware of the meaning: mapped to 0.25
3. Neutral: Neither difficult nor easy: mapped to 0.5
4. Difficult: Words for which an annotator was unclear of the meaning, but may have been able to infer the meaning from the sentence: mapped to 0.75
5. Very Difficult: Words that an annotator had never seen before, or were very unclear: mapped to 1

LCP 2021 has the 2 sub-tasks:
1. Sub-task 1: predicting the complexity score of single words
2. Sub-task 2: predicting the complexity score of multi-word expressions
