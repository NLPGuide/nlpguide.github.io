# NLP Guide

This is an open guide to natural language processing.

*Edit this guide at [github.com/NLPGuide](https://github.com/NLPGuide/)*

## Progress

See also: NLP Guide for [2018](/2018) and [2017](/2017)  

NLP Progress  
[nlpprogress.com](https://nlpprogress.com/)

EFF AI Metrics - Written Language, Spoken Language  
[eff.org/ai/metrics](https://www.eff.org/ai/metrics)

AI Index - Natural Language Understanding  
[aiindex.org](https://aiindex.org/2017-report.pdf)

## Demos

[explosion.ai/demos](https://explosion.ai/demos/)

## Language

Definitions of language are often political and not consistent.  For our purposes by default we defer to https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes.  Some major libs and services use non-standard codes.  (For example, Google Translate uses `jw` not `jv` for Javanese, and `iw` not `he` for Hebrew.) Confusion with country codes is common.

## Tasks  

parsing  
translation  
named-entity recognition  
natural language understanding  
natural language generation  
speech - recognition, synthesis  
classification - sentiment analysis, spam detection  
relation extraction  
coreference resolution  

## Applications

translation:  Google, Microsoft, Baidu, Yandex, DeepL, Babelfish  
agents:  Siri, Google Now, Google Assistant, Amazon Alexa, Microsoft Cortana, IBM Watson

Most natural language processing is not standalone products but integrations in nearly all major applications, for example:  

search engines: Google, Bing, Baidu, Yandex  
marketplaces: eBay, Amazon, Ali Baba  
social networks: Facebook, Twitter, Reddit, Quora, StackExchange  
integrated as recommendations, spam filtering, spelling correction, advert matching, entity recognition

## Libs

NLTK, Moses, Giza++, [OpenNLP](https://opennlp.apache.org/)  
spaCy, Stanford NLP, Berkeley, TF [syntaxnet](https://github.com/tensorflow/models/tree/master/research/syntaxnet)      
[Universal Dependencies](http://universaldependencies.org/)  
[AllenNLP](http://allennlp.org/)  
THUMT, TF seq2seq, pytorch seq2seq  

GitHub: [natural-language-processing](https://github.com/topics/natural-language-processing), [nlp](https://github.com/topics/nlp)

> Which programming languages?  C/C++, Java ==> python, NodeJS

## APIs
Google Cloud, Azure ML, AWS, IBM
Nuance, Indico, ABBYY   
EventRegistry

> How do choose?  Language support (programming and human), latency and price... and last but not least, quality.

## OS/Browser Integrations
speech recognition, speech synthesis, OCR, handwriting recognition

## Datasets  
Wikipedia, Common Crawl  
Universal Dependencies  
Penn Tree Bank  
WMT workshop data  
CLEVR  
SQuAD  
Enron emails  
[OPUS open parallel corpus](http://opus.nlpl.eu/)  
[WordNet](https://wordnet.princeton.edu/)  
[NLTK Corpora](http://www.nltk.org/nltk_data/) 

> For which tasks is there data?  For which languages is there data?

## Research Orgs
Google, Bing, Baidu, Yandex, Amazon, Facebook
Twitter, Fuji Xerox, NTT, Rakuten, SAP, eBay

Stanford, Johns Hopkins, U of Washington, U of Maryland, USC ISI, CMU, Cornell
U de Montréal  
U of Edinburgh, Sheffield, Cambridge
DFKI, U of Aachen, Stuttgart, Heidelberg, TU Berlin, Munich, Darmstadt, Humboldt U  
Bar-Ilan U, Hebrew U
Tsinghua U, Peking U, Chinese Academy of Sciences
U Kyoto, Tokyo

SRI/DARPA

> Who is missing?  Relative to their output in general: Apple, Samsung, eBay, Oracle, Xerox, MIT and Ivy League, Technion, UCx, Switzerland, India, France, Russia and Eastern Europe, OpenAI

## Papers

arXiv cs.CL: [archive](https://arxiv.org/archive/cs.CL) | [recent](https://arxiv.org/list/cs.CL/recent)  
arXiv cs.LG: [archive](https://arxiv.org/archive/cs.LG) | [recent](https://arxiv.org/list/cs.LG/recent)

**[1]** Antoine Bordes, et al. "**Joint Learning of Words and Meaning Representations for Open-Text Semantic Parsing**." AISTATS(2012) [[pdf]](https://www.hds.utc.fr/~bordesan/dokuwiki/lib/exe/fetch.php?id=en%3Apubli&cache=cache&media=en:bordes12aistats.pdf)

**[2]** Mikolov, et al. "**Distributed representations of words and phrases and their compositionality**." ANIPS(2013): 3111-3119 [[pdf]](http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf) **(word2vec)**

**[3]** Sutskever, et al. "**“Sequence to sequence learning with neural networks**." ANIPS(2014) [[pdf]](http://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf)

**[4]** Ankit Kumar, et al. "**“Ask Me Anything: Dynamic Memory Networks for Natural Language Processing**." arXiv preprint arXiv:1506.07285(2015) [[pdf]](https://arxiv.org/abs/1506.07285)

**[5]** Yoon Kim, et al. "**Character-Aware Neural Language Models**." NIPS(2015) arXiv preprint arXiv:1508.06615(2015) [[pdf]](https://arxiv.org/abs/1508.06615)

**[6]** Jason Weston, et al. "**Towards AI-Complete Question Answering: A Set of Prerequisite Toy Tasks**." arXiv preprint arXiv:1502.05698(2015) [[pdf]](https://arxiv.org/abs/1502.05698) **(bAbI tasks)**

**[7]** Karl Moritz Hermann, et al. "**Teaching Machines to Read and Comprehend**." arXiv preprint arXiv:1506.03340(2015) [[pdf]](https://arxiv.org/abs/1506.03340) **(CNN/DailyMail cloze style questions)**

**[8]** Alexis Conneau, et al. "**Very Deep Convolutional Networks for Natural Language Processing**." arXiv preprint arXiv:1606.01781(2016) [[pdf]](https://arxiv.org/abs/1606.01781) **(state-of-the-art in text classification)**

**[9]** Armand Joulin, et al. "**Bag of Tricks for Efficient Text Classification**." arXiv preprint arXiv:1607.01759(2016) [[pdf]](https://arxiv.org/abs/1607.01759) **(slightly worse than state-of-the-art, but a lot faster)**


#### RNN and Sequence-to-Sequence Models

**[34]** Graves, Alex. "**Generating sequences with recurrent neural networks**." arXiv preprint arXiv:1308.0850 (2013). [[pdf]](http://arxiv.org/pdf/1308.0850) **(LSTM, very nice generating result, show the power of RNN)** 

**[35]** Cho, Kyunghyun, et al. "**Learning phrase representations using RNN encoder-decoder for statistical machine translation**." arXiv preprint arXiv:1406.1078 (2014). [[pdf]](http://arxiv.org/pdf/1406.1078) **(First Seq-to-Seq Paper)** 

**[36]** Sutskever, Ilya, Oriol Vinyals, and Quoc V. Le. "**Sequence to sequence learning with neural networks**." Advances in neural information processing systems. 2014. [[pdf]](https://arxiv.org/pdf/1409.3215.pdf) **(Outstanding Work)** 

**[37]** Bahdanau, Dzmitry, KyungHyun Cho, and Yoshua Bengio. "**Neural Machine Translation by Jointly Learning to Align and Translate**." arXiv preprint arXiv:1409.0473 (2014). [[pdf]](https://arxiv.org/pdf/1409.0473v7.pdf) 

**[38]** Vinyals, Oriol, and Quoc Le. "**A neural conversational model**." arXiv preprint arXiv:1506.05869 (2015). [[pdf]](http://arxiv.org/pdf/1506.05869.pdf%20(http://arxiv.org/pdf/1506.05869.pdf)) **(Seq-to-Seq on Chatbot)** 

#### Speech

**[8]** Hinton, Geoffrey, et al. "**Deep neural networks for acoustic modeling in speech recognition: The shared views of four research groups**." IEEE Signal Processing Magazine 29.6 (2012): 82-97. [[pdf]](http://cs224d.stanford.edu/papers/maas_paper.pdf) **(Breakthrough in speech recognition)**

**[9]** Graves, Alex, Abdel-rahman Mohamed, and Geoffrey Hinton. "**Speech recognition with deep recurrent neural networks**." 2013 IEEE international conference on acoustics, speech and signal processing. IEEE, 2013. [[pdf]](http://arxiv.org/pdf/1303.5778.pdf) **(RNN)**

**[10]** Graves, Alex, and Navdeep Jaitly. "**Towards End-To-End Speech Recognition with Recurrent Neural Networks**." ICML. Vol. 14. 2014. [[pdf]](http://www.jmlr.org/proceedings/papers/v32/graves14.pdf)

**[11]** Sak, Haşim, et al. "**Fast and accurate recurrent neural network acoustic models for speech recognition**." arXiv preprint arXiv:1507.06947 (2015). [[pdf]](http://arxiv.org/pdf/1507.06947) **(Google Speech Recognition System)**

**[12]** Amodei, Dario, et al. "**Deep speech 2: End-to-end speech recognition in english and mandarin**." arXiv preprint arXiv:1512.02595 (2015). [[pdf]](https://arxiv.org/pdf/1512.02595.pdf) **(Baidu Speech Recognition System)**

**[13]** W. Xiong, J. Droppo, X. Huang, F. Seide, M. Seltzer, A. Stolcke, D. Yu, G. Zweig "**Achieving Human Parity in Conversational Speech Recognition**." arXiv preprint arXiv:1610.05256 (2016). [[pdf]](https://arxiv.org/pdf/1610.05256v1) **(State-of-the-art in speech recognition, Microsoft)**

## Startups

[angel.co/natural-language-processing](https://angel.co/natural-language-processing)

[crunchbase.com/.../natural-language-processing](https://www.crunchbase.com/search/organizations/field/organizations/categories/natural-language-processing)

Unbabel, Lilt, Aylien

acquired: Siri (Apple), Viv (Samsung), WordLens (Google), wit.ai (Facebook), 

## Events

ACL

EMNLP  

CoNLL

EACL

NIST TAC

PyData  

RAAIS  

NIPS

Google IO, F8, AWS DevDay...

## Competitions
WMT workshops, conferences  
Kaggle [text-data](https://www.kaggle.com/tags/text-data), [linguistics](https://www.kaggle.com/tags/linguistics), [languages](https://www.kaggle.com/tags/languages), [literature](https://www.kaggle.com/tags/literature)  
annotated datasets like SQuAD and CLEVR  
[Winograd Schema Challenge](https://cs.nyu.edu/faculty/davise/papers/WinogradSchemas/WS.html) ([wiki](https://en.wikipedia.org/wiki/Winograd_Schema_Challenge))

## Learning

### Courses

http://cs224n.stanford.edu / http://cs224d.stanford.edu

https://www.youtube.com/watch?v=OQQ-W_63UgQ&list=PL3FW7Lu3i5Jsnh1rnUwq_TcylNr7EkRe6

https://github.com/oxford-cs-deepnlp-2017/lectures

https://github.com/jacobeisenstein/gt-nlp-class/

http://phontron.com/class/mtandseq2seq2018/


### Tutorials

https://fasttext.cc/docs/en/supervised-tutorial.html

http://thestraightdope.mxnet.io/chapter05_recurrent-neural-networks/simple-rnn.html

http://pytorch.org/tutorials/beginner/deep_learning_nlp_tutorial.html

http://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html

https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html


### Books

[*Linguistic Fundamentals for Natural Language Processing: 100 Essentials from Morphology and Syntax*](http://www.morganclaypool.com/doi/abs/10.2200/S00493ED1V01Y201303HLT020)  
2013  
Emily M. Bender, University of Washington  

[*Neural Network Methods for Natural Language Processing*](https://www.morganclaypool.com/doi/abs/10.2200/S00762ED1V01Y201703HLT037)
2017  
Yoav Goldberg, Bar-Ilan University  
Graeme Hirst, University of Toronto  

[*A Primer on Neural Network Models for Natural Language Processing*](http://u.cs.biu.ac.il/~yogo/nnlp.pdf)  
2015 draft  
Yoav Goldberg, Bar-Ilan University  

[*Speech and Language Processing (3rd ed. draft)*](https://web.stanford.edu/~jurafsky/slp3/)  
2017 draft  
Dan Jurafsky, Stanford University  
James H. Martin, University of Colorado  

[*Foundations of Statistical Natural Language Processing*](https://nlp.stanford.edu/fsnlp/)  
1999  
Christopher Manning, Stanford University  
Hinrich Schütze, University of Munich  

[*Introduction to Information Retrieval*](https://nlp.stanford.edu/IR-book/)  
2008  
Christopher Manning, Stanford University  
Prabhakar Raghavan, Google
Hinrich Schütze, University of Munich  


## News Sources

https://nlp.stanford.edu/read/  

https://explosion.ai/blog/  

https://yerevann.github.io/  

http://approximatelycorrect.com/category/natural-language-processing/

http://newsletter.ruder.io/

https://www.producthunt.com/@bittlingmayer/collections

http://nathan.ai


## More Reading

http://mitp.nautil.us/article/170/last-words-computational-linguistics-and-deep-learning

http://colah.github.io/posts/2014-07-NLP-RNNs-Representations/

https://explosion.ai/blog/quora-deep-text-pair-classification  

http://ruder.io/highlights-emnlp-2017/index.html  
http://ruder.io/word-embeddings-2017/

http://approximatelycorrect.com/2017/09/26/a-random-walk-through-emnlp-2017/

http://norvig.com/spell-correct.html  
http://norvig.com/chomsky.html  


## Fora  

[#nlproc](https://twitter.com/search?q=%23nlproc)

https://www.reddit.com/r/LanguageTechnology/

https://plus.google.com/communities/112547995826249627629

http://linguistics.stackexchange.com/

https://stackoverflow.com/questions/tagged/nlp

https://datascience.stackexchange.com/questions/tagged/nlp

https://opendata.stackexchange.com/questions/tagged/nlp


## TODO
related fields - machine learning, linguistics  
subfields  
guide for engineers vs guide for ML researchers
