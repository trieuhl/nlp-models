Pre-trained models

## BERT
1. [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (Devlin et al., 2019)](https://arxiv.org/pdf/1810.04805.pdf) [[github]](https://github.com/huggingface/transformers)
<p align="center">
    <img src="figs/bert.png" width="500"/>
    <br>
        <em>BERT (Devlin et al., 2019)</em>
</p>

- Citations: 31k (Google Scholar, 2021 Dec)

- Compare with:
  - OpenAI GPT: finetune-based, Transformer-based, left-to-right
  - ELMo: feature-based, left-to-right and right-to-left representations
  - GloVe: word representations

- Architecture: Transformer (Vaswani et al., 2017)

## OpenAI GPT-2
2. [Language Models are Unsupervised Multitask Learners (Radford et al., 2019)](http://www.persagen.com/files/misc/radford2019language.pdf) [[github]](https://github.com/openai/gpt-2)
- Citations: 2.2k (Google Scholar, 2021 Dec)

## Transformer
3. [Attention Is All You Need (Vaswani et al., 2017)](https://proceedings.neurips.cc/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf) [[github]](https://github.com/jadore801120/attention-is-all-you-need-pytorch)
- Citations: 32.9k (Google Scholar, 2021 Dec)

## ELMo
4. [Deep contextualized word representations (Peters et al., NAACL 2018)](https://arxiv.org/pdf/1802.05365.pdf) [[github]](https://github.com/HIT-SCIR/ELMoForManyLangs)
- Citations: 8.7k (Google, 2021 Dec)
- Architecture: bidirectional LSTM, two-layer biLMs
  - Word vectors are learned functions of the internal states of a deep bidirectional language model (biLM)

## GloVe
5. [GloVe: Global Vectors for Word Representation (Pennington et al., EMNLP 2014)](https://aclanthology.org/D14-1162.pdf) [[github]](https://github.com/stanfordnlp/GloVe)
- Citations: 25k (Google Scholar, 2021 Dec)
- Compare with:
  - CBOW, skip-gram (Mikolov et al., 2013)

## CBOW, skip-gram
6. [Efficient Estimation of Word Representations in Vector Space (Mikolov et al., ICLR 2013)](https://arxiv.org/pdf/1301.3781.pdf) [[github(gensim)]](https://github.com/RaRe-Technologies/gensim)
- Citations: 25.7k (Google Scholar, 2021 Dec)

7. [Distributed representations of words and phrases and their compositionality (Mikolov et al., NIPS 2013)](https://proceedings.neurips.cc/paper/2013/file/9aa42b31882ec039965f3c4923ce901b-Paper.pdf)
- Citations: 31.1k (Google Scholar, 2021 Dec)
