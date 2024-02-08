# pierresendorek.github.io

## About me
Interests
* Synthesizers, sound effects, weird sounds
* Machine Learning
* Neural Networks
* Bayesian models
* Markov Chains
* Optimization problems
* Surprising algorithms


More about me / contact [LinkedIn profile](https://www.linkedin.com/in/pierresendorek/)

## My personal projects

See my [github repositories](https://github.com/pierresendorek?tab=repositories) to have an overview of all my projects.

---
### Voice converter

[Source code](https://github.com/pierresendorek/voice_converter)

This algorithm enables to convert one's voice to someone elses voice. Developped as a side project, my former company, Xebia, gave me the opportunity to present it at our yearly conference.

The algorithm works by using a vocal feature extractor (pitch + formants).
At learning time, the features are aligned with those of the target voice thanks to a Dynamic Time Warping algorithm. Then the mapping between the features is learned by the neural network. At synthesis time, my voice features are extracted and converted by the neural network without alignment. Finally I use my vocal synthesizer to generate the target voice.



Video of the conference

<iframe width="560" height="315" src="https://www.youtube.com/embed/jjdS0HGN3Js?si=3GBJl5-9WIJSRkOM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---
### Cryptocurrencies trading

[Source code](https://github.com/pierresendorek/cryptocurrencies_trading)

A project in which I invested some time. The code contains
* Python wrappers for API calls to get informations about the values of previous trades.
* Python wrappers to download historical data
* Recursive exponential smoothing functions for nonhomogeneous time sampling to extract smoothed features such as averages, variances at with parametrable smoothing, and their mathematical derivations.
* Some strategies that I tried (arbitrage, noise scalping and more)



---
### Vocoder

[Source code](https://github.com/pierresendorek/vocoder)


Fascinated by this audio effect I decided to code a vocoder by myself to see how it works.


Here is an example of how it sounds on my own voice

| | |
|---|---|
| Modulator input sound | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/vocoder/in.mp3"></audio> |
| Carrier input sound | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/vocoder/carrier.mp3"></audio>|
| Result / output sound |<audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/vocoder/out.mp3"></audio>|

---
### Beat Box to Real Percussions converter

Here is an audio utility that converts "beatbox" sounds one make with its mouth to real percussion sounds. No Neural Networks were used here, only a research of a closest neighbor in the space of the features.

[Source code](https://github.com/pierresendorek/redrum)

| | |
|---|---|
| Beatbox sound | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/redrum/in.mp3"></audio> |
| Result / output sound | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/redrum/out.mp3"></audio> |
| Beatbox sound + Result together | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/redrum/mix.mp3"></audio> |

---
### Interacting Particles

I also coded this project in Java. The goals were to gain experience with
* Java graphical components
* Real time interactions
* Using a graphical interface
* Have fun with some physical phenomenon

<iframe width="560" height="315" src="https://www.youtube.com/embed/B-DOCRPKvX8?si=Yh07cRVRx6AGGL0_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---
### D'Alembert Wave Equation
I coded this project in Java. The goals were to gain experience with
* Java graphical components
* 3d isometric rendering, that I fully coded from scratch
* D'Alembert Wave Equation, and play with some parameters

<iframe width="560" height="315" src="https://www.youtube.com/embed/MeQwHqAqhgU?si=XYLxuIkJ_ECK_Cn0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---
### Sound generators, transformers and analyzers

[Source code](https://github.com/pierresendorek/sound_gen_transform_analyze)

This repository contains code and documentation for some audio tools I made. The goal of the project is to group the work also done in my other sound-related projects, such as
* [audioTools](https://github.com/pierresendorek/audioTools)
* Vocoder (as seen before on this page)
* Redrum (as seen before on this page)
* [Neural Sound Generator](https://github.com/pierresendorek/neural_sound_generator)






