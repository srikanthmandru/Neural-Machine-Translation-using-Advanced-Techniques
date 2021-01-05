# Neural Machine Translation using Advanced Techniques


## Author: Srikanth Babu Mandru

### Project Description:

One of the primary ways of communication between humans is through the human-languages. However, due to diversity in our cultures and living, many languages have been evolved along with the human-evolution. To make humans understand the language of others from a different language-speaking nation or region, there is a need for translator to convert the ideas from one language to another. Since human-translators are not available at all-times, so this project aims to build a “Machine Translation” model that translates text from one language to another using the recent advancements in Machine learning field, especially neural network architectures from the deep learning space. To be precise, the project goal is to implement a machine learning model that can translate the text in English to Hindi. For this project, I have started working with the Seq2Seq (Sequence-to-Sequence) model with attention from Bahdanau et al. [6] since it is a well-known architecture for machine translation using the idea of “Attention” to the RNN encoder-decoder networks from Bahdanau et al. [5]. The Seq2Seq model has been implemented, and from my findings, it was taking more time to train as it contains RNN layers. I have also found that the model’s generation ability decreases as the maximum sequence length of sentences increases which shows that the RNNs are performing poorly at capturing the long-range dependencies. In this process of building a Neural Machine
Translation (NMT), I came to know that seq2seq model requires more memory and time to train. The main contribution of this project is to bridge the gap of work on English-Hindi translation with proper techniques and results. Nevertheless, the main theme of this project is building a good translation model. Finally, with the experimentation, I am able to build a seq2seq attention model that resulted in the **BLEU score of “17.83”**.


### References:

1. Ilya et al., Sequence to Sequence Learning with Neural Networks, NIPS, 2014. (https://arxiv.org/abs/1409.3215)

2. Ashish et al., Attention is All you need, NIPS, 2017. (https://arxiv.org/abs/1706.03762)

3. IIT Bombay English-Hindi dataset Link:
http://www.cfilt.iitb.ac.in/iitb_parallel/

4. Chris Manning et al., Effective Approaches to Attention-based Neural Machine Translation, EMNLP, 2015. (https://arxiv.org/abs/1508.04025)

5. Bahdanau et al., Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation, EMNLP, 2014. (https://arxiv.org/abs/1406.1078)

6. Bahdanau et al., Neural Machine Translation by Jointly Learning to Align and Translate, ICLR 2015. (https://arxiv.org/abs/1409.0473)

7. OpenNMT : (https://opennmt.net/)

8. Pre-Trained BERT: ( https://pypi.org/project/pytorch-pretrained-bert/ )

9. Jay Alammar’s blog posts: Alammar, Jay (2018). The Illustrated Transformer [Blog post]. Retrieved from ( https://jalammar.github.io/illustrated-transformer/ )

10. Seq2Seq tutorials:
(a.)https://pytorch.org/tutorials/intermediate/seq2seq_ translation_tutorial.html 
(b.)https://pytorch.org/tutorials/beginner/torchtext_tra nslation_tutorial.html
