# <h1 align="center">**Translation**</h1>

<p align="center">
<img src="images/image_readme.png"> 
</p>

In this repository, translation models are implemented, a task of Natural Language Processing (NLP) that involves converting a sequence of text or audio from one language to another, with text translation being the most common. These models are created using TensorFlow and Hugging Face's Transformers libraries.

The most significant use cases include document translation, web content localization, real-time interpretation in video conferencing applications, and linguistic assistance in messaging and social media applications. Additionally, these models are fundamental in the creation of multilingual virtual assistants and in the automation of translation processes in global companies.

## **Implemented Models:**

- **English to Spanish text translation with LSTM networks:** Model using [LSTM networks](https://www.tensorflow.org/api_docs/python/tf/keras/layers/LSTM) with an [Attention mechanism](https://www.tensorflow.org/api_docs/python/tf/keras/layers/MultiHeadAttention) to translate text from English to Spanish, trained with the [ManyThings dataset](https://www.manythings.org/anki/). It has high performance and [BLEU score](https://huggingface.co/spaces/evaluate-metric/bleu) for short texts, medium for medium-length texts, and low for long texts.

- **English to Spanish text translation with MarianMT:** Model [``Helsinki-NLP/opus-mt-en-es``](https://huggingface.co/Helsinki-NLP/opus-mt-en-es), which is a variant of [MarianMT](https://huggingface.co/docs/transformers/model_doc/marian) fine-tuned with the [OPUS eng-spa dataset](https://github.com/Helsinki-NLP/Tatoeba-Challenge/blob/master/models/eng-spa/README.md). To further enhance its performance in English to Spanish text translation, it is fine-tuned again with the ManyThings dataset. It has excellent performance and a high BLEU score for texts of any length, from short to very long.

## **Some Results**

<p align="left">
<img src="images/images_models/translation_6.png" style="width: 362px;"> 
</p>

---
<p align="left">
<img src="images/images_models/translation_5.png" style="width: 671px;"> 
</p>

---
<p align="left">
<img src="images/images_models/translation_4.png" style="width: 701px;"> 
</p>

---
<p align="left">
<img src="images/images_models/translation_3.png" style="width: 716px;"> 
</p>

---
<p align="left">
<img src="images/images_models/translation_2.png" style="width: 718px;"> 
</p>

---
<p align="left">
<img src="images/images_models/translation_1.png" style="width: 711px;"> 
</p>

#### *More results can be found in the respective notebooks.*

## **Technological Stack**
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)](https://docs.python.org/3/) 
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white&labelColor=101010)](https://www.tensorflow.org/api_docs)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=white&labelColor=101010)](https://huggingface.co/)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white&labelColor=101010)](https://plotly.com/)

## **Contact**
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=101010)](mailto:jerson.gimenesbeltran@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101010)](https://www.linkedin.com/in/jerson-gimenes-beltran/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/JersonGB22/)