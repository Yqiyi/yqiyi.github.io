---
title: "PURA: Provably Unbiased and Robust Multi-Bit Watermarking for AI-Generated Text Attribution"
authors:
- Yaofei Wang
- Jinyang Guo
- Shuchao Du
- Chao Wang
- admin
- Donghui Hu
- Weiming Zhang
- Nenghai Yu
- Kejiang Chen
date: "2026-11-14T00:00:00Z"
doi: "10.1145/3830454.3846709"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-11-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *2026 ACM SIGSAC Conference on Computer and Communications Security*
publication_short: In *CCS '26*

abstract: "Fine-grained attribution of AI-generated text is becoming increasingly important for accountability and auditing, yet existing multi-bit watermarking methods still struggle to simultaneously preserve the base generation distribution, support high-capacity payloads, and remain recoverable after editing. We present PURA, a provably unbiased and robust multi-bit watermarking method for text attribution. Instead of perturbing token probabilities directly, PURA embeds payloads in the latent sampling space via keyed inverse transform sampling, and recovers them by treating observed tokens as soft interval evidence and aggregating such evidence across the sequence. This design preserves the base generation distribution exactly while substantially improving recovery stability under post-editing and channel perturbations. Building on this recovery paradigm, we further develop a unified robustness analysis and show that, under bounded attack strength, the per-bit error probability decays exponentially with sequence length. Extensive experiments show that PURA substantially outperforms existing unbiased baselines in the high-payload regime. For example, when embedding 36 bits in 200 tokens, PURA achieves a 91.7% message match rate, more than three times that of the strongest unbiased baseline, while preserving text quality and remaining statistically close to unwatermarked text, and incurring only millisecond-level verification overhead. Our code is available at https://github.com/anshigaoa/PURA."

# Summary. An optional shortened abstract.
summary: "Fine-grained attribution of AI-generated text is becoming increasingly important for accountability and auditing, yet existing multi-bit watermarking methods still struggle to simultaneously preserve the base generation distribution, support high-capacity payloads, and remain recoverable after editing. We present PURA, a provably unbiased and robust multi-bit watermarking method for text attribution. Instead of perturbing token probabilities directly, PURA embeds payloads in the latent sampling space via keyed inverse transform sampling, and recovers them by treating observed tokens as soft interval evidence and aggregating such evidence across the sequence. This design preserves the base generation distribution exactly while substantially improving recovery stability under post-editing and channel perturbations. Building on this recovery paradigm, we further develop a unified robustness analysis and show that, under bounded attack strength, the per-bit error probability decays exponentially with sequence length. Extensive experiments show that PURA substantially outperforms existing unbiased baselines in the high-payload regime. For example, when embedding 36 bits in 200 tokens, PURA achieves a 91.7% message match rate, more than three times that of the strongest unbiased baseline, while preserving text quality and remaining statistically close to unwatermarked text, and incurring only millisecond-level verification overhead. Our code is available at https://github.com/anshigaoa/PURA."

tags:
- Watermarking
- Generative AI Watermarking

featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3830454.3846709
url_code: 'https://github.com/anshigaoa/PURA'
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
#   slides: example
---
<div style="display:none">

</div>
