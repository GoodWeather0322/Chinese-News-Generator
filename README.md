# Chinese News Generator


<h3 id=2>Chinese News Article Generator</h3>

A PyTorch implementation of Chinese News Article Generator with with [Huggingface Transformers](https://github.com/huggingface/transformers)

Model is based on Pretrained [GPT-2 Model](https://github.com/openai/gpt-2) and [BERT chinese tokenizer](https://github.com/google-research/bert), finetune by chinese news articles

- [GPT-2 Model](https://github.com/openai/gpt-2)
- [BERT chinese tokenizer](https://github.com/google-research/bert)
- Training Dataset (News articles & PTT articles)
    - CNA News
    - UDN News
    - CTS News
    - PTT Gossiping

## Model Descriptions

 A chinese version of GPT-2 model, using BERT chinese BPE tokenizer

 - A simple prototype of chinese news article generator

 - **1.5B** parameters for GPT2-base model and **3.2B** parameters for GPT2-medium model

 - **21128** BPE tokens from BERT chinese BPE tokenizer

 - **1.4B** tokens for model training

 <center>

[loss curve](/loss.png)

 </center>




## Demo website

## Generate Example


