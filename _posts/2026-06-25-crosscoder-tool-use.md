---
layout: paper
category: paper
title: "Localizing RL-Induced Tool Use to a Single Crosscoder Feature"
authors: "Andrii Shportko, Shubham Bhokare, Ahmed Zeyad A Alzahrani, Bowen Cheng, Gustavo Mercier, Jessica Hullman"
venue: "Mechanistic Interpretability Workshop at ICML 2026 (Spotlight)"
thumb: "assets/images/paper-thumb-crosscoder-tool-use.png"
banner: "assets/images/paper-banner-crosscoder-tool-use.png"
caption: "Decoder UMAP: the Dedicated Feature Crosscoder (left) yields three spatially distinct regions&mdash;A-exclusive, B-exclusive, and shared&mdash;while the CrossCoder (right) mixes A-biased and B-biased features uniformly with shared features."
pdf: "https://arxiv.org/abs/2606.26474"
---

<!-- abstract -->

Fine-tuning through RL reshapes the internal representations of language models to enable agentic behaviors such as tool use, yet the mechanistic basis of these changes remains poorly understood. While RL substantially improves structured tool-call generation, it is unclear which features emerge, which are preserved, and whether identified features can be leveraged for retraining-free behavioral control. In this work, we show that Dedicated Feature Crosscoders (DFC) isolate a compact set of RL-specific features that mediate tool-calling capability in Qwen2.5-3B. Across a 48-crosscoder hyperparameter sweep, encode-decode reconstruction improves the RL model's tool correctness by +31.1 &plusmn; 9.7 pp and passively transfers tool-calling ability to the frozen base model by +6.8 &plusmn; 5.0 pp which we call a capability spillover. Our findings show that DFC partitioning concentrates RL-introduced capability into a minimal, steerable feature set that enables runtime behavioral control of agentic LLMs.

<h3><svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-bookmark" viewBox="0 0 16 16">
  <path d="M2 2a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v13.5a.5.5 0 0 1-.777.416L8 13.101l-5.223 2.815A.5.5 0 0 1 2 15.5V2zm2-1a1 1 0 0 0-1 1v12.566l4.723-2.482a.5.5 0 0 1 .554 0L13 14.566V2a1 1 0 0 0-1-1H4z"/>
</svg> Citation</h3>
<div class="bibtex">
<!-- bibtex -->
<h4>BibTeX</h4>
<pre>
@inproceedings{shportko2026localizing,
  title={Localizing RL-Induced Tool Use to a Single Crosscoder Feature},
  author={Shportko, Andrii and Bhokare, Shubham and Alzahrani, Ahmed Zeyad A and Cheng, Bowen and Mercier, Gustavo and Hullman, Jessica},
  booktitle={Mechanistic Interpretability Workshop at the 43rd International Conference on Machine Learning},
  year={2026}
}
</pre>
</div>
