+++
abstract = "Analysis and detection of complex events in videos require a semantic representation of the video content. Existing video semantic representation methods typically require users to pre-define an exhaustive concept lexicon and manually annotate the presence of the concepts in each video, which is infeasible for real-world video event detection problems. In this paper, we propose an automatic semantic concept discovery scheme by exploiting Internet images and their associated tags. Given a target event and its textual descriptions, we crawl a collection of images and their associated tags by performing text based image search using the noun and verb pairs extracted from the event textual descriptions. The system first identifies the candidate concepts for an event by measuring whether a tag is a meaningful word and visually detectable. Then a concept visual model is built for each candidate concept using a SVM classifier with probabilistic output. Finally, the concept models are applied to generate concept based video representations. We use the TRECVID Multimedia Event Detection (MED) 2013 as our video test set and crawl 400K Flickr images to automatically discover 2, 000 visual concepts. We show significant performance gains of the proposed concept discovery method over different video event detection tasks including supervised event modeling over concept space and semantic based zero-shot retrieval without training examples. Importantly, we show the proposed method of automatic concept discovery outperforms other well-known concept library construction approaches such as Classemes and ImageNet by a large margin (228%) in zero-shot event retrieval. Finally, subjective evaluation by humans also confirms clear superiority of the proposed method in discovering concepts for event representation."
abstract_short = ""
authors = ["Jiawei Chen*", "**Yin Cui***", "Guangnan Ye", "Dong Liu", "Shih-Fu Chang (*equal contribution)"]
date = "2014-04-01"
image_preview = "paper/ICMR14_FlickrConcept.jpg"
math = true
publication_types = ["1"]
publication = "In *Proceedings of International Conference on Multimedia Retrieval (ICMR)*, 2014."
publication_short = "In *ICMR*, 2014"
selected = true
title = "Event-Driven Semantic Concept Discovery by Exploiting Weakly Tagged Internet Images"
url_pdf = "/~ycui/papers/ICMR14_FlickrConcept.pdf"
# url_data = "#"
# url_code = "#"
# url_arxiv = "#"
url_bixtex = "/~ycui/bibtex/ICMR14_FlickrConcept.txt"
# url_extendedabstract = "#"
# url_poster = "#"
url_slides = "/~ycui/slides/ICMR14_FlickrConcept.pdf"
# url_video = "#"

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
