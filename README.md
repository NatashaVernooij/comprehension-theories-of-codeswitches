# Evaluating Prediction-Based Theories of Bilingual Comprehension of Spanish/English Codeswitches 
Ch.s 3-5 of disseration
Associatied OSF: https://osf.io/3z4qw/

This repository contains the materials, data, and analysis script associated with 2 human-participants experiments that evaluated bilinguals' comprehension of Spanish-English codeswitches (Chapters 3 & 4), and the data of LLM processing (surprisal) of those same codeswitches. Mathematical models of 3 different theories of bilingual codeswitch comprehension were evaluated, and model performance was used to assess which theory best explains the human behavioral data.


## Contents
Study Materials: folder contains stimuli and task instructions with examples. Stimuli for humans and LLM were the same.

Data: folder contains the processed data- human only (Chapters 3-4), LLM only, and combined data (Chapter 5).
- files beginning with "Ch5": combined human and LLM (surpirsal) data for the different sets of stimuli
- adj_n_freq.csv: contians the frequency per million for the adjectives and nouns in the stimuli. Used for post-hoc analysis.

## Study Information
Overview: 
In this body of work, we tested 3 different theories of bilingual language comprehension: the Current Word Hypothesis, the Matrix Language hypothesis, and the Surprisal Codeswitching Hypothesis. 
Participants completed a Stop-Making-Sense task where they read sentences on a computer one word at time. At each word, they decided if the sentence still made sense or not. If the sentence made sense, they pressed a button to continue the sentence and see the next word. If the sentence did not make senese, they pressed a different button to end the sentence. In the experiment in Chapter 3, participants read sentences where two theories made the same predictions for human language comprehension. As such, this experiment served to validate the task on these stimuli. In the experiment in Chapter 4, participants read sentences where two theories made oppositive predictions for human language comprehension and we were able to test the two theories against each other. In Chapter 5, we used surprisal caluculated by GPT3 to operationalize a final theory of language comprehension, and were able to test all three theories of language comprehension against each other. 
