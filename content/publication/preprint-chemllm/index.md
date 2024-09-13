---
title: "ChemLLM: A Chemical Large Language Model"
authors:
- Di Zhang
- Wei Liu
- Qian Tan
- Jingdan Chen
- Hang Yan
- admin
- Jiatong Li
- Weiran Huang
- Xiangyu Yue
- Dongzhan Zhou
- Shufei Zhang
- Mao Su
- Hansen Zhong
- Yuqiang Li
- Wanli Ouyang
date: "2024-05-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["arXiv"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Large language models (LLMs) have made impressive progress in chemistry applications, including molecular property prediction, molecular generation, experimental protocol design, etc. However, the community lacks a dialogue-based model specifically designed for chemistry. The challenge arises from the fact that most chemical data and scientific knowledge are primarily stored in structured databases, and the direct use of these structured data compromises the model's ability to maintain coherent dialogue. To tackle this issue, we develop a novel template-based instruction construction method that transforms structured knowledge into plain dialogue, making it suitable for language model training. By leveraging this approach, we develop ChemLLM, the first large language model dedicated to chemistry, capable of performing various tasks across chemical disciplines with smooth dialogue interaction. ChemLLM beats GPT-3.5 on all three principal tasks in chemistry, i.e., name conversion, molecular caption, and reaction prediction, and surpasses GPT-4 on two of them. Remarkably, ChemLLM also shows exceptional adaptability to related mathematical and physical tasks despite being trained mainly on chemical-centric corpora. Furthermore, ChemLLM demonstrates proficiency in specialized NLP tasks within chemistry, such as literature translation and cheminformatic programming. ChemLLM opens up a new avenue for exploration within chemical studies, while our method of integrating structured chemical knowledge into dialogue systems sets a new frontier for developing LLMs across various scientific fields. Codes, Datasets, and Model …

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- AI for Science; Large Language Models

featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2402.06852
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
