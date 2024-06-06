# Harnessing large language models over transformer models for detecting Bengali depressive social media text: A comprehensive study

## Abstract
In an era where the silent struggle of underdiagnosed depression pervades globally, our research delves into the crucial link between mental health and social media. This work focuses on early detection of depression, particularly in extroverted social media users, using LLMs such as GPT 3.5, GPT 4 and our proposed GPT
3.5 fine-tuned model DepGPT, as well as advanced Deep learning models(LSTM, Bi-LSTM, GRU, BiGRU) and Transformer models(BERT, BanglaBERT, SahajBERT, BanglaBERT-Base). The study categorized Reddit and X datasets into ‘‘Depressive’’ and ‘‘Non-Depressive’’ segments, translated into Bengali by native speakers with expertise in mental health, resulting in the creation of the Bengali Social Media Depressive Dataset (BSMDD). 

Our work provides full architecture details for each model and a methodical way to assess their performance in Bengali depressive text categorization using zero-shot and few-shot learning techniques. Our work demonstrates the superiority of SahajBERT and Bi-LSTM with FastText embeddings in their respective domains also tackles explainability issues with transformer models and emphasizes the effectiveness of LLMs, especially DepGPT(GPT 3.5 fine-tuned), demonstrating flexibility and competence in a range of learning contexts. According to the experiment results, the proposed model, DepGPT, outperformed not only Alpaca Lora 7B in zero-shot and few-shot scenarios but also every other model, achieving a near-perfect accuracy of 0.9796 and an F1-score of 0.9804, high recall, and exceptional precision. Although competitive, GPT-3.5 Turbo and Alpaca Lora 7B show relatively poorer effectiveness in zero-shot and few-shot situations. The work emphasizes the effectiveness and flexibility of LLMs in a variety of linguistic circumstances, providing insightful information about the complex field of depression detection models.

## Proposed Methodology

![Methodology](https://github.com/AKC23/Harnessing-LLMs-over-transformer-models-for-detecting-Bengali-depressive-text-A-comprehensive-study/assets/57568723/f239f1c7-951e-4c66-a735-1aa2fdb08e77)

## Paper
Accepted version - [ResearchGate](https://www.researchgate.net/publication/380628761_Harnessing_large_language_models_over_transformer_models_for_detecting_Bengali_depressive_social_media_text_A_comprehensive_study) <br>
Published version - https://doi.org/10.1016/j.nlp.2024.100075

## Citation
``` yaml
@article{chowdhury2024harnessing,
  title={Harnessing Large Language Models Over Transformer Models for Detecting Bengali Depressive Social Media Text: A Comprehensive Study},
  author={Chowdhury, Ahmadul Karim and Sujon, Md Saidur Rahman and Shafi, Md Shirajus Salekin and Ahmmad, Tasin and Ahmed, Sifat and Hasib, Khan Md and Shah, Faisal Muhammad},
  journal={arXiv preprint arXiv:2401.07310},
  year={2024}
}
```



