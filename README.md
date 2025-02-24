# <i>Mind the Gesture.</i> Evaluating AI Sensitivity to Culturally Offensive Non-Verbal Gestures

This repository contains the <b>MC-SIGNS</b> dataset for the paper "[Mind the Gesture. Evaluating AI Sensitivity to Culturally Offensive Non-Verbal Gestures]()". This dataset contains the cultural interpretations of 25 common emblematic gestures that may be considered offensive across different cultures.


# Abstract
Gestures are an integral part of non-verbal communication, with meanings that vary across cultures, and misinterpretations that can have serious social and diplomatic consequences. 
As AI systems become more integrated into global applications, ensuring they do not inadvertently perpetuate cultural offenses is critical. To this end, we introduce Multi-Cultural Set of Inappropriate Gestures and Nonverbal Signs (<b>MC-SIGNS</b>), a dataset of 288 gesture-country pairs annotated for offensiveness, cultural significance, and contextual factors across 25 gestures and 85 countries. Through systematic evaluation using MC-SIGNS, we uncover critical limitations: text-to-image (T2I) systems exhibit strong US-centric biases,  performing better at detecting offensive gestures in US contexts than in non-US ones; large language models (LLMs) tend to over-flag gestures as offensive; and vision-language models (VLMs) default to US-based interpretations when responding to universal concepts like wishing someone luck, frequently suggesting culturally inappropriate gestures. These findings highlight the urgent need for culturally-aware AI safety mechanisms to ensure equitable global deployment of AI technologies. 

![MC-SIGNS](assets/intro.png)

# Data
The <code>dataset</code> folder contains the curated <b>MC-SIGNS</b> dataset (<code>MC-SIGNS.csv</code>). Detailed information on each gesture is available in <code>gesture_details.csv</code>. Corresponding gesture images are stored in <code>dataset/image-files</code>. 

# License
Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg