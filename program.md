---
layout: default
---
<!-- # Program of the First Workshop on Uncertainty-Aware NLP @EACL 2024 -->
<!-- / [HOME](/) / [CALL FOR PAPERS](/#call-for-papers) / [ACCEPTED PAPERS](/accepted-papers) / [PROGRAM COMMITTEE](https://uncertainlp.github.io/#program-committee) / PROGRAM / [CONTACT](https://uncertainlp.github.io/#contact) / -->

The workshop will take place March 22, 2024 at the Bastion 2 room of the <a href="https://maps.app.goo.gl/Mq8zQciGEe6wnnDZ8">Corinthia St George's Bay hotel</a>. Here is the detailed program of the workshop.

### Workshop Schedule 


- 09:00 - 09:10: **Opening remarks**
- 09:10 - 09:55: **Invited Talk - Chrysoula Zerva**: [*Uncertainty in NLP: Quantification, interpretation and evaluation*.](/slides/UncertaiNLP-Chrysoula-Zerva.pdf)
  - **Abstract**: As the availability (and size) of language models keeps increasing, so do their applications to different tasks, rendering them ubiquitous in modern society. This in turn, brings forward the question of reliability. We know models don’t always know what they don’t knowand hence being able to quantify the uncertainty over their predictions is a key step in the path towards reliability. But how can we estimate uncertainty when we have multiple sources of it, and frequently no or limited access to the parameters of the models? And how do we know if we can trust our uncertainty estimations? In this talk I will discuss uncertainty quantification in NLP, emphasising its interpretation and evaluation. I will focus on generation and evaluation tasks, using machine translation as the main paradigm.
- 09:55 - 10:15: **Presentation Session 1**
  - [*Aligning Uncertainty: Leveraging LLMs to Analyze Uncertainty Transfer in Text Summarization*](/slides/UncertaiNLP-Zahra-Kolagar.pdf), Zahra Kolagar and Alessandra Zarcone
- 10:15 - 10:30: **Lightening paper presentations**
  - [*Context Tuning for Retrieval Augmented Generation*](/slides/UncertaiNLP-Raviteja-Anantha.pdf), Raviteja Anantha and Danil Vodianik
  - [*Linguistic Obfuscation Attacks and Large Language Model Uncertainty*](/slides/UncertaiNLP-Sebastian-Steindl.pdf), Sebastian Steindl, Ulrich Schäfer, Bernd Ludwig and Patrick Levi
  - [*Order Effects in Annotation Tasks: Further Evidence of Annotation Sensitivity*](/slides/UncertaiNLP-Jacob-Beck.pdf), Jacob Beck, Stephanie Eckman, Bolei Ma, Rob Chew and Frauke Kreuter
  - [*The Effect of Generalisation on the Inadequacy of the Mode*](/slides/UncertaiNLP-Bryan-Eikema.pdf), Bryan Eikema
  - *Uncertainty Resolution in Misinformation Detection*, Yury Orlovskiy, Camille Thibault, Anne Imouza, Jean-Francois Godbout, Reihaneh Rabbany and Kellin Pelrine
  - [*Combining Confidence Elicitation and Sample-based Methods for Uncertainty Quantification in Misinformation Mitigation*](/slides/UncertaiNLP-Mauricio-Rivera.pdf), Mauricio Rivera, Jean-Francois Godbout, Reihaneh Rabbany and Kellin Pelrine
  - [*Linguistically Communicating Uncertainty in Patient-Facing Risk Prediction Models*](/slides/UncertaiNLP-Adarsa-Sivaprasad.pdf), Adarsa Sivaprasad and Ehud Reiter

- 10:30 - 11:00: **Coffee Break**
- 11:00 - 12:15: **In-person poster session** (Corinthia St George's Bay, Terrace Suite)
- 12:15 - 13:15: **Lunch break**
- 13:15 - 14:00: **Invited Talk - Elias Stengel-Eskin** [*Confidence-based Rephrasing, Refinement, and Selection*](/slides/UncertaiNLP-Elias-Stengel-Eskin.pdf).
  - **Abstract**: Many kinds of NLP systems and tasks can benefit from calibrated confidence scores -- this talk will showcase several ways in which we can use confidence to improve performance across a variety of settings. After making the case for calibration in one such setting (semantic parsing) and documenting the calibration of existing models, I will present results on using calibrated confidence scores to trigger human interactions, improving the balance between a system's safety and usability. Specifically, I will discuss DidYouMean, a method for rephrasing and answering difficult parsing queries. Moving to a visually-grounded setting, I will then present RepARe, our recent work in which we use confidence to select rephrased and augmented questions for VQA. Finally, I will share a pair of recent papers in which confidence shapes discussions between multiple LLM agents, touching on our group's prior work on annotator disagreement and diverse answers.  
- 14:00 - 15:30: **Presentation Session 2**
  - [*Optimizing Relation Extraction in Medical Texts through Active Learning: A Comparative Analysis of Trade-offs*](/slides/UncertaiNLP-Siting-Liang.pdf), Siting Liang, Pablo Valdunciel Sánchez and Daniel Sonntag
  - [*Efficiently Acquiring Human Feedback with Bayesian Deep Learning*](/slides/UncertaiNLP-Edwin-Simpson.pdf), Haishuo Fang, Jeet Gor and Edwin Simpson
  - [*Don’t Blame the Data, Blame the Model: Understanding Noise and Bias When Learning from Subjective Annotations*](/slides/UncertaiNLP-Abhishek-Anand.pdf), Abhishek Anand, Negar Mokhberian, Prathyusha Naresh Kumar, Anweasha Saha, Zihao He, Ashwin Rao, Fred Morstatter and Kristina Lerman
  - [*Teaching Probabilistic Logical Reasoning to Transformers*](/slides/UncertaiNLP-Aliakbar-Nafar.pdf), Aliakbar Nafar, K. Brent Venable and Parisa Kordjamshidi
  - *Calibration-Tuning: Teaching Large Language Models to Know What They Don’t Know*, Sanyam Kapoor, Nate Gruver, Manley Roberts, Arka Pal, Samuel Dooley, Micah Goldblum and Andrew Gordon Wilson
- 15:30 - 16:00: Coffee Break
- 16:00 - 16:30: **Presentation Session 3**
  - [*How Does Beam Search improve Span-Level Confidence Estimation in Generati- ve Sequence Labeling?*](/slides/UncertaiNLP-Kazuma-Hashimoto.pdf) Kazuma Hashimoto, Iftekhar Naim and Karthik Raman
  - *Consistent Joint Decision-Making with Heterogeneous Learning Models*, Hossein Rajaby Faghihi and Parisa Kordjamshidi
- 16:30 - 17:15: **Invited talk - Kristin Lennox** (and DALL-E 3) *Mathemagic! The non-mystical nature of mathematics and what it means for you*.
  - **Abstract**: Mathematical modeling of real-world phenomena is both ubiquitous in modern times and a tradition with millennia of history. This talk provides a (very) brief overview of mathematical history, beginning with the philosophy of Pythagoras through the mathematical crises of the 19th century that ultimately led to the modern division between “pure” and “applied” mathematics. Through this historical lens, we consider why mathematical modeling of uncertainty is uniquely challenging and also how these challenges have been addressed in the field of statistics. To conclude, we will provide some suggestions from statistical practice that are also likely to be relevant to the development of uncertainty methods and metrics for natural language.
- 17:15 - 17:30: **Closing remarks**

