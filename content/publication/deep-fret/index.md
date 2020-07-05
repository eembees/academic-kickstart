---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "DeepFRET"
subtitle: "Rapid and automated single molecule FRET data classification using deep learning"
summary: "Single molecule Förster Resonance energy transfer (smFRET) is a mature and adaptable method for studying the structure of biomolecules and integrating their dynamics into structural biology. 
The development of high throughput methodologies and ... "

abstract: "
Single molecule Förster Resonance energy transfer (smFRET) is a mature and adaptable method for studying the structure of biomolecules and integrating their dynamics into structural biology. 
The development of high throughput methodologies and the growth of commercial instrumentation have outpaced the development of rapid, standardized, and fully automated methodologies to objectively analyze the wealth of produced data. 
Here we present DeepFRET, an automated standalone solution based on deep learning, where the only crucial human intervention in transiting from raw microscope images to histogram of biomolecule behavior, is a user-adjustable quality threshold. 
Integrating all standard features of smFRET analysis, DeepFRET will consequently output common kinetic information metrics for biomolecules. 
We validated the utility of DeepFRET by performing quantitative analysis on simulated, ground truth, data and real smFRET data. 
The accuracy of classification by DeepFRET outperformed human operators and current commonly used hard threshold and reached >95% precision accuracy only requiring a fraction of the time (<1% as compared to human operators) on ground truth data. 
Its flawless and rapid operation on real data demonstrates its wide applicability. 
This level of classification was achieved without any preprocessing or parameter setting by human operators, demonstrating DeepFRET’s capacity to objectively quantify biomolecular dynamics. 
The provided a standalone executable based on open source code capitalises on the widespread adaptation of machine learning and may contribute to the effort of benchmarking smFRET for structural biology insights ."
authors: []
tags: [academic, machine-learning, biophysics]
categories: [academic, machine-learning, biophysics]
url_code: "https://github.com/hatzakislab/DeepFRET-GUI"
url_preprint: "https://www.biorxiv.org/content/10.1101/2020.06.26.173260v1"
publication_types: ["3"]
publication: "[BioRxiv](https://www.biorxiv.org/)"
date: 2020-06-25T15:19:33+02:00
lastmod: 2020-06-25T15:19:33+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
