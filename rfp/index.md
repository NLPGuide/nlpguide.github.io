# Requests for Projects
*A list of novel but doable projects in natural language processing*

Inspired by YCombinator's [*Requests for Startups*](https://www.ycombinator.com/rfs/), here is a list of novel but doable projects in natural language processing.

The dataset for a project may not exist yet but we know how to generate it at scale with a bit of scripting.

### Classification / Regression
Given a URL, predict whether or not it is an image.

Given an HTML element, predict whether or not it is an advertisement that should be blocked.  (See rules files for adblockers)

Language identification for written variants of a language like British, American, Canadian and Indian English

Given an HTML element, predict whether or not it is main content (like Chrome, Safari and Firefox for mobile, see Readability and AMP)

Identify propaganda, hate speech and threats of war to monitor regimes and predict conflict


### Sequences / Generation

Given a string, fix the encoding to make it more human-readable if necessary

Given HTML, generate Markdown (.md)
Given text (without formatting, eg from copy-pasting a website), generate Markdown (.md)

Given a GitHub repo, generate a README.md  
Given a README.md, generate a GitHub repo

Given a GitHub Pages-enabled repo, generate HTML

Given a screenshot of a website, generate HTML (What to do about images?)

Given a research paper, generate a blog post  
Given a blog post, generate a research paper

Given a question on StackExchange, generate an answer or comment

Translation between variants like British and American English, or Eastern and Western Armenian

Generate and/or disambiguate between variants and translations of proper names - person names, placenames and organisation names

Transliteration for multiple languages and scripts in one model

Translation for multiple language pairs in one model


### Speech

Transcribe and index the audio of a large set of YouTube videos so that they are searchable


### Datasets

Augment text data with realistic noisification 

Build text data and pre-trained models from arXiv papers, to find quality authors, topic trends, previous work... and slice by time, region, university... 

Build text data and pre-trained models from GitHub repo READMEs


### Representations

Sentence representations

Combine or diff fastText models trained on different datasets or with different parameters


### Visualisation / Interpretability

Visualise/interpet a text classification model's predictions 1) on a row/sentence 2) in aggregate for a model and dataset 3) across models differing by epochs or other hyperparameters

Visualise/interpet a seq2seq model's output 1) on a row/sentence 2) in aggregate for a model and dataset 3) across models differing by epochs or other hyperparameters

Modify fastText `test` to list out rows from the test set that were most strongly assigned each label, the rows most strongly assigned the wrong label, and the rows barely assigned a label

Diff fastText models trained on different datasets or with different parameters

### Speech

Accent reduction - for foreign or regional accents




