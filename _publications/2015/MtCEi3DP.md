---
layout: publication
title: Microstructures to Control Elasticity in 3D Printing

authors: 
  - name: Schumacher, Christian
    url: https://graphics.ethz.ch/~chschuma/
    affiliations: [1,2]
  - name: Bickel, Bernd
    url: http://berndbickel.com
    affiliations: [1,3]
  - name: Marschner, Steve
    affiliations: [4]
  - name: Rys, Jan
    affiliations: [2]
  - name: Daraio, Chiara
    affiliations: [2]
  - name: Gross, Markus
    affiliations: [1,2]

affiliations:
  - name: Disney Research Zurich
    url: http://www.disneyresearch.com/research-labs/disney-research-zurich/
  - name: ETH Zurich
    url: http://www.ethz.ch/
  - name: IST Austria
    url: http://ist.ac.at
  - name: Cornell University
    url: https://www.cornell.edu/

publication: ACM Trans. Graph. 34, 4 (SIGGRAPH 2015 Papers)
date: 2015-08-01

abstract: |
  We propose a method for fabricating deformable objects with spatially varying elasticity using 3D printing.
  Using a single, relatively stiff printer material, our method designs an assembly of small-scale 
  microstructures that have the effect of a softer material at the object scale, with properties depending
  on the microstructure used in each part of the object. We build on work in the area of metamaterials,
  using numerical optimization to design tiled microstructures with desired properties, but with the key
  difference that our method designs families of related structures that can be interpolated to smoothly
  vary the material properties over a wide range. To create an object with spatially varying elastic
  properties, we tile the object's interior with microstructures drawn from these families, generating a
  different microstructure for each cell using an efficient algorithm to select compatible structures for
  neighboring cells. We show results computed for both 2D and 3D objects, validating several 2D and 3D
  printed structures using standard material tests as well as demonstrating various example applications.

teaser:
  image:
    - url: MtCEi3DP.jpg
      alt: Microstructures to Control Elasticity in 3D Printing

grp: bickel
paper: http://pub.ist.ac.at/~bbickel/downloads/Microstructures-to-Control-Elasticity-in-3D-Printing-Paper.pdf
---

## {{ page.title }}

{% include figure.html images=page.teaser.image %}

{% include authors.html authors=page.authors affiliations=page.affiliations %}

{% include publication.html publication=page.publication %}

### Abstract

{{ page.abstract }}

### Supplementary video

{% include youtube.html id='T_ibOR2owQc' %}

### Links

![Paper](paper.jpg) Paper [PDF]({{page.paper}})
