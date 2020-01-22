---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: boston_skyline1.jpg
  caption: (image credit)
  caption_url: https://www.flickr.com/photos/13382424@N00/5230714594/
widget1:
  title: "From DNase-seq to TF binding"
  url: '/research/piq'
  image: nbt-2.png
  text: 'We describe protein interaction quantitation (PIQ), 
a computational method for modeling the magnitude and 
shape of genome-wide DNase I hypersensitivity profiles to 
identify transcription factor (TF) binding sites.'
widget2:
  title: "High-throughput mapping of regulatory DNA"
  url: '/research/mera'
  image: nbt.3468-F1.png
  text: 'Here, we present the multiplexed editing regulatory assay (MERA), a high-throughput CRISPR-Cas9–based approach that analyzes the functional impact of the regulatory genome in its native context. Using this approach, we identify unmarked regulatory elements (UREs) that control gene expression but do not have typical enhancer epigenetic or chromatin features.'
widget3:
  title: "Interpretation non-coding variants"
  url: '/research/gerv'
  image: gerv-img2.jpg
  text: 'We present GERV, a novel computational method for predicting regulatory variants that affect transcription factor binding. GERV learns a k-mer-based generative model of transcription factor binding from ChIP-seq and DNase-seq data, and scores variants by the change of predicted ChIP-seq reads between the reference and alternate allele.'

permalink: /index.html
---
