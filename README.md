# FinalReport-48479373
Author: Damaranath Kookula

Differentially Private Masked Language Model (DP-MLM) — Replication Project

This repository documents the replication of the Differentially Private Masked Language Model (DP-MLM) proposed by Beigi, Wang & Liu.
The project explores how differential privacy can be integrated into language models without compromising linguistic quality or meaning.

Overview

The DP-MLM introduces a privacy-budget parameter ($\epsilon$) that controls the balance between data privacy and text utility.
This replication focused on:

Reproducing the original rewriting mechanism on the AG News dataset,

Evaluating the privacy–utility trade-off for $\epsilon = 4, 8, 16$, and

Performing demonstration runs on small samples from IMDB Reviews and BBC-style News to test cross-domain behaviour.

(Note: these extra datasets were used only for demonstration and qualitative inspection; they were not saved as full derived datasets.)

Key Findings

The replication successfully reproduced the privacy–utility curve described in the original paper.At moderate privacy levels ($\epsilon = 8$), rewritten texts retained structure and meaning while achieving anonymization.

Quantitative metrics (BLEU, ROUGE-L, TF-IDF) confirmed that stronger privacy slightly reduced lexical overlap but maintained coherence.

Reflection

This project highlighted both the technical challenges of reproducing older open-source code with updated dependencies and the conceptual balance between privacy and linguistic fidelity.
It demonstrates that differentially private language models can preserve readability and meaning even under strong privacy settings, reinforcing their potential for secure NLP applications.

### NOTE: I didn't actual dataset files since they are too big and exceeding the 25mb storage limit but repository contains all output saved file, ADSCode.ipynb file contains Main code.


