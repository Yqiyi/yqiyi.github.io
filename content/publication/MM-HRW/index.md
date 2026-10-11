---
title: "A New Weight Function for Highest Random Weight Scheme and its Efficient Lookup Implementations"
authors:
- Muhammad Waqas
- Sian-Jheng Lin
- Bin Liu
- admin
- Adnan Fazil
date: "2026-08-06T00:00:00Z"
doi: "https://doi.org/10.1016/j.future.2026.108711"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-08-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Future Generation Computer Systems"
publication_short: "FGCS"

abstract: "Cloud infrastructures have become increasingly popular among distributed applications in the modern era due to their efficient failure recovery, global reach, mobility, and service integration. The Highest Random Weight (HRW) is one of the Consistent Hashing (CH) schemes that offers indefinite scalability while maintaining consistency, lookup, minimal dispersal, and load balancing in cloud environments. However, as systems scale, existing HRW and other CH variants face mounting challenges, including high memory usage, performance degradation due to rehashing and 𝑂⁡(𝑤) comparisons during lookup operations. This paper suggests a weight function for the Highest Random Weight (HRW) scheme, termed as Multiplication Modulo-based Highest Random Weight (MM-HRW) scheme. In the MM-HRW scheme, the entire key range can be divided into several nonoverlapping ranges, and each range corresponds to a working node. By applying binary search on the ranges, we can find out the working node of a key with 𝑂⁡(log⁡𝑤) comparisons. Additionally, we present the corresponding algorithms, implementations, and mathematical validation to support the experimental findings. The results demonstrate that MM-HRW consistently achieves an affordable memory footprint, validating its scalability across various scenarios. Additionally, by considering a small, medium and large cluster size, MM-HRW scheme achieves a high and stable lookup rate while maintaining 𝑂⁡(log⁡𝑤) comparisons across all scenarios."

# Summary. An optional shortened abstract.
summary: "Cloud infrastructures have become increasingly popular among distributed applications in the modern era due to their efficient failure recovery, global reach, mobility, and service integration. The Highest Random Weight (HRW) is one of the Consistent Hashing (CH) schemes that offers indefinite scalability while maintaining consistency, lookup, minimal dispersal, and load balancing in cloud environments. However, as systems scale, existing HRW and other CH variants face mounting challenges, including high memory usage, performance degradation due to rehashing and 𝑂⁡(𝑤) comparisons during lookup operations. This paper suggests a weight function for the Highest Random Weight (HRW) scheme, termed as Multiplication Modulo-based Highest Random Weight (MM-HRW) scheme. In the MM-HRW scheme, the entire key range can be divided into several nonoverlapping ranges, and each range corresponds to a working node. By applying binary search on the ranges, we can find out the working node of a key with 𝑂⁡(log⁡𝑤) comparisons. Additionally, we present the corresponding algorithms, implementations, and mathematical validation to support the experimental findings. The results demonstrate that MM-HRW consistently achieves an affordable memory footprint, validating its scalability across various scenarios. Additionally, by considering a small, medium and large cluster size, MM-HRW scheme achieves a high and stable lookup rate while maintaining 𝑂⁡(log⁡𝑤) comparisons across all scenarios."

tags:
- Distributed Algorithms
- Consistent Hashing

featured: false

links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
url_project: ''
url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<div style="display:none">

</div>
