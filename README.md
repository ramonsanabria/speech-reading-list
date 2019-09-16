# Speech Resource List

This resource list is mantained by [Ramon Sanabria](http://www.cs.cmu.edu/~ramons/), [Edinburgh NLP](https://edinburghnlp.inf.ed.ac.uk/) and [The Centre for Speech Technology Research](http://www.cstr.ed.ac.uk/), [The University of Edinburgh](https://www.ed.ac.uk/). Ex [Language Technologies Institute](https://www.lti.cs.cmu.edu/) and [Robotics Institute](https://www.ri.cmu.edu/), [CMU](https://www.cmu.edu/). 

This list is probably biased towards my current research directions. So, please, if there is anythin missing, please let me know. Suggestions are super welcome :)

<h1 id="content_table">Content Table</h1>

* [Papers](#papers)
* [Tutorials](#tutorials)
* [Courses](#courses)
* [Journals](#journals)
* [Workshops](#workshops)
* [Datasets](#datasets)

<h1 id="papers">Papers</h1>

* [Multimodal](#multimodal)
	* [Adaptation](#multimodal_adaptation)
	* [Representation](#multimodal_adaptation)
	* [Unsupervised](#multimodal_unsupervised)
	* [Other](#multimodal_other)

* [Unsupervised](#unsupervised)
	* [Segmentation](#unsupervised_segmentation)
	* [Representation](#unsupervised_representation)
		* [High-level Representation](#unsupervised_representation_highlevel)
		* [Low-level Representation](#unsupervised_representation_lowlevel)
	* [Other](#unsupervised_other)

* [Supervised](#supervised)
	* [Acoustic Modeling](#supervised_am)

<h2 id="multimodal">Multimodal</h2>
<h3 id="multimodal_adaptation">Adaptation</h2>

* Moriya Y, Jones GJ. [Multimodal Speaker Adaptation of Acoustic Model and Language Model for Asr Using Speaker Face Embedding.](https://ieeexplore.ieee.org/abstract/document/8683724) **ICASSP 2019** 
* Caglayan O, Sanabria R, Palaskar S, Barraul L, Metze F. [Multimodal Grounding for Sequence-to-sequence Speech Recognition.](https://arxiv.org/pdf/1811.03865.pdf) **ICASSP 2019**
* Palaskar S, Sanabria R, Metze F. [End-to-end multimodal speech recognition.](https://arxiv.org/abs/1804.09713) **ICASSP 2018**
* Gupta A, Miao Y, Neves L, Metze F. [Visual features for context-aware speech recognition.](https://arxiv.org/abs/1712.00489) **ICASSP 2017** 
* Sun F, Harwath D, Glass J. [Look, Listen, And Decode: Multimodal Speech Recognition With Images.](https://groups.csail.mit.edu/sls/publications/2016/FelixSun_SLT_2016.pdf) **ICASSP 2016**

<h3 id="multimodal_representation">Representation</h2>

* Pasad, Ankita, et al. [On the Contributions of Visual and Textual Supervision
in Low-Resource Semantic Speech Retrieval](https://arxiv.org/pdf/1904.10947.pdf) **INTERSPEECH 2019**
* Owens A, Wu J, McDermott JH, Freeman WT, Torralba A. [Learning sight from sound: Ambient sound provides supervision for visual learning.](https://arxiv.org/pdf/1712.07271.pdf) **IJCV 2018**


<h3 id="multimodal_unsupervised">Unsupervised</h2>

* Kamper H, Settle S, Shakhnarovich G, Livescu K. [Visually grounded learning of keyword prediction from untranscribed speech.](https://arxiv.org/pdf/1703.08136.pdf) **INTERSPEECH 2017**

<h3 id="multimodal_other">Other (maybe not speech, but still relevant)</h2>

* Shi H, Mao J, Gimpel K, Livescu K. [Visually Grounded Neural Syntax Acquisition.](https://arxiv.org/pdf/1906.02890.pdf) **arxiv**
* Caglayan O, Madhyastha P, Specia L, Barrault L. [Probing the Need for Visual Context in Multimodal Machine Translation](https://arxiv.org/abs/1903.08678) **NAACL 2019**



<h2 id="unsupervised">Unsupervised</h2>
<h3 id="unsupervised_segmentation">Segmentation</h2>

* Kamper H, Jansen A, Goldwater S. [Fully unsupervised small-vocabulary speech recognition using a segmental bayesian model.](https://pdfs.semanticscholar.org/26f5/b704a3f1e0d8d7187c048ca48630553684b6.pdf) **INTERSPEECH 2015**


<h3 id="unsupervised_representation">Representation</h3>

<h4 id="unsupervised_representation_highlevel">High-level Representation</h4>

* Kamper H, Jansen A, King S, Goldwater S. [Unsupervised lexical clustering of speech segments using fixed-dimensional acoustic embeddings.](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.724.7106&rep=rep1&type=pdf) **SLT 2014**

<h4 id="unsupervised_representation_lowlevel">Low-level Representation</h4>


* Chung YA, Hsu WN, Tang H, Glass J. [An unsupervised autoregressive model for speech representation learning.](https://arxiv.org/abs/1904.03240) **INTERSPEECH 2019**
* Pascual S, Ravanelli M, Serrà J, Bonafonte A, Bengio Y. [Learning problem-agnostic speech representations from multiple self-supervised tasks.](https://arxiv.org/pdf/1904.03416.pdf) **INTERSPEECH 2019**

<h3 id="unsupervised_other">Other (maybe not speech, but still relevant)</h2>

* Kawakami, K., Dyer, C. and Blunsom, P. [Learning to Discover, Ground and Use Words with Segmental Neural Language Models.](https://www.aclweb.org/anthology/P19-1645) **ACL 2019**
* Kawakami, K., Dyer, C. and Blunsom, P. [Unsupervised Word Discovery with Segmental Neural Language Models](https://arxiv.org/pdf/1811.09353.pdf) **ACL 2019**

<h2 id="supervised">Supervised</h2>
<h3 id="supervised_am">Acoustic Modeling</h2>
<h4 id="supervised_am">Transformer-like</h2>

* Dong L, Xu S, Xu B. [Speech-transformer: a no-recurrence sequence-to-sequence model for speech recognition](http://150.162.46.34:8080/icassp2018/ICASSP18_USB/pdfs/0005884.pdf) **ICASSP 2018**
* Sperber, M., Niehues, J., Neubig, G., Stüker, S., Waibel, A. [Self-Attentional Acoustic Models](http://msperber.com/research/pdf/Sperber-Interspeech2018-SelfAttentionalAM.pdf) **INTERSPEECH 2018**
* Zhou S, Dong L, Xu S, Xu B. [Syllable-Based Sequence-to-Sequence Speech Recognition with the Transformer in Mandarin Chinese](https://arxiv.org/pdf/1804.10752.pdf) **INTERSPEECH 2018**

<h4 id="supervised_am">Pretraining</h2>

* Wiesner M, Renduchintala A, Watanabe S, Liu C, Dehak N, Khudanpur S. [Pretraining by Backtranslation for End-to-end ASR in Low-Resource Settings](https://arendu.github.io/images/PSDA_MMDA.pdf) **INTERSPEECH 2019**
* Bansal S, Kamper H, Livescu K, Lopez A, Goldwater S. [Pre-training on high-resource speech recognition improves low-resource speech-to-text translation](https://arxiv.org/pdf/1809.01431.pdf). **NAACL 2019**


<h4 id="supervised_am">Augmentation</h2>

* Park DS, Chan W, Zhang Y, Chiu CC, Zoph B, Cubuk ED, Le QV. [SpecAugment: A Simple Data Augmentation Method for Automatic Speech Recognition
](https://arxiv.org/pdf/1904.08779.pdf) **INTERSPEECH 2019**



<h1 id="tutorials">Tutorials</h1>

<h1 id="courses">Courses</h1>

* [The University of Edinburgh, AUTOMATIC SPEECH RECOGNITION.](http://www.inf.ed.ac.uk/teaching/courses/asr/lectures-2019.html)

<h1 id="journals">Journals</h1>

<h1 id="workshops">Workshops</h1>


<h1 id="datasets">Datasets</h1>

* Great resource from [@_josh_meyer_](https://twitter.com/_josh_meyer_) [here](https://github.com/JRMeyer/open-speech-corpora)
* Sanabria R, Caglayan O, Palaskar S, Elliott D, Barrault L, Specia L, Metze F. [How2: a large-scale dataset for multimodal language understanding.](https://arxiv.org/pdf/1811.00347.pdf). **NIPS 2018 Workshop**


