# Quora Question Pair Similarity
## Problem Statement
Quora is a platform to ask questions and connect with people who contribute unique insights and quality answers. A key challenge is to pair each question with a similar question that has already been answered. This ensures that an answer to a question that has already been answered receives maximum value. This could be useful to instantly provide answers to new questions that are repeats of older questions or highlight the questions that might be answered in the future.
## Data Overview
- Data can be dowanloaded from http://qim.fs.quoracdn.net/quora_duplicate_questions.tsv
- Data has five columns : qid1, qid2, question1, question2, is_duplicate

## Models Used
- A GRU based model with Attention Mechanism on tokens(Achieves 81% accuracy).
- A GRU based model on characters.
- A GRU based model on tokens and characters.
