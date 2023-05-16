---
layout: publication
title: "Monocular Reconstruction of Neural Face Reflectance Fields"

authors:
  - name: B R, Mallikarjun 
    affiliations: [1]
    url: 
  - name: Tewari, Ayush
    affiliations: [1]
    url: https://people.mpi-inf.mpg.de/~atewari/
  - name: Oh, Tae-Hyun
    affiliations: [2]
    url: https://ami.postech.ac.kr/members/tae-hyun-oh
  - name: Weyrich, Tim
    affiliations: [3]
    url: https://reality.cs.ucl.ac.uk/weyrich.html
  - name: Bickel, Bernd
    affiliations: [4]
    url: https://berndbickel.com/
  - name: Seidel, Hans-Peter
    affiliations: [1]
    url: https://people.mpi-inf.mpg.de/~hpseidel/
  - name: Pfister, Hanspeter
    affiliations: [5]
    url: https://vcg.seas.harvard.edu/people/hanspeter-pfister
  - name: Matusik, Wojciech
    affiliations: [6]
    url: https://cdfg.mit.edu/wojciech
  - name: Elgharib, Mohamed
    affiliations: [1]
    url: https://people.mpi-inf.mpg.de/~elgharib/
  - name: Theobalt, Christian
    affiliations: [1]
    url: https://people.mpi-inf.mpg.de/~theobalt/

affiliations:
  - name: Max Planck Institute for Informatics, Saarland Informatics Campus
    url: https://ist.ac.at
  - name: POSTECH
    url: https://postech.ac.kr/eng/
  - name: University College London
    url: https://www.ucl.ac.uk/
  - name: IST Austria
    url: https://ist.ac.at
  - name: Harvard University
    url: https://www.harvard.edu/
  - name: MIT CSAIL
    url: https://www.csail.mit.edu/    

publication: Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition
date: 2021-06-09


bibtex: |
  @inproceedings{tewari2021monocular,
    title={Monocular Reconstruction of Neural Face Reflectance Fields},
    author={Tewari, Ayush and Oh, Tae-Hyun and Weyrich, Tim and Bickel, Bernd and Seidel, Hans-Peter and Pfister, Hanspeter and Matusik, Wojciech and Elgharib, Mohamed and Theobalt, Christian and others},
    booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
    pages={4791--4800},
    year={2021}
  }



grp: bickel
paper: https://openaccess.thecvf.com/content/CVPR2021/papers/R_Monocular_Reconstruction_of_Neural_Face_Reflectance_Fields_CVPR_2021_paper.pdf

abstract: |
  The reflectance field of a face describes the reflectance properties responsible for complex lighting effects including diffuse, specular, inter-reflection and self shadowing. Most existing methods for estimating the face reflectance from a monocular image assume faces to be diffuse with very few approaches adding a specular component. This still leaves out important perceptual aspects of reflectance as higher-order global illumination effects and self-shadowing are not modeled. We present a new neural representation for face reflectance where we can estimate all components of the reflectance responsible for the final appearance from a single monocular image. Instead of modeling each component of the reflectance separately using parametric models, our neural representation allows us to generate a basis set of faces in a geometric deformation-invariant space, parameterized by the input light direction, viewpoint and face geometry. We learn to reconstruct this reflectance field of a face just from a monocular image, which can be used to render the face from any viewpoint in any light condition. Our method is trained on a light-stage training dataset, which captures 300 people illuminated with 150 light conditions from 8 viewpoints. We show that our method outperforms existing monocular reflectance reconstruction methods, in terms of photorealism due to better capturing of physical premitives, such as sub-surface scattering, specularities, self-shadows and other higher-order effects.


teaser:
  caption: |

  images:
  - url: teaser.jpg
    alt: Monocular Reconstruction of Neural Face Reflectance Fields (Teaser Image)

---

## {{ page.title }}

{% include figure.html caption=page.teaser.caption images=page.teaser.images columns=1 %}

{% include authors.html authors=page.authors affiliations=page.affiliations %}

{% include publication.html publication=page.publication url=page.doi %}

### Abstract

{{ page.abstract }}

### Resources

* [Paper (17 MB)]({{ page.paper }})

<!--
* [Official publisher page]({{page.doi}}) &nbsp; [![ACM](ACM_logo.svg){: width="40x"}]({{page.doi}})
-->

### Citation

{% include citation.html citation=page.bibtex %}


### Acknowledgements
We thank Tarun Yenamandra and Duarte David for helping us with the comparisons. This work was supported by the ERC Consolidator Grant 4DReply (770784). We also acknowledge support from Technicolor and Interdigital.

![EU](flag_yellow_low.jpg){: width="150x"}
![ERC](LOGO-ERC.jpg){: width="150px"}
