# BarMusComp: Encoding songs with linear and nonlinear compression methods to reveal structure #

Hello, and welcome on this repository!

This project aims at compressing all bars in a song, and studies the compressed representations of every bar to infer its structure. It is related to my PhD thesis [1].

This repository contains code for the NTD, PCA, NMF, and Autoencoders (developed in PyTorch), as presented in [2].

This project is an extension of the toolbox as_seg [3], which computes the segmentation of an autosimilarity matrix.

It can be installed with pip using `pip install barmuscomp`.

This is a first release, and may contain bug. Comments are welcomed!

## Software version ##

This code was developed with Python 3.8.5, and some external libraries detailed in dependencies.txt. They should be installed automatically if this project is downloaded using pip.

## Tutorial Notebook ##

3 tutorial notebooks are available in the folder "Notebooks", and present the different compression methods on the song 'Come Together'.

## Credits ##

Code was created by Axel Marmoret (<axel.marmoret@irisa.fr>), and strongly supported by Jeremy E. Cohen (<jeremy.cohen@irisa.fr>).

The technique in itself was also developed by Frédéric Bimbot (<bimbot@irisa.fr>).

## References ##
[1] Unsupervised Machine Learning Paradigms for the Representation of Music Similarity and Structure, PhD Thesis Marmoret Axel 
(not uploaded yet but will be soon! You should check the website hal.archives-ouvertes.fr/ in case this README is not updated with the reference.)

[2] Marmoret, A., Cohen, J.E, and Bimbot, F., "Barwise Compression Schemes for Audio-Based Music Structure Analysis"", in: 19th Sound and Music Computing Conference, SMC 2022, Sound and music Computing network, 2022.

[3] https://gitlab.inria.fr/amarmore/autosimilarity_segmentation - https://hal.archives-ouvertes.fr/hal-03797507