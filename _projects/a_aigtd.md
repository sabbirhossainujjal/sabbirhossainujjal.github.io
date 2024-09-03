---
layout: page
title: AI Generated Text Detection
short-title: AI Generated Text Detection
description: A deep learning based project to build a system which can detect whether a given text is AI generated or Human written.
img: assets/img/project/AI-content-detectors.png
# redirect: https://unsplash.com
importance: 1
category: academic
---

keywords: `Deep Learning`, `NLP`, `AI Text Detection`, `Classification`, `Feature Engineering`, `Machine Learning`, `Deberta`, `Bert`

A deep learning based project to build a system which can detect whether a given text is AI generated or Human written. The project was focused to build a robust model which accurately detect AI generated text which can help on different evaluation process.


# Problem Statement
With the rise of AI revolution, In recent years, large language models (LLMs) have become increasingly sophisticated, capable of generating text that is difficult to distinguish from human-written text. Modern LLM are so powerful that students could use LLMs to generate essays that are not their own, missing crucial learning keystones, which also bring significant changes in education system. 

In this project I developed a Deep Learning based model that can accurately detect whether an essay was written by a student or an LLM which may help the evaluator to take proper action. 

# Dataset
For the task we needed two type of data
- Human written text data: 
    - [persuade corpus 2.0](https://github.com/scrosseye/persuade_corpus_2.0)
    * This dataset comprises over 25,000 argumentative essays produced by 6th-12th grade students in the United States for 15 topics.<br>
- AI generated data<br>
    - For AI generated Data we used different available LLM models (`Chat-GPT-3.5`, `LLAMA-2`, `Mistral`, `Gemini`) for the same topics as the human written text.


# Modeling Approach
- The task is a Binary classification task. 
* We used two type of modeling approach for the task. 
1. Feature Based ML Model
2. Deep Learning Based Model

### ML Modeling:
For conventional ML model we extracted different features from the dataset.  We extracted feature on different level for the model.<br>
1. Paragraph level features<br>
2. Sentence level features<br>
3. Word level features<br>

### DL Modeling:
For our task we leverage different transformer base models
1. Bert-base-cased
2. Bert-small
3. Deverta-V3-small


> For more details please check out the project report:

<iframe src="/assets/pdf/AiGeneratedTextDetection.pdf" width="100%" height="600px" frameborder="0">
    Your browser does not support PDFs. Please download the PDF to view it: <a href="/assets/pdf/AiGeneratedTextDetection.pdf">Download PDF</a>.
</iframe>