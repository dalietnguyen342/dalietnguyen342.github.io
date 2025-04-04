---
title: "Multimodal Medical Question Answering System (DSC2024)"
collection: portfolio
excerpt: "Technologies: HuggingFace Transformers, Langchain, NLP, TTS(Text-to_Speeech: Speech Processing technique), LLMs and ETL."
---

[GITHUB](https://github.com/UIT-HuyTanNhiPhuong/Blind-Doctor.git)

## Overview
![image](https://github.com/user-attachments/assets/f70078d4-8212-46a0-a848-71d44c8812ba)

Developed an end-to-end multimodal system for medical question answering that seamlessly integrates data engineering pipelines, advanced data science methodologies, and state-of-the-art AI models. The system is designed to provide accurate and accessible medical information by processing both audio and textual inputs and generating human-like responses.

## Key Models & Technologies
- **Wav2Vec 2.0:** For high-fidelity speech recognition and conversion of spoken queries into text.
- **Sentence-BERT:** For effective semantic retrieval and ensuring the context of medical information is preserved.
- **Fine-Tuned LLMs:** Customized language models trained on medical datasets to generate accurate and reliable responses.
- **Integrated TTS:** Utilized advanced TTS systems to convert text responses into clear and natural audio output.

## Data Engineering & Pipeline Integration
- **Data Ingestion & Preprocessing:**  
  Constructed a robust ETL pipeline to collect and preprocess multimodal data (speech and text) from diverse medical information sources. This ensures high-quality input data for downstream processing.

- **System Integration:**  
  Integrated various components of the system—speech recognition, text processing, and text-to-speech conversion—into a cohesive pipeline that supports real-time interaction and scalable deployment.

## Data Science & AI Model Integration
- **Speech Recognition:**  
  Utilized **Wav2Vec 2.0** for accurate and efficient speech-to-text conversion, enabling the system to understand spoken queries from users.

- **Text Retrieval & Understanding:**  
  Employed **Sentence-BERT** for semantic search and contextual understanding, ensuring that the system accurately retrieves relevant medical information from a curated database.

- **Text Generation:**  
  Leveraged fine-tuned Large Language Models (LLMs) to generate precise, contextually relevant answers for medical queries. These models are tailored for medical language comprehension and reasoning.

- **Text-to-Speech Conversion:**  
  Integrated text-to-speech (TTS) technology to convert the generated textual responses into natural-sounding speech, making the system accessible for users who prefer audio interaction.

## Conclusion
This multimodal system exemplifies the convergence of data engineering, data science, and AI to address complex real-world problems in the medical domain. By integrating robust data pipelines with cutting-edge deep learning models, the system not only delivers high-accuracy medical question answering but also enhances user accessibility through both textual and audio interfaces.
