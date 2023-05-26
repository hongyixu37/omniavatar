# OmniAvatar: Geometry-Guided Controllable 3D Head Synthesis
###[Project](https://hongyixu37.github.io/omniavatar/)| [Paper]https://arxiv.org/abs/2303.15539< br>

![](imgs/header.gif)

___

> **OmniAvatar: Geometry-Guided Controllable 3D Head Synthesis**<br>
> Hongyi Xu, Guoxian Song, Zihang Jiang, Jianfeng Zhang, Yichun Shi<br>
> , Jing Liu, Wanchun Ma, Jiashi Feng, Linjie Luo<br>
> https://arxiv.org/abs/2303.15539 <br>
>
>**Abstract:** We present DeepSIM, a generative model for conditional image manipulation based on a single image.
We present OmniAvatar, a novel geometry-guided 3D head synthesis model trained from in-the-wild unstructured images that is capable of synthesizing diverse identity- preserved 3D heads with compelling dynamic details un- der full disentangled control over camera poses, facial ex- pressions, head shapes, articulated neck and jaw poses. To achieve such high level of disentangled control, we first ex- plicitly define a novel semantic signed distance function (SDF) around a head geometry (FLAME) conditioned on the control parameters. This semantic SDF allows us to build a differentiable volumetric correspondence map from the observation space to a disentangled canonical space from all the control parameters. We then leverage the 3D- aware GAN framework (EG3D) to synthesize detailed shape and appearance of 3D full heads in the canonical space, fol- lowed by a volume rendering step guided by the volumetric correspondence map to output into the observation space. To ensure the control accuracy on the synthesized head shapes and expressions, we introduce a geometry prior loss to conform to head SDF and a control loss to conform to the expression code. Further, we enhance the temporal realism with dynamic details conditioned upon varying expressions and joint poses. Our model can synthesize more preferable identity-preserved 3D heads with compelling dynamic de- tails compared to the state-of-the-art methods both qualita- tively and quantitatively. We also provide an ablation study to justify many of our system design choices.

## Start using the template
To start using the template click on `Use this Template`.

The template uses html for controlling the content and css for controlling the style. 
To edit the websites contents edit the `index.html` file. It contains different HTML "building blocks", use whichever ones you need and comment out the rest.  

## Components
- Teaser video
- Images Carousel
- Youtube embedding
- Video Carousel
- PDF Poster
- Bibtex citation

## Tips:
- The `index.html` file contains comments instructing you what to replace, you should follow these comments.
- The `meta` tags in the `index.html` file are used to provide metadata about your paper 
(e.g. helping search engine index the website, showing a preview image when sharing the website, etc.)
- The resolution of images and videos can usually be around 1920-2048, there rarely a need for better resolution that take longer to load. 
- All the images and videos you use should be compressed to allow for fast loading of the website (and thus better indexing by search engines). For images, you can use [TinyPNG](https://tinypng.com), for videos you can need to find the tradeoff between size and quality.
- When using large video files (larger than 10MB), it's better to use youtube for hosting the video as serving the video from the website can take time.
- Using a tracker can help you analyze the traffic and see where users came from. [statcounter](https://statcounter.com) is a free, easy to use tracker that takes under 5 minutes to set up. 
- This project page can also be made into a github pages website.
- Replace the favicon to one of your choosing (the default one is of the Hebrew University). 
- Suggestions, improvements and comments are welcome, simply open an issue or contact me. You can find my contact information at [https://pages.cs.huji.ac.il/eliahu-horwitz/](https://pages.cs.huji.ac.il/eliahu-horwitz/)

## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.