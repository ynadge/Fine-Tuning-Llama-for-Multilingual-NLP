# Fine-Tuning-Llama-for-Multilingual-NLP

This project aims to adapt Llama-2 to effectively generate fluent and culturally sensitive Hindi material. By fine-tuning the model on a carefully curated dataset of high-quality Hindi text, I aim to improve its performance on various NLP tasks, such as text generation, translation, and question answering.

## Motivation and Problem Significance

Hindi is the world's third-most spoken language. Giving it scale: approximately 8 in every hundred people speak Hindi! With such a large population of the world communicating and spending their day-to-day lives immersed in this language and its culture, it is disheartening that the availability of high-quality language models specifically trained on Hindi data remains a significant challenge.

## Key Technologies
* sentencepiece: Fast, language-independent subword tokenizer that learns to split text into subword units directly from the data.
* transformers: Comprehensive collection of pre-trained models, tokenizers, and utilities for state-of-the-art natural language processing tasks.
* torch: Machine learning library that provides a flexible and efficient platform for deep learning research and development.
* IndicTrans2: High-quality machine translation between Indian languages.
* nltk: Leading platform for building Python programs to work with human language data.
* peft: Hugging Face library for easily training large language models with minimal computational cost.

## Steps of the Project
* Developed a Hindi language model using a 100,000-article dataset.
* Employed SentencePiece for tokenization and extended the Llama tokenizer for enhanced performance.
* Implemented a novel pre-training strategy: Combined translation-based pretraining with bilingual next-token prediction for improved multilingual capabilities.
* Fine-tuned the model using the PEFT library for efficient parameter-efficient fine-tuning.
* Leveraged Transformers and IndicTrans libraries for model training and multilingual text processing.

I've included all the details in my [project code](https://github.com/ynadge/Fine-Tuning-Llama-for-Multilingual-NLP/blob/main/Lamma_2_Hindi_Finetuned.ipynb).

## Future Work
Language fluency is not the sole test of a model's ability to generate quality material; it is also literary traditions, historical context, and so much more. Training this model on datasets that are geared towards all these different parts of the culture would make it truly relevant when generating Hindi text.
