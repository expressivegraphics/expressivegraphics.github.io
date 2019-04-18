---
layout: default
title: Accepted Submissions
image:
  card: 2019/expressiveCard.jpg
year: 2019
---


<div class="col-12 col-sm-12 col-lg-12">

  <a name="accepted"></a><h2>Papers</h2><br/>
  
      <a name="paper1"></a>
      <h4>Non-Photorealistic Animation for Immersive Storytelling</h4>

      <p>Cassidy Curtis, Kevin Dart, Theresa Latzko, and John Kahrs.</p>
      <p>Immersive media such as virtual and augmented reality pose some interesting new challenges for non-photorealistic animation: we must not only balance the screen-space rules of a 2D visual style against 3D motion coherence, but also account for stereo spatialization and interactive camera movement, at a rate of 90 frames per second. We introduce two new real-time rendering techniques: MetaTexture, an example-based multiresolution texturing method that adheres to the movement of 3D geometry while maintaining a consistent level of screen-space detail, and Edge Breakup, a method for roughening edges by warping with structured noise. We show how we have used these techniques, along with art-directable coloring, shadow filtering, and shader-based texture indication, to achieve the “moving illustration” style of the immersive short film “Age of Sail”.</p>
  
      <a name="paper2"></a>
      <hr class="bs-docs-separator">
      <h4>Video Motion Stylization by 2D Rigidification</h4>

      <p>Johanna Delanoy, Aaron Hertzmann, and Adrien Bousseau.</p>
      <p>This paper introduces a video stylization method that increases the apparent rigidity of motion. Existing stylization methods often retain the 3D motion of the original video, making the result look like a 3D scene covered in paint rather than a 2D painting of a scene. In contrast, traditional hand-drawn animations often exhibit simplified in-plane motion, such as in the case of cut-out animations where the animator moves pieces of paper from frame to frame. Inspired by this technique, we propose to modify a video such that its content undergoes 2D rigid transforms. To achieve this goal, our approach applies motion segmentation and optimization to best approximate the input optical flow with piecewise-rigid transforms, and re-renders the video such that its content follows the simplified motion. The output of our method is a new video and its optical flow, which can be fed to any existing video stylization algorithm.</p>

      <a name="paper3"></a>
      <hr class="bs-docs-separator">
      <h4>Learning from Multi-domain Artistic Images for Arbitrary Style Transfer</h4>

      <p>Zheng Xu, Michael Wilber, Chen Fang, Aaron Hertzmann, and Hailin Jin.</p>
      <p>We propose a fast feed-forward network for arbitrary style transfer, which can generate stylized image for previously unseen content and style image pairs. Besides the traditional content and style representation based on deep features and statistics for textures, we use adversarial networks to regularize the generation of stylized images. Our adversarial network learns the intrinsic property of image styles from large-scale multi-domain artistic images. The adversarial training is challenging because both the input and output of our generator are diverse multi-domain images. We use a conditional generator that stylized content by shifting the statistics of deep features, and a conditional discriminator based on the coarse category of styles. Moreover, we propose a mask module to spatially decide the stylization level and stabilize adversarial training by avoiding mode collapse. As a side effect, our trained discriminator can be applied to rank and select representative stylized images. We qualitatively and quantitatively evaluate the proposed method, and compare with recent style transfer methods. We release our code and model at <a href="https://github.com/nightldj/behance_release">https://github.com/nightldj/behance_release</a>.</p>
	  
      <a name="paper4"></a>
      <hr class="bs-docs-separator">
      <h4>Real-Time Patch-Based Stylization of Portraits Using Generative Adversarial Network</h4>

      <p>David Futschik, Menglei Chai, Chen Cao, Chongyang Ma, Aleksei Stoliar, Sergey Korolev, Sergey Tulyakov, Michal Kučera, and Daniel Sýkora.</p>
      <p>We present a learning-based style transfer algorithm for human portraits which significantly outperforms current state-of- the-art in computational overhead while still maintaining comparable visual quality. We show how to design a conditional generative adversarial network capable to reproduce the output of Fišer et al.’s patch-based method [FJS∗17] that is slow to compute but can deliver state-of-the-art visual quality. Since the resulting end-to-end network can be evaluated quickly on current consumer GPUs, our solution enables first real-time high-quality style transfer to facial videos that runs at interactive frame rates. Moreover, in cases when the original algorithmic approach of Fišer et al. fails our network can provide a more visually pleasing result thanks to generalization. We demonstrate the practical utility of our approach on a variety of different styles and target subjects.</p>
	  
      <a name="paper5"></a>
      <hr class="bs-docs-separator">
      <h4>Enhancing Neural Style Transfer using Patch-Based Synthesis</h4>

      <p>Ondřej Texler, Jakub Fišer, Mike Lukac, Jingwan Lu, Eli Shechtman, and Daniel Sýkora.</p>
      <p>We present a new approach to example-based style transfer which combines neural methods with patch-based synthesis to achieve compelling stylization quality even for high-resolution imagery. We take advantage of neural techniques to provide adequate stylization at the global level and use their output as a prior for subsequent patch-based synthesis at the detail level. Thanks to this combination, our method keeps the high frequencies of the original artistic media better, thereby dramatically increases the fidelity of the resulting stylized imagery. We also show how to stylize extremely large images (e.g., 340 Mpix) without the need to run the synthesis at the pixel level, yet retaining the original high-frequency details.</p>
	  
      <a name="paper6"></a>
      <hr class="bs-docs-separator">
      <h4>Sketching and Layering Graffiti Primitives</h4>

      <p>Daniel Berio, Paul Asente, Jose Echevarria, and Frederic Fol Leymarie.</p>
      <p>We present a variant of the skeletal strokes algorithm aimed at mimicking the appearance of hand made graffiti art. It includes a unique fold-culling process that stylizes folds rather than eliminating them. We demonstrate how the stroke structure can be exploited to generate non-global layering and self-overlap effects like the ones that are typically seen in graffiti art and other related art forms like traditional calligraphy. The method produces vector output with no artificial artwork splits, patches or masks to render the non-global layering; each path of the vector output is part of the desired outline. The method lets users interactively generate a wide variety of stylised outputs.</p>
	  
      <a name="paper7"></a>
      <hr class="bs-docs-separator">
      <h4>Single Stroke Aerial Robot Light Painting</h4>

      <p>Kejia Ren and Paul Kry.</p>
      <p>This paper investigates trajectory generation alternatives for creating single-stroke light paintings with a small quadrotor robot. We propose to reduce the cost of a minimum snap piecewise polynomial quadrotor trajectory passing through a set of waypoints by displacing those waypoints towards or away from the camera while preserving their projected position. It is in regions of high curvature, where waypoints are close together, that we make modifications to reduce snap, and we evaluate two different strategies: one that uses a full range of depths to increase the distance between close waypoints, and another that tries to keep the final set of waypoints as close to the original plane as possible. Using a variety of one-stroke animal illustrations as targets, we evaluate and compare the cost of different optimized trajectories, and discuss the qualitative and quantitative quality of flights captured in long exposure photographs.</p>

      <a name="paper8"></a>
      <hr class="bs-docs-separator">
      <h4>Generating Playful Palettes from Images</h4>

      <p>Stephen DiVerdi, Jingwan Lu, Jose Echevarria, and Maria Shugrina.</p>
      <p>Playful Palettes are a recent innovation in how artists can mix, explore, and choose colors in a user interface that combines the benefits of a traditional media painter’s palette with non-destructive capabilities of digital tools. We present a technique to generate a Playful Palette that best represents the colors found in an input image, allowing the artist to select colors from the image’s gamut, while maintaining full editability of the palette. We show that our approach outperforms recent work in terms of how accurately the image gamut is reproduced, and we present an approximation algorithm that is an order of magnitude faster with an acceptable loss in quality.</p>
	  
      <a name="paper9"></a>
      <hr class="bs-docs-separator">
      <h4>Aesthetically-Oriented Atmospheric Scattering</h4>

      <p>Yang Shen, Ian Mallett, and Konstantin Shkurko.</p>
      <p>We present Aesthetically-Oriented Atmospheric Scattering (AOAS): an experiment into the feasibility of using real-time rendering as a tool to explore sky styles. AOAS provides an interactive design environment which enables rapid iteration cycles from concept to implementation to preview. Existing real-time rendering techniques for atmospheric scattering struggle to produce non-photorealistic sky styles within any 3D scene. To solve this problem, first, we simplify the geometric representation of atmospheric scattering to a single skydome to leverage the flexibility and simplicity of skydomes in compositing with 3D scenes. Second, we classify the essential and non-essential visual characteristics of the sky and allow AOAS to vary the latter, thus producing meaningful, non-photorealistic sky styles with real-time atmospheric scattering that are still recognizable as skies, but contain artistic stylization. We use AOAS to generate a wide variety of sky examples ranging from physical to highly stylized in appearance. The algorithm can be easily implemented on the GPU, and performs at interactive frame rates with low memory consumption and CPU usage.</p>
	  
      <a name="paper10"></a>
      <hr class="bs-docs-separator">
      <h4>Abstract Shape Synthesis From Linear Combinations of Clelia Curves</h4>

      <p>Lance Putnam, Stephen Todd, and William Latham.</p>
      <p>This article outlines several families of shapes that can be produced from a linear combination of Clelia curves. We present parameters required to generate a single curve that traces out a large variety of shapes with controllable axial symmetries. Several families of shapes emerge from the equation that provide a productive means by which to explore the parameter space. The mathematics involves only arithmetic and trigonometry making it accessible to those with only the most basic mathematical background. We outline formulas for producing basic shapes, such as cones, cylinders, and tori, as well as more complex families of shapes having non-trivial symmetries. This work is of interest to computational artists and designers as the curves can be constrained to exhibit specific types of shape motifs while still permitting a liberal amount of room for exploring variations on those shapes.</p>
	  
      <a name="paper11"></a>
      <hr class="bs-docs-separator">
      <h4>Aesthetics of Curvature Bases for Sketches</h4>

      <p>Keith Lippincott, Ross Hatton, and Cindy Grimm.</p>
      <p>In this work we propose a curve approximation method that operates in the curvature domain. The curvature is represented using one of several different types of basis functions (linear, quadratic, spline, sinusoidal, orthogonal polynomial), and the curve’s geometry is reconstructed from that curvature basis. Our hypothesis is that different curvature bases will result in different aesthetics for the reconstructed curve. We conducted a user study comparing multiple curvature bases, both for aesthetics and similarity to the original curve, and found statistically significant differences in how people ranked the reconstructed curve’s aesthetics and similarity. To support adaptive curve fitting we developed a fitting algorithm that matches the original curve’s geometry and explicitly accounts for corners.</p>
	  
      <a name="paper12"></a>
      <hr class="bs-docs-separator">
      <h4>Defining Hatching in Art</h4>

      <p>Greg Philbrick and Craig Kaplan.</p>
      <p>We define hatching—a drawing technique—as rigorously as possible. A pure mathematical formulation or even a binary this-or- that definition is unreachable, but useful insights come from driving as close as we can. First we explain hatching’s purposes. Then we define hatching as the use of patches: groups of roughly parallel curves that form flexible, simple patterns. After elaborating on this definition’s parts, we briefly treat considerations for research in expressive rendering.</p>
	  
      <a name="paper13"></a>
      <hr class="bs-docs-separator">
      <h4>Stipple Removal in Extreme-tone Regions</h4>

      <p>Rosa Azami, Lars Doyle, and David Mould.</p>
      <p>Conventional tone-preserving stippling struggles with extreme-tone regions. Dark regions require immense quantities of stipples, while light regions become littered with stipples that are distracting and, because of their low density, cannot communicate any image features that may be present. We propose a method to address these problems, augmenting existing stippling methods. We will cover dark regions with solid polygons rather than stipples; in light areas, we both preprocess the image to prevent stipple placement in the very lightest areas and postprocess the stipple distribution to remove stipples that contribute little to the image structure. Our modified stipple images have better visual quality than the originals despite using fewer stipples.</p>
	  
      <a name="paper14"></a>
      <hr class="bs-docs-separator">
      <h4>Irregular Pebble Mosaics with Sub-Pebble Detail</h4>

      <p>Ali Sattari, Lars Doyle, and David Mould.</p>
      <p>Pebble mosaics convey images through an irregular tiling of rounded pebbles. Past work used relatively uniform tile sizes. We show how to create detailed representations of input photographs in a pebble mosaic style; we first create pebble shapes through a variant of k-means, then compute sub-pebble detail with textured, two-tone pebbles. We use a custom distance function to ensure that pebble sizes adapt to local detail and orient to local feature directions, for an overall effect of high fidelity to the input photograph despite the constraints of the pebble style.</p>

      <br/>
	  
	  <h2>Artworks</h2><br/>

      <a name="artwork1"></a>
      <h4>Wandering Without Wondering</h4>

      <p>Sala Wong and Peter Williams.</p>
      <p>Wandering Without Wondering is a hybrid-media installation distilling and chronicling artists Sala Wong and Peter Williams’ collaborative walking practice. The project uses various digital technologies to augment human senses, metaphorically linking and complicating the concepts of immersion and interaction through disruptive and hypermediated approaches to technologies such as 360-degree imaging, projection mapping, virtual reality and spatial audio produce an expressive, visually-saturated, physical/virtual hybrid space through which visitors journey between states of technologically-facilitated expression.</p>
	  
	  <a name="artwork2"></a>
      <hr class="bs-docs-separator">
      <h4>The CyberAnthill</h4>

      <p>Evan Raskob.</p>
      <p>The CyberAnthill is both a generative sculpture and a Live Computational Sculpting (LCS) system that uses a 3D printer and custom software to build plastic sculptures out of layered cellular automata. As the title alludes to, the cellular automata are inspired by Langston’s Ant and the light cycle racers in the cult 1980’s science-fiction movie Tron. Instead of the normal process of printing exacting, predetermined 3D models, the 3D printer generates its plastic forms by running unpredictable computer code.</p>
	  
	  <a name="artwork3"></a>
      <hr class="bs-docs-separator">
      <h4>Transhuman Expression Human-Machine Interaction as a Neutral Base for a New Artistic and Creative Practice</h4>

      <p>Liat Grayver and Gualtiero Volpe.</p>
      <p>Transhuman Expression is an interactive room installation created by Liat Grayver in collaboration with the EU-H2020-ICT project weDRAW in the context of a Vertigo STARTS residency at the Casa Paganini - InfoMus reseach center of DIBRIS - University of Genova, Italy. Data captured via motion detection of visitors is analyzed, processed, and projected on large screens positioned in the exhibition area. The collaboration benefited, was built on, and furthered experiences that both the artist and the research team have had in ongoing work exploring convergence of artistic and scientific practices. Grayver’s work in robotics-assisted painting gained new tools that can be integrated into the system she works with at the University of Konstanz, whilst Casa Paganini - InfoMus has acquired new perspectives on the range, scope, and scale of real-time, automated movement analysis. This paper reports about goals, methodology, and results of such a joint multidisciplinary activity.</p>
	  
	  <a name="artwork4"></a>
      <hr class="bs-docs-separator">
      <h4>Emergence in the Expressive Machine</h4>

      <p>Laura Dekker.</p>
      <p>The “Expressive Machine” is a series of interactive artworks which explore a machine’s-eye view of the world. The machine— an assemblage of hardware and software—provokes sensual interaction with viewer-participants, playing with transduction across multiple modes: from touch to sound, to word, to vision, to taste, to uniquely machinic states with no particular human analogue. These stimuli are processed in various interpretations, elaborations, in a relatively unstructured “data soup”. Asynchronous processes consume data from the soup. When trigger conditions for a particular expressive process are satisfied, the machine produces externalised outputs in various forms: sound, shift of attention, fragments of narrative, and so on. What can be considered as creativity arises as an emergent property—a serendipitous by-product of the machine working through its experiences, rather than an explicit creative process. To make this conceptual exploration possible, an adaptable, extensible, decentralised system is presented: its requirements, architecture and some implementations as interactive artworks. Each new site and context gives rise to a unique instantiation of the machine, as it explores and expresses its experiences.</p>
	  
	  <a name="artwork5"></a>
      <hr class="bs-docs-separator">
      <h4>Surface - Xbox Controlled Hot Wire Foam Cutter</h4>

      <p>Freddie Taewoo Hong.</p>
      <p>This artwork is a 3-axis sculpting instrument controlled by an Xbox controller, which allows anyone to intuitively apply one’s creativity in a real-time flow without the aid of pre-drawn digital geometry. Surface runs purely on user instinct rather than on any digital geometry. The artwork explores the ambiguous boundary between the analogue and digital; it also challenges conventional methods of digital fabrication, which rely vitally on CAD software.</p>
	  
	  <br/>
	  
	  <h2>Demos</h2><br/>

      <a name="demo1"></a>
      <h4>Artistic Sketching for Expressive Coding</h4>

      <p>Elodie Fourquet.</p>
      <p>This experiential paper describes using computer graphics and animation to motivate students taking their first programming course. An artistic context encourages students to create expressive images and animations. Their creative work consists in first abstracting a piece of art as a paper sketch, which they then abstract into code. Assessing the artistic merit of this activity will help our research community quest to better understand aesthetic, perception and meaning of visual representations [DS10].</p>
	  
	  <a name="demo2"></a>
      <hr class="bs-docs-separator">
      <h4>Sketch-Based Modeling of Parametric Shapes</h4>

      <p>Bastien Wailly and Adrien Bousseau.</p>
      <p>We demonstrate a sketch-based modeling system running on a multi-touch pen tablet. Our system takes inspiration from the work of Nishida et al. [NGDGA∗16], who proposed to use deep convolutional networks to interpret sketches of parametric shapes. While Nishida et al. applied this approach to the creation of procedural buildings, we focus on the creation of simple shapes (cuboids, cylinders, cones, spheres, pyramids) that users can assemble to create more complex objects. In this poster we describe the main components of our system – the deep convolutional networks used for sketch interpretation, the training data, the user interface, and the overall software architecture that combines these components. We will allow conference attendees to test our system on a pen tablet.</p>
	  
	  <br/>

      <h2>Posters</h2><br/>
      <a name="posters"></a>

      <a name="poster1"></a>
      <h4>Visual Communication with Successive Reading of Public and Secret Information by Generating Dual-Layer Images</h4>

      <p>Karim Hammoudi, Halim Benhabiles, Mahmoud Melkemi, and Shashank Rao Kadapanatham.</p>
      <p>In visual communication, visual cryptography is a technique that permits to share secret information through a two-step process. In a common processing scheme, two key images (ciphered images) are generated from a binary secret image. Then, the generated key images are sent to a recipient via two different communication channels. Once key images collected, the secret information is decoded via the human vision system by observing the superposition of the two key images. In this context, each key image generally has its appearance as a mix of black and white pixels. In this paper, we present a technique that permits to personalize the appearance of generated key images by making them exploitable for displaying visible information (e.g.; textual information) while simultaneously embedding secret information. A family of dual-layer images is thus highlighted towards fostering the development of visual creations. Experimental results show visual applications with successive reading of public and secret information from generated Dual-Layer key images.</p>

</div><!--/span-->
