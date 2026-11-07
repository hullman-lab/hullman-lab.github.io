---
layout: paper
category: paper
date: 2026-10-02
permalink: /paper/2026/11/01/fairness-failure-modes.html
title: "Fairness Failure Modes of Multimodal LLMs"
authors: "Canyu Chen, Anglin Cai, Joan Nwatu, Yale Li, Jessica Hullman, Rada Mihalcea, Kathleen McKeown, Manling Li"
venue: "Conference on Neural Information Processing Systems (NeurIPS) 2026"
thumb: "assets/images/paper-thumb-fairness-failure-modes.png"
banner: "assets/images/paper-banner-fairness-failure-modes.png"
caption: "An example from MultiBBQ. Each of the three contexts has a negative and a non-negative question, and correct answers are shown. Demographic words are replaced by neutral expressions in ambiguous contexts to avoid shortcut reasoning."
pdf: "assets/papers/2026-fairness-failure-modes-mllms.pdf"
---

<!-- abstract -->

Although Multimodal Large Language Models (MLLMs) are increasingly deployed in high-stakes domains, the fairness of their outputs is under-explored. Building on the BBQ language bias benchmark, we construct a new dataset, MultiBBQ, using attested social biases and AI-generated photorealistic images for controllable fairness evaluation of MLLMs in both visual-only and visual-language contexts. We propose two metrics, Fairness Score and Bias Score, and design an evaluation paradigm to address the challenges of shortcut reasoning and data contamination. Using comprehensive benchmarking, we diagnose four critical Fairness Failure Modes of MLLMs. In particular, proprietary models may fail to conduct effective counter-bias reasoning in disambiguated contexts due to over-refusal, while open-source models are deficient at abstaining in ambiguous contexts. We also analyze how input and model factors degrade fairness, demonstrate that MLLMs amplify bias over their backbone LLMs, and show the potentially limited effectiveness of mitigation methods such as reasoning and fairness instruction.

<h3><svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-bookmark" viewBox="0 0 16 16">
  <path d="M2 2a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v13.5a.5.5 0 0 1-.777.416L8 13.101l-5.223 2.815A.5.5 0 0 1 2 15.5V2zm2-1a1 1 0 0 0-1 1v12.566l4.723-2.482a.5.5 0 0 1 .554 0L13 14.566V2a1 1 0 0 0-1-1H4z"/>
</svg> Citation</h3>
<div class="bibtex">
<!-- bibtex -->
<h4>BibTeX</h4>
<pre>
@inproceedings{chen2026fairness,
  title={Fairness Failure Modes of Multimodal LLMs},
  author={Chen, Canyu and Cai, Anglin and Nwatu, Joan and Li, Yale and Hullman, Jessica and Mihalcea, Rada and McKeown, Kathleen and Li, Manling},
  booktitle={Advances in Neural Information Processing Systems (NeurIPS)},
  year={2026}
}
</pre>
</div>
