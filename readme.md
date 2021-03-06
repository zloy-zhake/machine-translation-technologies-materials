# Machine Translation Technologies

## Subject Content

### 1. Overview of machine translation problems
* Заметки об NLP: [1](https://habr.com/ru/post/79790/), [2](https://habr.com/ru/post/79819/), [3](https://habr.com/ru/post/79830/), [4](https://habr.com/ru/post/79853/), [5](https://habr.com/ru/post/79882/), [6](https://habr.com/ru/post/79923/), [7](https://habr.com/ru/post/79962/), [8](https://habr.com/ru/post/80081/), [9](https://habr.com/ru/post/80268/), [10](https://habr.com/ru/post/82068/)
* [Machine translation on wikipedia](https://en.wikipedia.org/wiki/Machine_translation)

##### Assignment:
1. Develop a program that performs word to word translation (Kazakh -> English) using a limited dictionary (20 word pairs) (Each student must choose different words)
2. Develop a program that performs word to word translation (English -> Kazakh) using a limited dictionary (20 word pairs) (Each student must choose different words)
3. Develop a program that performs word sense disambiguation for 10 ambiguous Kazakh words (Each student must choose different words)
4. Develop a program that performs word sense disambiguation for 10 ambiguous English words (Each student must choose different words)
5. Develop a program that identifies 20 named entities in Kazakh text (Each student must choose different words)
5. Develop a program that identifies 20 named entities in English text (Each student must choose different words)

### 2. Rule-based machine translation

#### 2.1 Basic concepts of RBMT
* [General introduction into Machine translation](https://svn.code.sf.net/p/apertium/svn/branches/courses/helsinki_2013/slides/session0.pdf)
* [Apertium for Dummies](http://wiki.apertium.org/wiki/Apertium_for_Dummies)
* [Helsinki Apertium Workshop](http://wiki.apertium.org/wiki/Helsinki_Apertium_Workshop/Programme)

##### Assignment:
1. Choose a Kazakh noun. Write rules to translate all cases of it into English (Each student must choose different words)
2. Choose an English verb. Write rules to translate all tenses of it into Kazakh (Each student must choose different words)

#### 2.2 RBMT models
* [Morphology and morphotactics](https://svn.code.sf.net/p/apertium/svn/branches/courses/helsinki_2013/slides/session1.pdf)
* [Morphophonology](https://svn.code.sf.net/p/apertium/svn/branches/courses/helsinki_2013/slides/session2b.pdf)
* [Morphological and syntactic disambiguation](https://svn.code.sf.net/p/apertium/svn/branches/courses/helsinki_2013/slides/session3.pdf)
* [Lexical transfer](https://svn.code.sf.net/p/apertium/svn/branches/courses/helsinki_2013/slides/session4.pdf)
* [Lexical selection](https://svn.code.sf.net/p/apertium/svn/branches/courses/helsinki_2013/slides/session4.pdf)
* [Basic structural transfer](https://svn.code.sf.net/p/apertium/svn/branches/courses/helsinki_2013/slides/session5.pdf)
* [Multi-level structural transfer](https://svn.code.sf.net/p/apertium/svn/branches/courses/helsinki_2013/slides/session6.pdf)

##### Assignment:
1. Write a program that performs morphological analysis of Kazakh noun cases (Each student must choose different words)
2. Write a program that performs morphological generation of Kazakh noun cases (Each student must choose different words)

#### 2.3 Overview of resources needed for RBMT
* [Some general resources](http://wiki.apertium.org/wiki/Resources)
* [Some resources for Kazakh](http://wiki.apertium.org/wiki/Kazakh)
* [Data consistency and quality](https://svn.code.sf.net/p/apertium/svn/branches/courses/helsinki_2013/slides/session7a.pdf)
* [Evaluation of machine translation](https://svn.code.sf.net/p/apertium/svn/branches/courses/helsinki_2013/slides/session7b.pdf)

##### Assignment:
1. Find linguistic resources for Kazakh and analyze how they can be improved. (Each student must choose different resource)

#### 2.4 Apertium machine translation platform
* [The Apertium machine-translation platform](https://svn.code.sf.net/p/apertium/svn/branches/courses/helsinki_2013/slides/session0a.pdf)
* [Apertium workflow diagram](http://wiki.apertium.org/wiki/Workflow_diagram)
* [Apertium workflow reference](http://wiki.apertium.org/wiki/Workflow_reference)
* [Apertium documentation](http://wiki.apertium.org/wiki/Documentation)

##### Assignment:
1. Install Apertium and create a new "dummy" language pair using instructions: https://wiki.apertium.org/wiki/Apertium_New_Language_Pair_HOWTO and https://wiki.apertium.org/wiki/Руководство_по_созданию_новой_языковой_пары.

### 3. Statistical machine translation

#### 3.1 Basic concepts of SMT
* [Statistical MT Handbook by Kevin Knight](http://www.isi.edu/natural-language/mt/wkbk.rtf)
* [SMT Tutorial by Kevin Knight and Philipp Koehn](http://people.csail.mit.edu/people/koehn/publications/tutorial2003.pdf)

##### Assignment:
1. Collect Kazakh-English parallel corpora (at least 500 sentences) from governmental web sites. (Each student must have unique sentences)

#### 3.2 SMT models
* [Word-Based Models](http://statmt.org/book/slides/04-word-based-models.pdf)
* [Phrase-Based Models](http://statmt.org/book/slides/05-phrase-based-models.pdf)
* [Decoding](http://statmt.org/book/slides/06-decoding.pdf)
* [Language Models](http://statmt.org/book/slides/07-language-models.pdf)
* [Tree-Based Models](http://statmt.org/book/slides/11-tree-based-models.pdf)

#### 3.3 Overview of resources needed for SMT
* [Europarl Corpus](http://statmt.org/europarl/)
* [News Commentary Corpus](http://www.casmacat.eu/corpus/news-commentary.html)
* [Evaluation](http://statmt.org/book/slides/08-evaluation.pdf)

##### Assignment:
1. Install Moses (http://www.statmt.org/moses/?n=Development.GetStarted) and train a baseline machine translation system using collected parallel data and instructions: http://www.statmt.org/moses/?n=Moses.Baseline

#### 3.4 Moses statistical machine translation system
* [Moses, a complete SMT system](http://statmt.org/moses/)
* [Baseline System](http://www.statmt.org/moses/?n=Moses.Baseline)
* [Phrase-based Tutorial](http://www.statmt.org/moses/?n=Moses.Tutorial)
* [Syntax Tutorial](http://www.statmt.org/moses/?n=Moses.SyntaxTutorial)
* [Tutorial for Using Factored Models](http://www.statmt.org/moses/?n=Moses.FactoredTutorial)
* [Optimizing Moses](http://www.statmt.org/moses/?n=Moses.Optimize)

##### Assignment:
1. Study BLUE evaluation metric (https://machinelearningmastery.com/calculate-bleu-score-for-text-python/, https://towardsdatascience.com/evaluating-text-output-in-nlp-bleu-at-your-own-risk-e8609665a213) and apply it to your trained baseline machine translation systems

### 4. Neural machine translation
* [Deep learning на пальцах](https://dlcourse.ai/)
* [fast.ai](https://www.fast.ai/)

#### 4.1 Basic concepts of NMT
* [Intro to Language Modeling](https://www.youtube.com/watch?v=PNNHaQUQqW8&list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9&index=12&t=0s)
* [Transfer learning for NLP](https://www.youtube.com/watch?v=5gCQvuznKn0&list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9&index=10&t=0s)

##### Assignment:
1. Collect more Kazakh-English parallel corpora (at least 500 sentences more) from governmental web sites. (Each student must have unique sentences)

#### 4.2 NMT models
* [NLP; Tabular data; Collaborative filtering; Embeddings](https://course.fast.ai/videos/?lesson=4)
* [Введение в NLP, word2vec](https://youtu.be/MBQdMQUZMQM)
* [Attention](https://www.youtube.com/watch?v=IfsjMg4fLWQ&list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9&index=12)
* [Transformer](https://www.youtube.com/watch?v=AFkGPmU16QA&list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9&index=17)
* [Understanding RNNs](https://www.youtube.com/watch?v=l1rlFh0PmZw&list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9&index=9&t=0s)
* [Translation with Seq2Seq](https://www.youtube.com/watch?v=IfsjMg4fLWQ&list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9&index=8&t=0s)
* [Introduction to the Transformer](https://www.youtube.com/watch?v=AFkGPmU16QA&list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9&index=3&t=0s)
* [The Transformer for Language Translation](https://www.youtube.com/watch?v=KzfyftiH7R8&list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9&index=18)

##### Assignment:
1. Install TensorFlow (https://www.tensorflow.org/install) and train a neural machine translation system with attention using collected parallel data and instructions: https://www.tensorflow.org/tutorials/text/nmt_with_attention

#### 4.3 Overview of resources needed for NMT
* [Europarl Corpus](http://statmt.org/europarl/)
* [News Commentary Corpus](http://www.casmacat.eu/corpus/news-commentary.html)
* [Evaluation](http://statmt.org/book/slides/08-evaluation.pdf)

#### 4.4 TensorFlow Neural Machine Translation Tutorial
* [Neural machine translation with attention](https://www.tensorflow.org/tutorials/text/nmt_with_attention)
* [Transformer model for language understanding](https://www.tensorflow.org/tutorials/text/transformer)

##### Assignment:
1. Evaluate the quality of your trained neural machine translation system using BLUE

### 5. Hybrid machine translation. Applications of Machine Translation.
* [Assimilation and Dissemination](http://wiki.apertium.org/wiki/Assimilation_and_Dissemination)

## Recommended Bibliography

* D.Jurafsky, J.H. Martin. Speech and Language Processing, 2nd Edition. Prentice Hall. - 2008. - 1032 P.
* D.Jurafsky, J.H. Martin. Speech and Language Processing (3rd ed. draft). [https://web.stanford.edu/~jurafsky/slp3/](https://web.stanford.edu/~jurafsky/slp3/)
* Apertium 2.0: Official documentation. [http://wiki.apertium.org/wiki/Documentation](http://wiki.apertium.org/wiki/Documentation)
* P.Koehn. Statistical Machine Translation. 1st Edition. Cambridge University Press. - 2010. - 446 P.
* Moses User Manual and Code Guide. [http://www.statmt.org/moses/manual/manual.pdf](http://www.statmt.org/moses/manual/manual.pdf)
* TensorFlow tutorials [https://www.tensorflow.org/tutorials/](https://www.tensorflow.org/tutorials/)
* Sergei Nirenburg, Harold Somers, Yorik Wilks (2003) Readings in machine translation / Sydney M. Lamb On the Mechanization of syntactic analysis. Lamb-P, 430
