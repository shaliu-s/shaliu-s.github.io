---
title: "Confidence Elicitation Improves Selective Generation in Black-Box Large Language Models"
collection: publications
category: conferences
date: 2024-10-1
venue: 'IEEE SMC'
paperurl: 'https://shaliu-s.github.io/files/paper1.pdf'
---

Large language models (LLMs) exhibit impressive capabilities across various domains in natural language processing. However, LLMs can produce fictional content, which we refer to as hallucinations, and it makes the LLMs unreliable. An important research topic is how to make LLMs accurately express the confidence to their answers, so they can refrain from outputting or regenerate output in cases of low-confidence predictions. It facilitates the application of LLMs in high-stakes areas. Currently, research on eliciting calibrated confidence from LLMs is still insufficient. Additionally, methods for estimating uncertainty in responses based on internal parameters of LLMs become unavailable, as many existing LLMs are black boxes served via APIs. Therefore, we analyze the existing confidence elicitation methods and propose COVO, a new confidence elicitation method that allows the black-box LLMs to output their confidence levels by letting the LLM itself judges whether the answer comes from a reliable source. Our method does not require external knowledge and it has high computational efficiency. Experiments show that COVO achieves better calibration and effectively reduces hallucinations in LLMs through selective generation. Additionally, the confidence scores enhance the reliability of the LLMs' responses.
