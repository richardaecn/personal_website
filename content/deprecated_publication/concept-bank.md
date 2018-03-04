+++
abstract = "Concept-based video representation has proven to be effective in complex event detection. However, existing methods either manually design concepts or directly adopt concept libraries not specifically designed for events. In this paper, we propose to build Concept Bank, the largest concept library consisting of 4,876 concepts specifically designed to cover 631 real-world events. To construct the Concept Bank, we first gather a comprehensive event collection from WikiHow, a collaborative writing project that aims to build the world's largest manual for any possible How-To event. For each event, we then search Flickr and discover relevant concepts from the tags of the returned images. We train a Multiple Kernel Linear SVM for each discovered concept as a concept detector in Concept Bank. We organize the concepts into a five-layer tree structure, in which the higher-level nodes correspond to the event categories while the leaf nodes are the event-specific concepts discovered for each event. Based on such tree ontology, we develop a semantic matching method to select relevant concepts for each textual event query, and then apply the corresponding concept detectors to generate concept-based video representations. We use TRECVID Multimedia Event Detection 2013 and Columbia Consumer Video open source event definitions and videos as our test sets and show very promising results on two video event detection tasks: event modeling over concept space and zero-shot event retrieval. To the best of our knowledge, this is the largest concept library covering the largest number of real-world events."
abstract_short = ""
authors = ["**Yin Cui**", "Dong Liu", "Jiawei Chen", "Shih-Fu Chang"]
date = "2014-03-29"
image_preview = "paper/arXiv14_ConceptBank.jpg"
math = true
publication_types = ["3"]
publication = "*arXiv preprint arXiv:1403.7591*, 2014."
publication_short = "*arXiv*, 2014"
selected = true
title = "Building a large concept bank for representing events in video"
url_pdf = "https://arxiv.org/pdf/1403.7591.pdf"
# url_data = "#"
# url_code = "#"
url_arxiv = "https://arxiv.org/abs/1403.7591"
url_bixtex = "/~ycui/bibtex/arXiv14_ConceptBank.txt"
# url_extendedabstract = "#"
# url_poster = "#"
# url_slides = "#"
# url_video = "#"

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
