# Introduction to RunwayML

## Session A: Hosted Models and Networking

### Objectives

- Learn how to integrate Colab with JavaScript and other software applications.

### Resources

- [Hosted Models](https://learn.runwayml.com/#/how-to/hosted-models)
- [Interact with models in Colab over the network](https://learn.runwayml.com/#/how-to/network)

## Session B: Generative Adversarial Networks, Semantic Maps

### Objectives

- Understand the basics of how the GANs and Image Colorization models work
- Develop high-level understandings of nonlinear dimensionality reductions and the latent space.
- Understand how GANs can be applied to interactive systems to generate imagery.
- [Slides](https://docs.google.com/presentation/d/1jECVQczrHB1Wtx4-BBJoVeWLW45hYoLk6dBak8SHSVQ/edit?usp=sharing)

### Additional references

- [Google's A.I. Experiments: Visualizing High-Dimensional Space](https://www.youtube.com/watch?v=wvsE8jm1GzE)
- [Using Artificial Intelligence to Augment Human Intelligence](https://distill.pub/2017/aia/) by Shan Carter (see the first three sections for latent space descriptions)
- Octavio Good on [Generative Adversarial Networks](https://www.youtube.com/watch?v=Oqm9vsf_hvU&feature=youtu.be&t=1313) (21:54 - 28:35)
- [GAN Lab](https://poloclub.github.io/ganlab/) by Minsuk Kahng, Nikhil Thorat, Polo Chau, Fernanda Viégas, and Martin Wattenberg
- [In the Age of A.I., Is Seeing Still Believing?](https://www.newyorker.com/magazine/2018/11/12/in-the-age-of-ai-is-seeing-still-believing) by Joshua Rothman

### Creative GAN projects

- [Playing a game of GANstruction](https://thegradient.pub/playing-a-game-of-ganstruction/) by Helena Sarin ([2019 Eyeo Talk](https://vimeo.com/354276365)]
- [Misremembering and Mistranslating: GANs in Art Context](http://annaridler.com/gans-in-art) and [Fall of the House of Usher](http://annaridler.com/fall-of-the-house-of-usher) by Anna Ridler
- [Using AI to Produce “Impossible” Tulips: Anna Ridler uses AI to bring “tulipmania” into the future](https://hyperallergic.com/487261/anna-ridler-tulipmania/) by Elain Ayers
- Mario Klingemann’s Neurography: [Cameraless Photography with Neural Networks](https://www.youtube.com/watch?v=21W5-q5YYjw)
- [Booksby.ai](https://booksby.ai/about/) by Andreas Refsgaard and Mikkel Thybo Loose
- [Unfinished](https://aiartists.org/roman-lipski) by Roman Lipski
- [Blackberry Winter](https://christianmioloclair.com/blackberrywinter) by Christian Mio Loclair
- [Meet AICAN, a machine that operates as an autonomous artist](https://www.interaliamag.org/articles/ahmed-elgammal/)

### Semantic Maps / Image Synthesis

- [Semantic Image Synthesis with Spatially-Adaptive Normalization](https://nvlabs.github.io/SPADE/), [original SPADE paper](https://arxiv.org/pdf/1903.07291.pdf) paper
- [GAUGan online demo](http://nvidia-research-mingyuliu.com/gaugan/)
- [Learning to See](http://www.memo.tv/portfolio/learning-to-see/) by Memo Akten
- [Uncanny Road](https://cvalenzuelab.com/uncannyrd/) by Anastasis Germanidis and Cristóbal Valenzuela
- [AI Lab Workshop: Painting Landscapes with the Body](https://github.com/ellennickles/painting-landscapes-with-the-body)

### Code Examples

- [Glitch! RunwayML template - StyleGAN](https://glitch.com/edit/#!/runway-ml-template)
- [Glitch! RunwayML StyleGAN walk](https://glitch.com/edit/#!/latent-sky-walk)
- [p5 web editor: send text to RunwayML: Generate an image with AttnGAN](https://editor.p5js.org/ima_ml/sketches/mOAf3ggYQ)
- [p5 web editor: send webcam image to RunwayML: Photo booth with Fast Style Transfer](https://editor.p5js.org/ima_ml/sketches/nhxxASB9t)
- [p5 web editor: send uploaded image file to RunwayML: Generate a caption with im2txt](https://editor.p5js.org/ima_ml/sketches/1kb6hUBvT)

### Assignment (Due Sunday, Nov 9):

1. Create a p5.js sketch that receives data from RunwayML (using any model). You can use this [glitch RunwayML template](https://glitch.com/edit/#!/runway-ml-template) which hides the keys in a `.env` file. **(If you work with the web editor only, be careful about leaving your token in your code and the model active in the RunwayML interface!)**
2. Optionally, send data to RunwayML or use another programming environment or software tool besides p5.js.
3. Continue your reflection on RunwayML in a blog post. How is working with RunwayML from your code compared to the web interface? Include screenshots and screen captures of your workflow.
