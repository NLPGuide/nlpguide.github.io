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

## Startups

[angel.co/natural-language-processing](https://angel.co/natural-language-processing)

[crunchbase.com/.../natural-language-processing](https://www.crunchbase.com/search/organizations/field/organizations/categories/natural-language-processing)

Unbabel, Lilt, Aylien

acquired: Siri (Apple), Viv (Samsung), WordLens (Google), wit.ai (Facebook), 

## Events

ACL

EMNLP  

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
