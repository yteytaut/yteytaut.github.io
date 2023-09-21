---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Link to my personal [Google scholar page](https://scholar.google.com/citations?hl=fr&authuser=2&user=NfT1P1kAAAAJ)   

# 2024

# 2023

**Teytaut, Y.**, Petit, A., Chabot-Canet C. and Roebel, A. [*A musicological pipeline for singing voice style analysis with neural voice processing and alignment*](https://jim2023.sciencesconf.org/data/pages/7_1_TEYTAUT_ET_AL.pdf), Journées d'Informatique Musicale (JIM) 2023, Saint-Denis, France, 2023

*Abstract*:
The study of singing style is of great interest both for expressive vocal synthesis and for the musicological analysis of vocal performances, inciting to a fruitful convergence between signal processing and musicology. However, for musicologists, these studies often come up against the absence of automatic analysis tools for voices recorded in a musical context, leading to long and tedious manual annotation work. This constraint imposes either to limit oneself to a restricted corpus, or to circumscribe one’s study to experimental corpora of voices without instrumental accompaniment, thus depriving oneself of the unequalled interest that commercial recordings represent, as accomplished artistic works. This article introduces a new protocol using deep learning techniques to provide musicologists with powerful tools for the analysis of singing voices, opening up new perspectives through the automation of the different steps. We present a complete processing chain in support of musicological analysis, using neural models to isolate singing voice, predict its F0, and automatically align the syllables or notes to the audio (despite the musical accompaniment). The effectiveness of this approach is demonstrated by its practical application on two popular songs. These tools, developed in an ANR project, will soon be available to the scientific community.


Doras, G., **Teytaut, Y.** and Roebel, A. [*A Linear Memory CTC-Based Algorithm for Text-to-Voice Alignment of Very Long Audio Recordings*](https://www.mdpi.com/2076-3417/13/3/1854), Applied Sciences 13.3 (2023): 1854.

*Abstract*:
Synchronisation of a voice recording with the corresponding text is a common task in speech and music processing, and is used in many practical applications (automatic subtitling, audio indexing, etc.). A common approach derives a mid-level feature from the audio and finds its alignment to the text by means of maximizing a similarity measure via Dynamic Time Warping (DTW). Recently, a Connectionist Temporal Classification (CTC) approach was proposed that directly emits character probabilities and uses those to find the optimal text-to-voice alignment. While this method yields promising results, the memory complexity of the optimal alignment search remains quadratic in input lengths, limiting its application to relatively short recordings. In this work, we describe how recent improvements brought to the textbook DTW algorithm can be adapted to the CTC context to achieve linear memory complexity. We then detail our overall solution and demonstrate that it can align text to several hours of audio with a mean alignment error of 50 ms for speech, and 120 ms for singing voice, which corresponds to a median alignment error that is below 50 ms for both voice types. Finally, we evaluate its robustness to transcription errors and different languages.

# 2022

# 2021

**Teytaut, Y.** and Roebel, A., [*Phoneme-to-audio alignment with recurrent neural networks for speaking and singing voice*](https://www.isca-speech.org/archive/pdfs/interspeech_2021/teytaut21_interspeech.pdf), Proc. Interspeech 2021, 61-65, [doi: 10.21437/Interspeech.2021-1676](https://www.isca-speech.org/archive/interspeech_2021/teytaut21_interspeech.html) (2021).

*Abstract*:
Phoneme-to-audio alignment is the task of synchronizing voice recordings and their related phonetic transcripts. In this work, we introduce a new system to forced phonetic alignment with Recurrent Neural Networks (RNN). With the Connectionist Temporal Classification (CTC) loss as training objective, and an additional reconstruction cost, we learn to infer relevant per-frame phoneme probabilities from which alignment is derived. The core of the neural architecture is a context-aware attention mechanism between mel-spectrograms and side information. We investigate two contexts given by either phoneme sequences (model PhAtt) or spectrograms themselves (model SpAtt). Evaluations show that these models produce precise alignments for both speaking and singing voice. Best results are obtained with the model PhAtt, which outperforms baseline reference with an average imprecision of 16.3ms and 29.8ms on speech and singing, respectively. The model SpAtt also appears as an interesting alternative, capable of aligning longer audio files without requiring phoneme sequences on small audio segments.

