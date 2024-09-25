---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### **[Soft error vulnerability prediction of GPGPU applications](https://ieeexplore.ieee.org/abstract/document/9756720/)** <br />
- [ ] Journal: The Journal of Supercomputing Vol:70, Issue:6
- [x] [Paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=uj3eWlIAAAAJ&citation_for_view=uj3eWlIAAAAJ:d1gkVwhDpl0C), [Code](https://github.com/BT-MasterThesis/SoftErrorVulnerabilityPrediction-GPGPUs)

### **[Predicting the Soft Error Vulnerability of GPGPU Applications](https://ieeexplore.ieee.org/abstract/document/9756720/)** <br />
- [ ] Conference: 2022 30th Euromicro International Conference on Parallel, Distributed and Network-based Processing (PDP)
- [x] [Paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=uj3eWlIAAAAJ&citation_for_view=uj3eWlIAAAAJ:u-x6o8ySG0sC), [Code](https://github.com/BT-MasterThesis/SoftErrorVulnerabilityPrediction-GPGPU)

### **Performance Evaluation of CUDA Optimizations for Convolution Operations** <br />
- [ ] Conference: BASARIM 2022 - 7th High-Performance Computing Conference 
- [x] [Paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=uj3eWlIAAAAJ&citation_for_view=uj3eWlIAAAAJ:u5HHmVD_uO8C), [Code](https://github.com/BT-MasterThesis/Optimizing_ConvolutionAlgorithms_CUDA)


<font color="red">This text is red!</font>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
