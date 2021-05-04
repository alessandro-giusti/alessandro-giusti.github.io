---
permalink: /research/zstackvis/
title: Artificial Defocus for Displaying Markers in Microscopy Z-Stacks
published: true
toc: true
---

Alessandro Giusti, Pierluigi Taddei, Cristina Magli, Giorgio Corani, Luca M. Gambardella, Luca Gianaroli

IEEE Transactions on Visualization and Computer Graphics, 2011. **Honorable Mention award** recipient at IEEE VIS.

## Abstract
As microscopes have a very shallow depth of field, Z-stacks (i.e. sets of images shot at different focal planes) are often acquired to fully capture a thick sample. Such stacks are viewed by users by navigating them through the mouse wheel. We propose a new technique of visualizing 3D point, line or area markers in such focus stacks, by displaying them with a depth-dependent defocus, simulating the microscope's optics; this leverages on the microscopists' ability to continuously twiddle focus, while implicitly performing a shape-from-focus reconstruction of the 3D structure of the sample. User studies confirm that the approach is effective, and can complement more traditional techniques such as color-based cues. We provide two implementations, one of which computes defocus in real time on the GPU, and examples of their application.

## Paper
* [IEEE Xplore](http://ieeexplore.ieee.org/xpl/freeabs_all.jsp?arnumber=6064938).
* [Preprint](http://www.idsia.ch/~giusti/papers/2011/vis.pdf).

## Bibtex
```
@article{giusti2011artificial,
  title={Artificial Defocus for Displaying Markers in Microscopy Z-Stacks},
  author={Giusti, Alessandro and Taddei, Pierluigi and Corani, Giorgio and Gambardella, Luca and Magli, Cristina and Gianaroli, Luca},
  journal={Visualization and Computer Graphics, IEEE Transactions on},
  volume={17},
  number={12},
  pages={1757--1764},
  year={2011},
  publisher={IEEE}
}
```

## Implementation
We provide for research purposes only both software implementations described in the paper.  
* [Matlab prototype](http://www.idsia.ch/~giusti/papers/2011/vis-matlab.zip)
* [Java+OpenGL Prototype](http://www.idsia.ch/~giusti/papers/2011/vis-java.zip) 
Please read included README

## Videos

Basic interaction techniques
{% include video id="wIqimGSSfz0" provider="youtube" %}

Complex interaction techniques: validating & correcting the segmentation of a 4-cell embryo
{% include video id="k_kecTNV2Mw" provider="youtube" %}

A ruler and protractor
{% include video id="8o7L82m5x2E" provider="youtube" %}

Pointless toys
{% include video id="5ceQGXOkzz4" provider="youtube" %}