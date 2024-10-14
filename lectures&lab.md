# Lectures & Lab

![alt text](Images/Planning.jpg "Schedule")

## Monday the 21st of October

* 9:45 AM - 11:45 AM: **TBA**<br/>
_Alasdair Newson_<br/>
TBA

* 2:00 PM - 4:00 PM: **Score based denoising diffusion: An introduction**<br/>
_Eric Moulines_ <br/>
TBA

* 4:30 PM - 6:00 PM: **Unveiling the Mechanisms Behind Diffusion Models with Applications to Image Restoration** <br/>
_Badr Moufad et Yazid Janati_<br/>
Diffusion Models (DMs) have impressively pervaded the field of generative modeling. They rapidly gained prominence thanks to their remarkable ability to model complex and multi-modal patterns. More importantly, the potential of DMs go beyond mere data generation. For instance, they are viable zero-shorts learner that can be used to solve downstream tasks without further training.
This practical session will be split into two parts. In the first, we will demystify the foundational aspects of DMs. Using a simple example of 2D points, we will understand key components of a DMs, their interplay, and practical implementation. In the second part, we will explore one among the interesting applications of DMs: solving Bayesian inverse problems. We will look at how we can leverage DMs to solve challenging image restoration problems, such image colorization, Super Resolution, without additional training. <br/>
Outline.
    * Training score-based diffusion model from first principles
      * Dataset, architecture, training objective: what you need to know
      * Sampling schemes: generating new data samples
      * Extension to conditional diffusion models
    * Zero-shot learning with diffusion models priors
      * Preliminary: Bayesian inverse problems
      * Diffusion model posterior samplers
      * Image restoration via diffusion models priors



## Tuesday the 22nd of October



* 9:00 AM - 10:30 AM: **Reinforcement from human feedback: Some theory and practice**, <br/>
_Yunhao Tang_<br/>
Reinforcement learning from human feedback (RLHF) is a major paradigm for the alignment of large language models. In this session, we will go through the basics of RLHF: the basic setup and background on RL, reward and preference models, the online and offline approaches to RLHF, their extensions and limitations. The theoretical discussion will be complemented by a practical session that hinges on the fundamentals.


* 11:00 AM - 12:30 AM: **Reinforcement from human feedback: Some theory and practice**, <br/>
_Yunhao Tang_<br/>
Reinforcement learning from human feedback (RLHF) is a major paradigm for the alignment of large language models. In this session, we will go through the basics of RLHF: the basic setup and background on RL, reward and preference models, the online and offline approaches to RLHF, their extensions and limitations. The theoretical discussion will be complemented by a practical session that hinges on the fundamentals.


* 2:00 PM - 3:30 PM: **How to train a LLM in 2024**, <br/>
_Manuel Faysse_<br/>
In this talk, we will explore large language model pretraining through the concrete example of CroissantLLM, a small bilingual english-french language model released at the beginning of the year. <br>
This will enable us to dive into various topics such as model architectures, scaling laws, data collection, tokenization, instruction-tuning...<br>
In a constantly evolving field, we will finally reflect upon where future developments are heading.<br>

* 4:00 PM - 5:30 PM: **How to train a LLM in 2024**, <br/>
_Manuel Faysse_<br/>
In this talk, we will explore large language model pretraining through the concrete example of CroissantLLM, a small bilingual english-french language model released at the beginning of the year. <br>
This will enable us to dive into various topics such as model architectures, scaling laws, data collection, tokenization, instruction-tuning...<br>
In a constantly evolving field, we will finally reflect upon where future developments are heading.<br>


## Wednesday the 23rd of October

* 9:00 AM - 11:00 AM: **Probabilistic generative models for audio-visual processing**, <br/>
_Xavier Alameda-Pineda_<br/>
In this talk, we will start with an overly-used old-timer: the expected-complete data log-likelihood. We will demonstrate the interest of this object for learning with latent variables, and showcase it with a few basic probabilistic models. We will move on to discuss more complex shallow models for audio-visual fusion, and quickly move on to neural models to process auditory and visual data, either in sequences or frame-wise. We will end up demonstrating the interest of this framework with more recent generative models. Applications will range from tracking, to speech enhancement, as well as motion prediction.

* 2:00 PM - 3:30 PM: **Large Language Models: The Falcon case study**, <br/>
  _Merouane Debbah_<br/>
Reinforcement learning from human feedback (RLHF) is a major paradigm for the alignment of large language models. In this session, we will go through the basics of RLHF: the basic setup and background on RL, reward and preference models, the online and offline approaches to RLHF, their extensions and limitations. The theoretical discussion will be complemented by a practical session that hinges on the fundamentals.


* 4:00 PM - 5:30 PM: **Confronting Climate Change with Generative and Self-supervised Machine Learning**, <br/>
_Claire Monteleoni_<br/>
The stunning recent advances in AI chatbots rely on cutting-edge generative deep learning algorithms and architectures trained on massive amounts of text data. Generative deep learning has also shown remarkable results when trained on video data and on combinations of different data types (i.e., multi-modal). The recent advances in generative deep learning can also benefit a variety of applications for addressing climate change. For example, generative deep learning trained on climate and weather data can be a powerful tool in generating an ensemble of weather predictions and in quantifying the uncertainty of long-term projections of climate change. 
As opposed to text and video, the relevant training data for this domain includes weather and climate data from observations, reanalyses, and even physical simulations. As in many massive data applications, creating “labeled data” for supervised machine learning is often costly, time-consuming, or even impossible. Fortuitously, in very large-scale data domains, “self-supervised” machine learning methods are now actually outperforming supervised learning methods. In this lecture, I will survey our lab’s work on developing generative and self-supervised machine learning approaches for applications addressing climate change, including detection and prediction of extreme weather events, and downscaling and temporal interpolation of spatiotemporal data. Our methods address problems such as forecasting the path and intensity of tropical cyclones, renewable energy planning, and projecting future sea-level rise.

## Thursday the 24th of October

* 9:00 AM - 10:30 AM: **Environmental and Societal impacts of (generative) AI**, <br/>
_Denis Trystram_<br/>
In this talk, we will start with an overly-used old-timer: the expected-complete data log-likelihood. We will demonstrate the interest of this object for learning with latent variables, and showcase it with a few basic probabilistic models. We will move on to discuss more complex shallow models for audio-visual fusion, and quickly move on to neural models to process auditory and visual data, either in sequences or frame-wise. We will end up demonstrating the interest of this framework with more recent generative models. Applications will range from tracking, to speech enhancement, as well as motion prediction.

* 2:00 PM - 3:30 PM: **A primer on physics-informed learning**, <br/>
 _Claire Boyer_<br/>
Physics-informed machine learning combines the expressiveness of data-based approaches with the interpretability of physical models. In this context, we consider a general regression problem where the empirical risk is regularized by a partial differential equation that quantifies the physical inconsistency. Practitioners often resort to physics-informed neural networks (PINNs) to solve this kind of problem. After discussing some strengths and limitations of PINNs, we prove that for linear differential priors, the problem can be formulated directly as a kernel regression task, giving a rigorous framework to analyze physics-informed ML. In particular, the physical prior can help in boosting the estimator convergence. We also propose the PIKL algorithm (PIKL for physics-informed kernel learning) as a numerical strategy to implement this kernel method.

* 4:00 PM - 5:30 PM: **Audio Generative AI**, <br/>
_Gael Richard_<br/>
In this talk, we will present the recent progresses in audio generative AI. After a short introduction recalling the specificities of an audio signal, we will introduce some of the most important architectures of deep neural audio synthesis models. We will also briefly discuss some of the existing strategies for cross-modal audio generation and illustrate the potential of model-based (or hybrid) deep learning  for audio generative AI.


* 4:00 PM - 5:30 PM: **TBA**, <br/>
_TBA_<br/>
TBA


## Friday the 25th of October


* 9:00 AM - 10:30 AM: **TBA**, <br/>
_Antoine Bossulet_<br/>
TBA

* 11:00 AM - 12:30 AM: **TBA**, <br/>
 _Vicky Kalogeiton_<br/>
TBA
* 2:00 PM - 3:30 PM: **TBA**, <br/>
_Xi Wang_<br/>
TBA
