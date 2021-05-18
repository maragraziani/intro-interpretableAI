![Logo of the project](https://introinterpretableai.files.wordpress.com/2021/03/cropped-screenshot-2021-03-22-at-17.11.49.png)

# Introduction to AI Interpretability 
> Repository of the main source code for the assignments of the "Introduction to interpretable AI" course
> 
> Presented by: Mara Graziani (PhD student at HES-SO Valais and University of Geneva)
> Email: mara.graziani@hevs.ch

This repository contains a series of Colab notebooks that you will use as a backbone for the assignmets and practical exercises of the course Introduction to Interpretable AI, as of in the Spring semester of 2021.

The notebooks in this folder present exercises on
- Feature Visualization with the Lucid toolbox
- Gradient-weighted Class Activation Mapping (Grad-CAM) on you CNN classifier. This explainability technique generates a heatmap the relevant input features. 
- Concept-based explanations with Regression Concept Vectors.
The notebooks are applied on standard computer vision tasks. A specific application is presented for breast histopathology images at high-magnification (40x). 

## Installing / Getting started

The notebooks can be directly run in the Colab workspace, so no installation / or setup of virtual environments is needed. 
The notebook data_setup.ipynb will drive you through the data preparation steps. 
If you encounter any isses please let me know. 

## Developing

You can directly clone the folder to your computer to start developing
the project further:

```shell
git clone https://github.com/maragraziani/interpretAI_DigiPath
```

## Features

* Generate feature activation maximization
* Generate CAM heatmaps for imagenet-pretrained model
* Load your own model and weights to generate CAM
* Apply latest research to interpret your model with Regression Concept Vectors

## Links

Some useful links for more information about this hands-on session:

- Funding Project homepage: https://www.ai4media.eu/
- Repository: https://github.com/maragraziani/intro-interpretableAI
- Issue tracker: https://github.com/maragraziani/intro-interpretableAI/issues
- 
- Related projects:
  - Someone else's project: https://github.com/maragraziani/rcvtool/

## Licensing
The code in this project is licensed under MIT license.
