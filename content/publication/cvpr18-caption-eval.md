+++
abstract = "Evaluation metrics for image captioning face two challenges. Firstly, commonly used metrics such as CIDEr, METEOR, ROUGE and BLEU often do not correlate well with human judgments. Secondly, each metric has well known blind spots to pathological caption constructions, and rule-based metrics lack provisions to repair such blind spots once identified. For example, the newly proposed SPICE correlates well with human judgments, but fails to capture the syntactic structure of a sentence. To address these two challenges, we propose a novel learning based discriminative evaluation metric that is directly trained to distinguish between human and machine-generated captions. In addition, we further propose a data augmentation scheme to explicitly incorporate pathological transformations as negative examples during training. The proposed metric is evaluated with three kinds of robustness tests and its correlation with human judgments. Extensive experiments show that the proposed data augmentation scheme not only makes our metric more robust toward several pathological transformations, but also improves its correlation with human judgments. Our metric outperforms other metrics on both caption level human correlation in Flickr 8k and system level human correlation in COCO. The proposed approach could be served as a learning based evaluation metric that is complementary to existing rule-based metrics."
abstract_short = ""
authors = ["**Yin Cui**", "Guandao Yang", "Andreas Veit", "Xun Huang", "Serge Belongie"]
date = "2018-06-01"
publishdate = "2018-05-01"
image = "paper/CVPR18_caption_eval_detailed.png"
image_preview = "paper/CVPR18_caption_eval.png"
math = true
publication_types = ["1"]
publication = "*CVPR* 2018"
publication_short = "*CVPR* 2018"
selected = true
title = "Learning to Evaluate Image Captioning"

url_details = "publication/cvpr18-fgvc"
url_pdf = "https://vision.cornell.edu/se3/wp-content/uploads/2018/03/1501.pdf"
# url_data = "#"
url_code = "https://github.com/richardaecn/cvpr18-caption-eval"
# url_arxiv = ""
url_bixtex = "bibtex/CVPR18_caption_eval.txt"
# url_extendedabstract = "#"
# url_poster = "posters/CVPR17_FGVC.pdf"
# url_slides = "#"
# url_video = "#"

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
