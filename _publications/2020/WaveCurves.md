---
layout: publication
title: "Wave Curves: Simulating Lagrangian water waves on dynamically deforming surfaces"

authors:
  - name: Skřivan, Tomáš
    affiliations: [1]
    url: https://pub.ist.ac.at/~tskrivan/
  - name: Söderström, Andreas
  - name: Johansson, John
    affiliations: [2]
  - name: Sprenger, Christoph
    affiliations: [2]
  - name: Museth, Ken
    affiliations: [2]
  - name: Wojtan, Chris
    affiliations: [1]
    url: http://pub.ist.ac.at/group_wojtan


affiliations:
  - name: IST Austria
    url: https://ist.ac.at
  - name: Weta Digital
    url: https://www.wetafx.co.nz/

publication: ACM Transactions on Graphics (SIGGRAPH 2020)
date: 2020-07-19

bibtex: |
  @article{skrivan2020wc,
    author    = {Skřivan, Tomáš and Söderström, Andreas and Johansson, John and Sprenger, Christoph and Museth, Ken and Wojtan, Chris},
    title     = {Wave Curves: Simulating Lagrangian water waves on dynamically deforming surfaces},
    journal   = {ACM Transactions on Graphics (TOG)},
    number    = {4},
    volume    = {39},
    year      = {2020},
    publisher = {ACM}
  }

paper: http://pub.ist.ac.at/group_wojtan/projects/2020_Skrivan_WaveCurves/wave_curves_2020.pdf
video: http://pub.ist.ac.at/group_wojtan/projects/2020_Skrivan_WaveCurves/wave_curves_main_with_authors.mp4
extravideo: http://pub.ist.ac.at/group_wojtan/projects/2020_Skrivan_WaveCurves/wave_curves_comparisons_with_authors.mp4

abstract: |
  We propose a method to enhance the visual detail of a water surface simulation. Our method works as a post-processing step which takes a simulation as input and increases its apparent resolution by simulating many detailed Lagrangian water waves on top of it. We extend linear water wave theory to work in non-planar domains which deform over time, and we discretize the theory using Lagrangian wave packets attached to spline curves. The method is numerically stable and trivially parallelizable, and it produces high frequency ripples with dispersive wave-like behaviors customized to the underlying fluid simulation.


teaser:
  caption: |

  images:
  - url: reprimg.jpg
    alt: representative image

---

## {{ page.title }}

{% include figure.html caption=page.teaser.caption images=page.teaser.images columns=1 %}

{% include authors.html authors=page.authors affiliations=page.affiliations %}

{% include publication.html publication=page.publication url=page.doi %}

### Abstract

{{ page.abstract }}

### Supplementary video

{% include youtube.html id='e7SqHnfV8rI' %}

### Links

* [Paper]({{ page.paper }})
* [Video File]({{ page.video }})
* [Additional Video]({{ page.extravideo }})

<!-- ### Citation -->

<!-- {% include citation.html citation=page.bibtex %} -->

### Acknowledgements

We wish to thank the anonymous reviewers and the members of the Visual Computing Group at IST Austria for their valuable feedback. This research was supported by the Scientific Service Units (SSU) of IST Austria through resources provided by Scientific Computing. This project has received funding from the European Research Council (ERC) under the European Union’s Horizon 2020 research and innovation programme under grant agreements No 638176 and Marie Sklodowska-Curie Grant Agreement No. 665385W.

![EU](flag_yellow_low.jpg){: width="150x"}
![ERC](LOGO-ERC.jpg){: width="150px"}