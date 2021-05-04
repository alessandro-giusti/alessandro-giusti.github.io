---
permalink: /research/fastscanning/
title: Fast Image Scanning with Deep Max-Pooling Convolutional Neural Networks
published: true
toc: true
---

Alessandro Giusti, Dan C. Ciresan, Jonathan Masci, Luca M. Gambardella, Juergen Schmidhuber  
ICIP 2013
       
## Abstract
Deep Neural Networks now excel at image classification, detection and segmentation.
When used to scan images by means of a sliding window, however, their high computational
complexity can bring even the most powerful hardware to its knees. We show how dynamic
programming can speedup the process by orders of magnitude, even when max-pooling layers
are present.

{% include figure image_path="/assets/images/research/icip2013-diagram-wide.png" %}

### Paper
* [Arxiv](http://arxiv.org/abs/1302.1700)
* [Proceedings](http://2013.ieeeicip.org/proc/pdfs/0004034.pdf)
* [Publisher](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6738831)

### Bibtex
```
@inproceedings{Giusti:2013a,
  author    = {Alessandro Giusti and
	       Dan Claudiu Ciresan and
	       Jonathan Masci and               
	       Luca Maria Gambardella and
               J{\"u}rgen Schmidhuber},
  title     = {Fast Image Scanning with Deep Max-Pooling Convolutional Neural Networks},
  booktitle = {ICIP},
  year      = {2013}
}
```