+++
abstract = "Existing fine-grained visual categorization methods often suffer from three challenges: lack of training data, large number of fine-grained categories, and high intra-class vs. low inter-class variance. In this work we propose a generic iterative framework for fine-grained categorization and dataset bootstrapping that handles these three challenges. Using deep metric learning with humans in the loop, we learn a low dimensional feature embedding with anchor points on manifolds for each category. These anchor points capture intra-class variances and remain discriminative between classes. In each round, images with high confidence scores from our model are sent to humans for labeling. By comparing with exemplar images, labelers mark each candidate image as either a \"true positive\" or a \"false positive.\" True positives are added into our current dataset and false positives are regarded as \"hard negatives\" for our metric learning model. Then the model is re-trained with an expanded dataset and hard negatives for the next round. To demonstrate the effectiveness of the proposed framework, we bootstrap a fine-grained flower dataset with 620 categories from Instagram images. The proposed deep metric learning scheme is evaluated on both our dataset and the CUB-200-2001 Birds dataset. Experimental evaluations show significant performance gain using dataset bootstrapping and demonstrate state-of-the-art results achieved by the proposed deep metric learning methods."
abstract_short = ""
authors = ["**Yin Cui**", "Feng Zhou", "Yuanqing Lin", "Serge Belongie"]
date = "2016-06-01"
image = "paper/CVPR16_FGVC_detailed.jpg"
image_preview = "paper/CVPR16_FGVC.jpg"
math = true
publication_types = ["1"]
publication = "*CVPR* 2016"
publication_short = "*CVPR* 2016"
selected = true
title = "Fine-Grained Categorization and Dataset Bootstrapping Using Deep Metric Learning With Humans in the Loop"

url_details = "publication/cvpr16-fgvc"
url_pdf = "http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Cui_Fine-Grained_Categorization_and_CVPR_2016_paper.pdf"
# url_data = "#"
# url_code = "#"
url_arxiv = "https://arxiv.org/abs/1512.05227"
url_bixtex = "bibtex/CVPR16_FGVC.txt"
# url_extendedabstract = "#"
url_poster = "posters/CVPR16_FGVC.pdf"
# url_slides = "#"
# url_video = "#"

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
