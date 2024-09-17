---
layout: page
title: Virtual Assistant
short-title: Virtual Assistant 
description:  Customized AI Assistant Enhancing Business Operations
img: assets/img/project/virtual_assistant.gif
importance: 1
category: work
---

Keywords: `Large Language Model(LLM)`, `Retrival Augmented Generation(RAG)`, `Vector Database`, `Automatic Speech Recognition(ASR)`, `Text-to-Speech(TTS)`, 

---

#### Brief Description

The primary objective of this project was to create an intuitive and user-friendly system capable of delivering accurate and contextually relevant information to both employees and root-level users. This virtual assistant seamlessly integrates several advanced technologies to ensure it operates efficiently without the need for constant human intervention and provides business specific supports to users.

Key modules of ACI Virtual Assistant:
- ASR system for transcribing quries both in Bengali and English
- Vector Database for storing business specific data
- LLM based RAG system for response generation 
- TTS system for deliver the response in audio format
<br>

#### Details of the components of the overall system and technologies

* Automatic Speech Recognition (ASR) Module
    * `Technology Used`: Transformer-based model Whisper trained on both Benglai and English Data.
    * `Functionality`: Converts spoken language into text with high accuracy, enabling the assistant to understand and process user queries in real-time.

* Response Generation and Conversation Control Module
    * `Technology Used`: State-of-the-art Large Language Model (LLM), Vector Database, RAG
    * `Functionality`: Acts as the core processing unit, interpreting the transcribed text and generating appropriate responses based on the input query.
    * `Enhancement`: Retrieval-Augmented Generation (RAG) is employed to prvent hallucination and ensure that the responses are not only coherent but also contextually accurate by leveraging a domain-specific knowledge base. This integration significantly enhances the system's ability to provide precise business-related information.

* Text-to-Speech (TTS) Module
    * `Technologies Used`: VITS TTS and Style TTS.
    * `Function`: Converts the generated text responses back into speech, making the interaction more natural and accessible, especially for users who prefer auditory information.

* Multilingual Capability
    * The virtual assistant is designed to be multilingual, with the ability to operate proficiently in both Bengali and English. This feature is particularly beneficial for root-level users who may face challenges with new technology and language barriers. By supporting these two languages, the assistant ensures broader accessibility and usability, fostering inclusivity within the organization.

* System Integration
    * Integration of `FastAPI` based devOps system and `Qdrant` based vector database system for seamless usage.
    * Unity based app for easy and user friendly interaction

<br><br>

Simple illustration of the project <br>

<div class="gif-image-container">
    <img src="/assets/img/project/virtual_assistant.gif" width="600px" height="400px" alt="Satelite Project">
</div>

N.B: **The code for this project can't be made public for propritory reasons**

#### Collaborators:
    1. Sifat Ibn Amin
    2. Rushidan Islam
    3. A F M Mahfuzul Kabir
    4. Sawradip Saha

