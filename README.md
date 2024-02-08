# pierresendorek.github.io

## About me
Interests
* Synthesizers, Sound Effects, weird sounds
* Bayesian models
* Markov Chains
* Neural Networks
* Surprising algorithms


To contact me and know more about me, see my [LinkedIn profile](https://www.linkedin.com/in/pierresendorek/)

## My personal projects

### Voice converter

This algorithm enables to convert one's voice to someone elses voice. Developped as a side project, my former company, Xebia, gave me the opportunity to present it at our yearly conference.

The algorithm works by using a vocal feature extractor (pitch + formants).
The features are then aligned with those of the target voice thanks to a Dynamic Time Warping algorithm. Then the mapping between the features is learned by the neural network, and I use my vocal synthesizer to generate a voice.

[Repository](https://github.com/pierresendorek/voice_converter)

Video of the conference

<iframe width="560" height="315" src="https://www.youtube.com/embed/jjdS0HGN3Js?si=3GBJl5-9WIJSRkOM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


### Vocoder
Fascinated by this audio effect I decided to code a vocoder by myself to see how it works.

[Repository](https://github.com/pierresendorek/vocoder)

Here is an example of how it sounds on my own voice

| | |
|---|---|
| Modulator input sound | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/vocoder/in.mp3"></audio> |
| Carrier input sound | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/vocoder/carrier.mp3"></audio>|
| Result / output sound |<audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/vocoder/out.mp3"></audio>|


### Beat Box to Real Percussions converter

Here is an audio utility that converts "beatbox" sounds one make with its mouth to real percussion sounds. No Neural Networks were used here, only a research of a closest neighbor in the space of the features.

| | |
|---|---|
| Beatbox sound | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/redrum/in.mp3"></audio> |
| Result / output sound | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/redrum/out.mp3"></audio> |
| Beatbox sound + Result together | <audio controls src="https://github.com/pierresendorek/pierresendorek.github.io/raw/main/audio/redrum/mix.mp3"></audio> |


### Interacting Particles

I also coded this project in Java. The goals were to gain experience with
* Java graphical components
* Real time interactions
* Using a graphical interface
* Have fun with some physical phenomenon

<iframe width="560" height="315" src="https://www.youtube.com/embed/B-DOCRPKvX8?si=Yh07cRVRx6AGGL0_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### D'Alembert Wave Equation
I coded this project in Java. The goals were to gain experience with
* Java graphical components
* 3d isometric rendering, that I fully coded from scratch
* D'Alembert Wave Equation, and play with some parameters

<iframe width="560" height="315" src="https://www.youtube.com/embed/MeQwHqAqhgU?si=XYLxuIkJ_ECK_Cn0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>





