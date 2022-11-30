<<<<<<< HEAD
# The Steganographic Potentials of Language Models

This is a research project in the AI safety field. The goal is to prevent LLMs deception via hidden reasoning in text, we evaluate and induce steganography.

Our contribution and impact:

- Evidence in favor or against LLMs steganography capabilities.
- Evaluation tool(s) to detect steganography.
- If we have a trained model on stego, this can be used to do research on steganography in LLMs (interpretability).
- Code base to conduct experiments with RL on current or future LLMs.
- Preventing models from hiding their reasoning in the plain text.
- Increasing trust in models text output (mech interpretability, AI control).
- Answering the question if models can hide their reasoning.
- Potential for other research directions (LLMs watermarking, stego tool, unknown steganography methods).


Why: to prevent LLMs deception

- AGI deception is a high risk factor and it is a likely outcome of capabilities increase. The rogue AI scenario.
- LLMs are likely to be the core of AGI.  Possibility of LLMs deception (collusion) through text.
- So we want to increase trust in the text (interpretability, control, fine tuning etc.) 

What: Deception via hidden reasoning in text

- If LLMs are able to hide their reasoning in plain text, then it is more difficult to prevent  their deception. Steganography enables hiding reasoning in the plain text.
- Steganography (stego) is hiding a message in such a way that its presence is undetected. Difference from cryptography is the hidden transmission. For text, images, audio, etc.
- Perfectly secure* (undetectable) steganography is possible.

How: evaluation and inducing steganography

- Rationale: It is neglected. There is one base steganography evaluation tool and only few publications addressing safety of stego by LLMs.
- Our solution: 
  - Prompting to eval stego, to have a good tool at hand for big labs and for research.
  - Inducing stego via SFT or RL, to understand current LLMs potential and find dangerous training conditions that might lead to it. Proof-of-concept.
- Why Reinforcement Learning (RL)? Unclear where LLMs might converge to when under optimization pressure. Interest in the indirect emergence of stego.

![image](https://github.com/user-attachments/assets/82013860-11df-4ee5-a8a5-c09e39973ca6)

Sources / references:

- Panickssery et al. LLM Evaluators Recognize and Favor Their Own Generations. 2024.
- Pfau et al. Let’s Think Dot by Dot: Hidden Computation in Transformer Language Models. 2024.
- Roger and Greenblatt, ‘Preventing Language Models From Hiding Their Reasoning’. 2023
- Motwani et al., ‘Secret Collusion Among Generative AI Agents’. 2024. Larger models are more capable.

=======
# Academic Project Page Template
This is an academic paper project page template.


Example project pages built using this template are:
- https://www.vision.huji.ac.il/deepsim/
- https://www.vision.huji.ac.il/3d_ads/
- https://www.vision.huji.ac.il/ssrl_ad/
- https://www.vision.huji.ac.il/conffusion/


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
>>>>>>> 94d80b2 (Initial commit)
