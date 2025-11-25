---
title: "Compgen: Synthesis and Generation of Faces From Edgemaps"
collection: publications
category: manuscripts
permalink: /publication/paper_1
excerpt: ''
date: 2025-04-06
venue: ''
slidesurl: ''
paperurl: ''
bibtexurl: 'https://Ruban-VP.github.io/files/paper_1_bibtex.bib'
citation: ''
---
**Abstract:**
In this paper, we address the problem of synthesis and generation of faces from edgemaps, motivated by extreme low bit-rate facial compression and the need for robust source-channel coding over noisy channels. Three approaches for image reconstruction are proposed. In the first, a deep learning-based encoder-decoder creates a latent space representation of the original image. 

An Edgemap-to-Latent Mapper (ELM) network maps the input edgemap to this latent space, with the final image reconstructed using a pre-trained compressive decoder. The second approach retrains the compressive decoder to reconstruct images from the ELM network’s output. The third approach jointly trains the ELM network and decoder, enabling direct reconstruction from the edgemap. This end-to-end framework achieves reasonable reconstruction fidelity. 

We also examine the impact of additive channel noise on edgemap transmission under low SNR conditions, demonstrating that even with significant noise, a DNN-based joint denoiser and edgemap decoder can reconstruct images. At extremely low SNRs, where edgemaps are highly corrupted, the network also exhibits generative capabilities, producing plausible images.
