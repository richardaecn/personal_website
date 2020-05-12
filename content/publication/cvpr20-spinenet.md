+++
abstract = "Convolutional neural networks typically encode an input image into a series of intermediate features with decreasing resolutions. While this structure is suited to classification tasks, it does not perform well for tasks requiring simultaneous recognition and localization (e.g., object detection). The encoder-decoder architectures are proposed to resolve this by applying a decoder network onto a backbone model designed for classification tasks. In this paper, we argue encoder-decoder architecture is ineffective in generating strong multi-scale features because of the scale-decreased backbone. We propose SpineNet, a backbone with scale-permuted intermediate features and cross-scale connections that is learned on an object detection task by Neural Architecture Search. Using similar building blocks, SpineNet models outperform ResNet-FPN models by 3%+ AP at various scales while using 10-20% fewer FLOPs. In particular, SpineNet-190 achieves 52.1% AP on COCO for a single model without test-time augmentation, significantly outperforms prior art of detectors. SpineNet can transfer to classification tasks, achieving 5% top-1 accuracy improvement on a challenging iNaturalist fine-grained dataset. Code is at: https://github.com/tensorflow/tpu/tree/master/models/official/detection"
abstract_short = ""
authors = ["Xianzhi Du", "Tsung-Yi Lin", "Pengchong Jin", "Golnaz Ghiasi", "Mingxing Tan", "**Yin Cui**", "Quoc V Le", "Xiaodan Song"]
date = "2020-06-13"
publishdate = "2020-05-01"
image = "paper/CVPR20_SpineNet_detailed.png"
image_preview = "paper/CVPR20_SpineNet.png"
math = true
publication_types = ["1"]
publication = "*CVPR* 2020"
publication_short = "*CVPR* 2020"
selected = true
title = "SpineNet: Learning Scale-Permuted Backbone for Recognition and Localization"

url_details = "publication/cvpr20-spinenet"
url_arxiv = "https://arxiv.org/abs/1912.05027"
# url_pdf = ""
# url_data = ""
url_code = "https://github.com/tensorflow/tpu/tree/master/models/official/detection"
url_bixtex = "bibtex/CVPR20_SpineNet.txt"
# url_extendedabstract = "#"
# url_poster = "#"
# url_slides = "#"
# url_video = "#"

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
