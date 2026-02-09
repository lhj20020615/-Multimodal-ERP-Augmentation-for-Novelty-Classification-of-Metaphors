# -Multimodal-ERP-Augmentation-for-Novelty-Classification-of-Metaphors
The corresponding code and dataset for the paper are provided, which you may use to replicate the experiments described therein, but they shall not be utilized for any other purposes.
This repository contains the code for a study on metaphor novelty identification using Event-Related Potential (ERP) features. The overall framework of the paper is illustrated in the figure below.
<img width="1889" height="924" alt="abs" src="https://github.com/user-attachments/assets/aef35bef-ab88-4065-b157-0f3fa4198d50" />
The script 2026.py constitutes part of the comparative experimental framework and is adapted from the experimental design proposed in “Surprisal and Metaphor Novelty: Moderate Correlations and Divergent Scaling Effects”. In this implementation, the original binary classification of metaphor novelty is extended to a three-way classification scheme.

Specifically, novelty scores are first assigned to all stimuli and then evenly partitioned into three categories. Given a total of 240 sentences, the top one-third are labeled as high-novelty metaphors (HN-M), the middle one-third as medium-novelty metaphors (MN-M), and the bottom one-third as low-novelty metaphors (LN-M).

The complete experimental results are provided in the 2026.zip archive (with file paths intentionally anonymized). Although the code released here demonstrates the implementation using the Qwen model, alternative models can be substituted and evaluated via local deployment (e.g., through Ollama) without affecting the overall experimental outcomes.
