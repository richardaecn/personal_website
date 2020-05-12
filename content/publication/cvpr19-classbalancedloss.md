+++
abstract = "With the rapid increase of large-scale, real-world datasets, it becomes critical to address the problem of long-tailed data distribution (i.e., a few classes account for most of the data, while most classes are under-represented). Existing solutions typically adopt class re-balancing strategies such as re-sampling and re-weighting based on the number of observations for each class. In this work, we argue that as the number of samples increases, the additional benefit of a newly added data point will diminish. We introduce a novel theoretical framework to measure data overlap by associating with each sample a small neighboring region rather than a single point. The effective number of samples is defined as the volume of samples and can be calculated by a simple formula. We design a re-weighting scheme that uses the effective number of samples for each class to re-balance the loss, thereby yielding a class-balanced loss. Comprehensive experiments are conducted on artificially induced long-tailed CIFAR datasets and large-scale datasets including ImageNet and iNaturalist. Our results show that when trained with the proposed class-balanced loss, the network is able to achieve significant performance gains on long-tailed datasets."
abstract_short = ""
authors = ["**Yin Cui**", "Menglin Jia", "Tsung-Yi Lin", "Yang Song", "Serge Belongie"]
date = "2019-01-16"
publishdate = "2019-01-16"
image = "paper/CVPR19_ClassBalancedLoss_detailed.png"
image_preview = "paper/CVPR19_ClassBalancedLoss.png"
math = true
publication_types = ["1"]
publication = "*CVPR* 2019"
publication_short = "*CVPR* 2019"
selected = true
title = "Class-Balanced Loss Based on Effective Number of Samples"

url_details = "publication/cvpr19-classbalancedloss"
url_arxiv = "https://arxiv.org/abs/1901.05555"
# url_pdf = ""
# url_data = ""
url_code = "https://github.com/richardaecn/class-balanced-loss"
url_bixtex = "bibtex/CVPR19_ClassBalancedLoss.txt"
# url_extendedabstract = "#"
url_poster = "posters/CVPR19_Class-Balanced.pdf"
# url_slides = "#"
# url_video = "#"

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
