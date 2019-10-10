# Speech Resource List 
This resource list is mantained by [Ramon Sanabria](http://www.cs.cmu.edu/~ramons/), [Edinburgh NLP](https://edinburghnlp.inf.ed.ac.uk/) and [The Centre for Speech Technology Research](http://www.cstr.ed.ac.uk/), [The University of Edinburgh](https://www.ed.ac.uk/). Ex [Language Technologies Institute](https://www.lti.cs.cmu.edu/) and [Robotics Institute](https://www.ri.cmu.edu/), [CMU](https://www.cmu.edu/). 

This list is probably biased towards my current research directions. So, please, if there is anythin missing, please let me know. Suggestions are super welcome :)

<h1 id="content_table">Content Table</h1>

* [Papers](#papers)
	* [Speech Processing and Recognition](#papers_asr)
	* [Speech Translation](#papers_st)
	* [Machine Translation](#papers_mt)
	* [Others](#papers_others)
* [Tutorials](#tutorials)
* [Courses](#courses)
* [Journals](#journals)
* [Datasets](#datasets)

<h1 id="papers">Papers</h1>
<h2 id="papers_asr">Speech Processing and Recognition</h2>


* [Unsupervised](#papers_asr_unsupervised)
	* [Segmentation](#papers_asr_unsupervised_segmentation)
	* [Representation](#papers_asr_unsupervised_representation)
		* [High-level Representation](#papers_asr_unsupervised_representation_highlevel)
		* [Low-level Representation](#papers_asr_unsupervised_representation_lowlevel)

* [Supervised](#papers_asr_supervised)
	* [Acoustic Modelling](#papers_asr_supervised_am)
		* [Transformer_like](#papers_asr_supervised_am_transformerlike)
		* [Pretraining](#papers_asr_supervised_am_pretraining)
		* [Augmentation](#papers_asr_supervised_am_augmentation)
	* [Language Modelling](#papers_asr_supervised_lm)
		* [Transformer_like](#papers_asr_supervised_lm_transformerlike)
	* [End-to-End](#papers_asr_supervised_e2e)

* [Zero-shot](#papers_asr_zeroshot)
	* [Acoustic Modelling](#papers_asr_zeroshot_am)
	* [Keyword Spotting](#papers_asr_zeroshot_keywordspotting)
	
* [Multimodal](#papers_asr_multimodal)
	* [Adaptation](#papers_asr_multimodal_adaptation)
	* [Representation](#papers_asr_multimodal_adaptation)
	* [Unsupervised](#papers_asr_multimodal_unsupervised)
	* [Zero-shot](#papers_asr_multimodal_zeroshot)
		* [Acoustic Modelling](#papers_asr_multimodal_zeroshot_am)
		* [Key-word Spottig](#papers_asr_zeroshot_keywordspotting)



<h3 id="papers_asr_unsupervised">Unsupervised</h3>
<h3 id="papers_asr_unsupervised_segmentation">Segmentation</h3>

* Kamper H, Jansen A, Goldwater S. [Fully unsupervised small-vocabulary speech recognition using a segmental bayesian model](https://pdfs.semanticscholar.org/26f5/b704a3f1e0d8d7187c048ca48630553684b6.pdf) **INTERSPEECH 2015**


<h4 id="papers_asr_unsupervised_representation">Representation</h4>

<h5 id="papers_asr_unsupervised_representation_highlevel">High-level Representation</h5>

* Kamper H, Jansen A, King S, Goldwater S. [Unsupervised lexical clustering of speech segments using fixed-dimensional acoustic embeddings.](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.724.7106&rep=rep1&type=pdf) **SLT 2014**

<h5 id="papers_asr_unsupervised_representation_lowlevel">Low-level Representation</h5>


* Oord AV, Li Y, Vinyals O. [Representation learning with contrastive predictive coding](https://arxiv.org/pdf/1807.03748.pdf) **NIPS 2019**
* Chung YA, Hsu WN, Tang H, Glass J. [An unsupervised autoregressive model for speech representation learning](https://arxiv.org/abs/1904.03240) **INTERSPEECH 2019**
* Pascual S, Ravanelli M, Serrà J, Bonafonte A, Bengio Y. [Learning problem-agnostic speech representations from multiple self-supervised tasks](https://arxiv.org/pdf/1904.03416.pdf) **INTERSPEECH 2019**


<h3 id="papers_asr_supervised">Supervised</h3>
<h4 id="papers_asr_supervised_am">Acoustic Modelling</h4>
<h5 id="papers_asr_supervised_am_transformerlike">Transformer-like</h5>

* Dong L, Xu S, Xu B. [Speech-transformer: a no-recurrence sequence-to-sequence model for speech recognition](http://150.162.46.34:8080/icassp2018/ICASSP18_USB/pdfs/0005884.pdf) **ICASSP 2018**
* Sperber, M., Niehues, J., Neubig, G., Stüker, S., Waibel, A. [Self-Attentional Acoustic Models](http://msperber.com/research/pdf/Sperber-Interspeech2018-SelfAttentionalAM.pdf) **INTERSPEECH 2018**
* Zhou S, Dong L, Xu S, Xu B. [Syllable-Based Sequence-to-Sequence Speech Recognition with the Transformer in Mandarin Chinese](https://arxiv.org/pdf/1804.10752.pdf) **INTERSPEECH 2018**

<h4 id="papers_asr_supervised_am_pretraining">Pretraining</h4>

* Wiesner M, Renduchintala A, Watanabe S, Liu C, Dehak N, Khudanpur S. [Pretraining by Backtranslation for End-to-end ASR in Low-Resource Settings](https://arendu.github.io/images/PSDA_MMDA.pdf) **INTERSPEECH 2019**


<h4 id="papers_asr_supervised_am_augmentation">Augmentation</h4>

* Park DS, Chan W, Zhang Y, Chiu CC, Zoph B, Cubuk ED, Le QV. [SpecAugment: A Simple Data Augmentation Method for Automatic Speech Recognition
](https://arxiv.org/pdf/1904.08779.pdf) **INTERSPEECH 2019**


<h4 id="papers_asr_supervised_e2e">End-to-end</h4>

* Baskar MK, Burget L, Watanabe S, Karafiát M, Hori T, Černocký JH. [Promising Accurate Prefix Boosting for sequence-to-sequence ASR](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8682782) **ICASSP 2019**
* Collobert R, Hannun A, Synnaeve G. [A fully differentiable beam search decoder](https://arxiv.org/pdf/1902.06022.pdf) **arxiv 2019**





<h3 id="papers_asr_zeroshot">Zero-shot</h3>


* Prasad M, van Esch D, Ritchie S, Mortensen JF. [Building Large-Vocabulary ASR Systems for Languages Without Any Audio Training Data](https://www.isca-speech.org/archive/Interspeech_2019/pdfs/1775.pdf)
**INTERSPEECH 2019**


<h4 id="papers_asr_zeroshot_keywordspotting">Keyword Spotting</h4>

* Menon R, Kamper H, van der Westhuizen E, Quinn J, Niesler T. [Feature exploration for almost zero-resource ASR-free keyword spotting using a multilingual bottleneck extractor and correspondence autoencoders](https://www.isca-speech.org/archive/Interspeech_2019/pdfs/1665.pdf) **INTERSPEECH 2019**



<h3 id="papers_asr_multimodal">Multimodal</h3>
<h4 id="papers_asr_multimodal_adaptation">Adaptation</h4>

* Moriya Y, Jones GJ. [Multimodal Speaker Adaptation of Acoustic Model and Language Model for Asr Using Speaker Face Embedding](https://ieeexplore.ieee.org/abstract/document/8683724) **ICASSP 2019** 
* Caglayan O, Sanabria R, Palaskar S, Barraul L, Metze F. [Multimodal Grounding for Sequence-to-sequence Speech Recognition](https://arxiv.org/pdf/1811.03865.pdf) **ICASSP 2019**
* Palaskar S, Sanabria R, Metze F. [End-to-end multimodal speech recognition](https://arxiv.org/abs/1804.09713) **ICASSP 2018**
* Gupta A, Miao Y, Neves L, Metze F. [Visual features for context-aware speech recognition](https://arxiv.org/abs/1712.00489) **ICASSP 2017** 
* Sun F, Harwath D, Glass J. [Look, Listen, And Decode: Multimodal Speech Recognition With Images](https://groups.csail.mit.edu/sls/publications/2016/FelixSun_SLT_2016.pdf) **ICASSP 2016**

<h4 id="papers_asr_multimodal_representation">Representation</h4>

* Pasad, Ankita, et al. [On the Contributions of Visual and Textual Supervision
in Low-Resource Semantic Speech Retrieval](https://arxiv.org/pdf/1904.10947.pdf) **INTERSPEECH 2019**
* Owens A, Wu J, McDermott JH, Freeman WT, Torralba A. [Learning sight from sound: Ambient sound provides supervision for visual learning.](https://arxiv.org/pdf/1712.07271.pdf) **IJCV 2018**


<h4 id="papers_asr_multimodal_unsupervised">Unsupervised</h4>

* Kamper H, Settle S, Shakhnarovich G, Livescu K. [Visually grounded learning of keyword prediction from untranscribed speech](https://arxiv.org/pdf/1703.08136.pdf) **INTERSPEECH 2017**

<h4 id="multimodal_other">Other (maybe not speech, but still relevant)</h2>

* Shi H, Mao J, Gimpel K, Livescu K. [Visually Grounded Neural Syntax Acquisition](https://arxiv.org/pdf/1906.02890.pdf) **arxiv 2019**
* Caglayan O, Madhyastha P, Specia L, Barrault L. [Probing the Need for Visual Context in Multimodal Machine Translation](https://arxiv.org/abs/1903.08678) **NAACL 2019**


<h2 id="papers_st">Speech Translation</h2>

* [Supervised](#papers_st_supervised)
* [Unsupervised](#papers_st_unsupervised)

<h3 id="papers_st">Supervised</h3>

* Inaguma H, Duh K, Kawahara T, Watanabe S. [Multilingual End-to-End Speech Translation](https://arxiv.org/pdf/1910.00254.pdf) **arXiv 2019**
* Bansal S, Kamper H, Livescu K, Lopez A, Goldwater S. [Pre-training on high-resource speech recognition improves low-resource speech-to-text translation](https://arxiv.org/pdf/1809.01431.pdf). **NAACL 2019**

<h3 id="papers_st_unsupervised">Unsupervised</h3>

* Chung YA, Weng WH, Tong S, Glass J. [Towards unsupervised speech-to-text translation](https://arxiv.org/pdf/1811.01307.pdf) **ICASSP 2019** 


<h2 id="papers_others">Others</h2>

* [Unsupervised](#papers_others_unsupervised)
* [Computer Vision](#papers_others_cv)


<h3 id="papers_other_unsupervised">Unsupervised</h3>

* Kawakami, K., Dyer, C. and Blunsom, P. [Learning to Discover, Ground and Use Words with Segmental Neural Language Models](https://www.aclweb.org/anthology/P19-1645) **ACL 2019** * Kawakami, K., Dyer, C. and Blunsom, P. [Unsupervised Word Discovery with Segmental Neural Language Models](https://arxiv.org/pdf/1811.09353.pdf) **ACL 2019**

<h3 id="papers_other_cv">Computer Vision</h3>


* Mahajan D, Girshick R, Ramanathan V, He K, Paluri M, Li Y, Bharambe A, van der Maaten L. [Exploring the limits of weakly supervised pretraining](http://openaccess.thecvf.com/content_ECCV_2018/papers/Dhruv_Mahajan_Exploring_the_Limits_ECCV_2018_paper.pdf) **EECV 2018**
* Patterson G, Hays J. [Coco attributes: Attributes for people, animals, and objects](http://cs.brown.edu/~gmpatter/pub_papers/coco_attributes.pdf)  **EECV 2016**

(http://cs.brown.edu/~gmpatter/pub_papers/coco_attributes.pdf)


<h1 id="courses">Courses</h1>


* [The University of Edinburgh, AUTOMATIC SPEECH RECOGNITION](http://www.inf.ed.ac.uk/teaching/courses/asr/lectures-2019.html)

<h1 id="journals">Journals</h1>



<h1 id="datasets">Datasets</h1>

* [Speech Recognition](#datasets_asr)
	* [Low-Resource](#datasets_asr_lowresource)
* [Speech To Translation](#datasets_st)
	* [Low-Resource](#datasets_st_lowresource)
	* [High-Resource](#datasets_st_highresource)
* [Machine Translation](#datasets_mt)
	* [Low-Resource](#datasets_mt_lowresource)
	* [High-Resource](#datasets_mt_highresource)
* [Multimodal](#datasets_multimodal)
* [Other](#datasets_other)

<h2 id="datasets_asr">Speech Recognition</h2>

<h3 id="datasets_asr_lowresource">Low Resource</h3>

* Black AW. [CMU Wilderness Multilingual Speech Dataset.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8683536) **ICASSP 2019**

<h2 id="datasets_st">Speech To Translation</h2>

<h3 id="datasets_st_lowresource">Low Resource</h3>

* Boito MZ, Havard WN, Garnerin M, Ferrand ÉL, Besacier L. [MaSS: A Large and Clean Multilingual Corpus of Sentence-aligned Spoken Utterances Extracted from the Bible.](https://arxiv.org/pdf/1907.12895.pdf) **arXiv 2019**
* Godard P, Adda G, Adda-Decker M, Benjumea J, Besacier L, Cooper-Leavitt J, Kouarata GN, Lamel L, Maynard H, Müller M, Rialland A. [A very low resource language speech corpus for computational language documentation experiments.](https://arxiv.org/abs/1710.03501) **LREC 2018**

<h3 id="datasets_st_highresource">High Resource</h3>

* Di Gangi MA, Cattoni R, Bentivogli L, Negri M, Turchi M. [MuST-C: a Multilingual Speech Translation Corpus.](https://www.aclweb.org/anthology/N19-1202) **NAACL 2019** 
* Salesky E, Burger S, Niehues J, Waibel A. [Towards fluent translations from disfluent speech.](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8639661) **SLT 2018**
* Post M, Kumar G, Lopez A, Karakos D, Callison-Burch C, Khudanpur S. [Improved speech-to-text translation with the Fisher and Callhome Spanish–English speech translation corpus.](http://www.mt-archive.info/10/IWSLT-2013-Post.pdf) **IWSLT 2013**


<h2 id="datasets_st">Machine Translation</h2>

<h3 id="datasets_lowresource">Low Resource</h3>

* Guzmán F, Chen PJ, Ott M, Pino J, Lample G, Koehn P, Chaudhary V, Ranzato MA. [Two new evaluation datasets for low-resource machine translation: Nepali-English and Sinhala-English](https://arxiv.org/pdf/1811.00347.pdf) **EMNLP 2019**


<h2 id="datasets_multimodal">Multimodal</h1>

* Sanabria R, Caglayan O, Palaskar S, Elliott D, Barrault L, Specia L, Metze F. [How2: a large-scale dataset for multimodal language understanding](https://arxiv.org/pdf/1811.00347.pdf) **NIPS 2018 Workshop**

<h2 id="datasets_other">Other</h1>

* Great resource from [@_josh_meyer_](https://twitter.com/_josh_meyer_) [here](https://github.com/JRMeyer/open-speech-corpora)
* Great collection of video datasets [here](https://www.di.ens.fr/~miech/datasetviz/)

