---
title: 'WaterBench: Towards Holistic Evaluation of Watermarks for
Large Language Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shangqing Tu
  - admin
  - Yushi Bai
  - Jifan Yu
  - Lei Hou
  - Juanzi Li

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-11-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: Preprint In [Arxiv 2311.07138](https://arxiv.org/abs/2311.07138)
publication_short: Preprint In *Arxiv*

abstract: "To mitigate the potential misuse of large language models (LLMs), recent research has developed watermarking algorithms, which restrict the generation process to leave an invisible trace for watermark detection. Due to the two-stage nature of the task, most studies evaluate the generation and detection separately, thereby presenting a challenge in unbiased, thorough, and applicable evaluations. In this paper, we introduce WaterBench, the first comprehensive benchmark for LLM watermarks, in which we design three crucial factors: (1) For benchmarking procedure, to ensure an apples-to-apples comparison, we first adjust each watermarking method’s hyper-parameter to reach the same watermarking strength, then jointly evaluate their generation and detection performance. (2) For task selection, we diversify the input and output length to form a five-category taxonomy, covering 9 tasks. (3) For evaluation metric, we adopt the GPT4-Judge for automatically evaluating the decline of instruction following abilities after watermarking. We evaluate 4 open-source watermarks on 2 LLMs under 2 watermarking strengths and observe the common struggles for current methods on maintaining the generation quality."

# Summary. An optional shortened abstract.
summary: "In this paper, we introduce WaterBench, the first comprehensive benchmark for LLM watermarks, in which we design three crucial factors:..."

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: './2311.07138.pdf'
url_code: 'https://github.com/THU-KEG/WaterBench'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
