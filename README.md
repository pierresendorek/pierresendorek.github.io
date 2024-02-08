# pierresendorek.github.io

## About me
Interests
* Synthesizers, sound effects, weird sounds
* Machine Learning
* Neural Networks
* Bayesian models
* Markov Chains
* Optimization methods
* Surprising algorithms


More about me / contact [LinkedIn profile](https://www.linkedin.com/in/pierresendorek/)

## My personal projects

See my [github repositories](https://github.com/pierresendorek?tab=repositories) to have an overview of all my projects.

---
### Voice converter (2017)

[Source code](https://github.com/pierresendorek/voice_converter)

This algorithm enables to convert one's voice to someone elses voice. Developped as a side project, my former company, Xebia, gave me the opportunity to present it at our yearly conference.

The algorithm works by using a vocal feature extractor (pitch + formants).
At learning time, the features are aligned with those of the target voice thanks to a Dynamic Time Warping algorithm. Then the mapping between the features is learned by the neural network. At synthesis time, my voice features are extracted and converted by the neural network without alignment. Finally I use my vocal synthesizer to generate the target voice.



Video of the conference

<iframe width="560" height="315" src="https://www.youtube.com/embed/jjdS0HGN3Js?si=3GBJl5-9WIJSRkOM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---
### Cryptocurrencies trading (2020)

[Source code](https://github.com/pierresendorek/cryptocurrencies_trading)

A project in which I invested some time. The code contains
* Python wrappers for API calls to get informations about the values of previous trades.
* Python wrappers to download historical data
* Recursive exponential smoothing functions for nonhomogeneous time sampling to extract smoothed features such as averages, variances at with parametrable smoothing, and their mathematical derivations.
* Some strategies that I tried (arbitrage, noise scalping and more)



---
### Vocoder (2016)

[Source code](https://github.com/pierresendorek/vocoder)


Fascinated by this audio effect I decided to code a vocoder by myself to see how it works.


Here is an example of how it sounds on my own voice

| | |
|---|---|
| Modulator input sound | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/vocoder/in.mp3"></audio> |
| Carrier input sound | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/vocoder/carrier.mp3"></audio>|
| Result / output sound |<audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/vocoder/out.mp3"></audio>|

---
### Beat Box to Real Percussions converter (2016)

Here is an audio utility that converts "beatbox" sounds one make with its mouth to real percussion sounds. No Neural Networks were used here, only a research of a closest neighbor in the space of the features.

[Source code](https://github.com/pierresendorek/redrum)

| | |
|---|---|
| Beatbox sound | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/redrum/in.mp3"></audio> |
| Result / output sound | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/redrum/out.mp3"></audio> |
| Beatbox sound + Result together | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/redrum/mix.mp3"></audio> |

---
### Interacting Particles (2015)

I also coded this project in Java. The goals were to gain experience with
* Java graphical components
* Real time interactions
* Using a graphical interface
* Have fun with some physical phenomenon

<iframe width="560" height="315" src="https://www.youtube.com/embed/B-DOCRPKvX8?si=Yh07cRVRx6AGGL0_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---
### D'Alembert Wave Equation (2015)
I coded this project in Java. The goals were to gain experience with
* Java graphical components
* 3d isometric rendering, that I fully coded from scratch
* D'Alembert Wave Equation, and play with some parameters

<iframe width="560" height="315" src="https://www.youtube.com/embed/MeQwHqAqhgU?si=XYLxuIkJ_ECK_Cn0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---
### Sound generators, transformers and analyzers (2023)

[Source code](https://github.com/pierresendorek/sound_gen_transform_analyze)

This repository contains code and documentation for some audio tools I made. The goal of the project is to group the work also done in my other sound-related projects, such as
* [audioTools](https://github.com/pierresendorek/audioTools)
* Vocoder (as seen before on this page)
* Redrum (as seen before on this page)
* [Neural Sound Generator](https://github.com/pierresendorek/neural_sound_generator)



---
## Papers & Patents

* Pierre Sendorek. “Amélioration de l’intégrité d’un système de positionnement GNSS/IMU” (Improvement of the integrity of a GNSS/IMU positioning system). PhD Thesis, French. CIFRE with Thales Avionics and Télécom ParisTech, june 2015. *Industrial Confidentiality.

* [Pierre Sendorek, Karim Abed Meraim, Maurice Charbit. "Amélioration de l'intégrité d'une position GNSS par une réduction de la sensibilité à une panne satellite" Brevet Français Numéro P2937 6 sept. 2013. *Patent*.](https://data.inpi.fr/brevets/FR3010533)

* [Pierre Sendorek, Maurice Charbit, Karim Abed-Meraim, Sébastien Legoll. Locally Optimal Confidence Ball for a Gaussian Mixture Random Variable. 4th Int. Conf. on Indoor Positioning and
Indoor Navigation(IPIN)„ Oct 2013, Belfort, France. ffhal-01002332f](https://hal.science/hal-01002332/document)

* [Pierre Sendorek, Karim Abed-Meraim, Maurice Charbit, Sebastien Legoll. Improvements of
GNSS/INS Localization’s Integrity with Gaussian Mixture Filters in a Bayesian Framework. The
6th European Workshop on GNSS Signals and Signal Processing, Dec 2013, Munich, Germany. ffhal01002195f](https://hal.science/hal-01002195/document)

* [KOTNIK, Bojan, SENDOREK, Pierre, ASTROV, Sergey, et al. Evaluation of voice activity and voicing detection. In : INTERSPEECH. 2008. p. 1642-1645.](https://d1wqtxts1xzle7.cloudfront.net/41160102/Evaluation_of_voice_activity_and_voicing20160114-31021-boerdj.pdf20160114-19908-1wdcvrm-libre.pdf?1452833976=&response-content-disposition=inline%3B+filename%3DEvaluation_of_voice_activity_and_voicing.pdf&Expires=1707428828&Signature=MMaWr7EDAirAHO0hZPSwTFzaDxCCVhzrku6T3uFS-kWbLVFLiyjcPExVc02x60BfTP5h992eQo3ZDRN4kUeDNqEnZTdu4jviF~EbdUIYQc0B4kH6HlBVD9ROCAlhup-ELltlD4n1b4zZ45geXuGwZCwKZZTgDb-vLSqg-ARk71~yPMhR0NTN3BCqUkIDRhjCVdQF7hYLzQX58frjmD9G2OpV2JlQx48c-jscEoTNmWRWO4pxl0obwsbx~umg1X4N3IdZFGR5fFVqiCVe-ahgf4rKMPMKGdzvxRJMID36~3MYC~eOltNz7G895pLGMe5zl-OGKQqs3O--b6-pMnRq0w__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)

---
## Other talks

<iframe width="560" height="315" src="https://www.youtube.com/embed/1y8UzkM9eMI?si=y8-Uta0Pxb8fykfp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/TP4ROl6EYrU?si=a5DYVBnLuJ0MqJKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/OfI64rl5VNE?si=j42FP08DkX7-SBBl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

