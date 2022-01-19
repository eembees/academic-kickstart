---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Generative Modelling of Sequential Data"
summary: ""

abstract: ""
authors: []
tags: [academic, machine-learning]
categories: [academic, machine-learning]
# url_preprint: "https://doi.org/10.21203/rs.3.rs-75642/v1"
publication_types: ["7"]
date: 2022-01-12T12:00:00+01:00
lastmod: 2022-01-13T11:14:47+01:00
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



# WaveNet Samples:
## Librispeech
{{<audio src="files/msc/audio/S8_LIBRI_100H_samples_150_1.wav" caption="WaveNet (S=8 N=5 L=10 C=32) trained on Librispeech 100h-clean - Sample" format="audio/wav" >}}

## TIMIT
{{<audio src="files/msc/audio/S2_N5_L10_C32_sample.wav" caption="WaveNet (S=2 N=5 L=10 C=32) trained on TIMIT - Generated Sample" format="audio/wav" >}}
{{<audio src="files/msc/audio/S2_N5_L10_C64_sample.wav" caption="WaveNet (S=2 N=5 L=10 C=64) trained on TIMIT - Generated Sample" format="audio/wav" >}}
{{<audio src="files/msc/audio/S2_N5_L10_C92_sample.wav" caption="WaveNet (S=2 N=5 L=10 C=92) trained on TIMIT - Generated Sample" format="audio/wav" >}}
{{<audio src="files/msc/audio/S4_N5_L10_C32_sample.wav" caption="WaveNet (S=4 N=5 L=10 C=32) trained on TIMIT - Generated Sample" format="audio/wav" >}}
{{<audio src="files/msc/audio/S4_N5_L10_C64_sample.wav" caption="WaveNet (S=4 N=5 L=10 C=64) trained on TIMIT - Generated Sample" format="audio/wav" >}}
{{<audio src="files/msc/audio/S4_N5_L10_C92_sample.wav" caption="WaveNet (S=4 N=5 L=10 C=92) trained on TIMIT - Generated Sample" format="audio/wav" >}}
{{<audio src="files/msc/audio/S8_N5_L10_C32_sample.wav" caption="WaveNet (S=8 N=5 L=10 C=32) trained on TIMIT - Generated Sample" format="audio/wav" >}}
{{<audio src="files/msc/audio/S8_N5_L10_C64_sample.wav" caption="WaveNet (S=8 N=5 L=10 C=64) trained on TIMIT - Generated Sample" format="audio/wav" >}}
{{<audio src="files/msc/audio/S8_N5_L10_C92_sample.wav" caption="WaveNet (S=8 N=5 L=10 C=92) trained on TIMIT - Generated Sample" format="audio/wav" >}}
{{<audio src="files/msc/audio/S16_N5_L10_C32_sample.wav" caption="WaveNet (S=16 N=5 L=10 C=32) trained on TIMIT - Generated Sample" format="audio/wav" >}}
{{<audio src="files/msc/audio/S16_N5_L10_C64_sample.wav" caption="WaveNet (S=16 N=5 L=10 C=64) trained on TIMIT - Generated Sample" format="audio/wav" >}}
{{<audio src="files/msc/audio/S16_N5_L10_C92_sample.wav" caption="WaveNet (S=16 N=5 L=10 C=92) trained on TIMIT - Generated Sample" format="audio/wav" >}}




# WaveNet Reconstructions:
## Librispeech
{{<audio src="files/msc/audio/S8_LIBRI_100H_predictions_150_1.wav" caption="WaveNet (S=8 N=5 L=10 C=32) trained on Librispeech 100h-clean - Reconstruction" format="audio/wav" >}}
## TIMIT
{{<audio src="files/msc/audio/S2_N5_L10_C32_reconstruction.wav" caption="WaveNet (S=2 N=5 L=10 C=32) trained on TIMIT - Reconstruction" format="audio/wav" >}}
{{<audio src="files/msc/audio/S2_N5_L10_C64_reconstruction.wav" caption="WaveNet (S=2 N=5 L=10 C=64) trained on TIMIT - Reconstruction" format="audio/wav" >}}
{{<audio src="files/msc/audio/S2_N5_L10_C92_reconstruction.wav" caption="WaveNet (S=2 N=5 L=10 C=92) trained on TIMIT - Reconstruction" format="audio/wav" >}}
{{<audio src="files/msc/audio/S4_N5_L10_C32_reconstruction.wav" caption="WaveNet (S=4 N=5 L=10 C=32) trained on TIMIT - Reconstruction" format="audio/wav" >}}
{{<audio src="files/msc/audio/S4_N5_L10_C64_reconstruction.wav" caption="WaveNet (S=4 N=5 L=10 C=64) trained on TIMIT - Reconstruction" format="audio/wav" >}}
{{<audio src="files/msc/audio/S4_N5_L10_C92_reconstruction.wav" caption="WaveNet (S=4 N=5 L=10 C=92) trained on TIMIT - Reconstruction" format="audio/wav" >}}
{{<audio src="files/msc/audio/S8_N5_L10_C32_reconstruction.wav" caption="WaveNet (S=8 N=5 L=10 C=32) trained on TIMIT - Reconstruction" format="audio/wav" >}}
{{<audio src="files/msc/audio/S8_N5_L10_C64_reconstruction.wav" caption="WaveNet (S=8 N=5 L=10 C=64) trained on TIMIT - Reconstruction" format="audio/wav" >}}
{{<audio src="files/msc/audio/S8_N5_L10_C92_reconstruction.wav" caption="WaveNet (S=8 N=5 L=10 C=92) trained on TIMIT - Reconstruction" format="audio/wav" >}}
{{<audio src="files/msc/audio/S16_N5_L10_C32_reconstruction.wav" caption="WaveNet (S=16 N=5 L=10 C=32) trained on TIMIT - Reconstruction" format="audio/wav" >}}
{{<audio src="files/msc/audio/S16_N5_L10_C64_reconstruction.wav" caption="WaveNet (S=16 N=5 L=10 C=64) trained on TIMIT - Reconstruction" format="audio/wav" >}}
{{<audio src="files/msc/audio/S16_N5_L10_C92_reconstruction.wav" caption="WaveNet (S=16 N=5 L=10 C=92) trained on TIMIT - Reconstruction" format="audio/wav" >}}


