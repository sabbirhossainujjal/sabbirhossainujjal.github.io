---
layout: page
title: Bengali Name Extractor
short-title: Bengali Name Extractor
description: A deep learning based project to build a system which can extract person name from given text. 
img: assets/img/project/name_extractor.png
# redirect: https://unsplash.com
importance: 3
category: academic
---


A deep learning based project to build a system which can extract person name from given text. The project was focused to build a robust model which can extract any person name which can be used in any call center and online voice based transaction systems.

As this is a name entity extraction task, it was handled as `token classification` task. In token classification process we can predict which token belongs to name entity class and extract names from this prediction. For the task, first I preprocessed the given data, making appropiate datasets for token classification modeling, then experimented with different huggingface models for the task. Then I train the models with these experimented parameters and build an end-to-end inference script.The inference script will load the best saved models (saved in training processe) and do prediction using the model and then post-process the model output for desire output format for given input.<br>

Example -<br>
input: আব্দুর রহিম নামের কাস্টমারকে একশ টাকা বাকি দিলাম
output: আব্দুর রহিম
input: অর্থনীতি ও আর্থসামাজিক বেশির ভাগ সূচকে বাংলাদেশ ছাড়িয়ে গেছে দক্ষিণ এশিয়াকে ।
output: None