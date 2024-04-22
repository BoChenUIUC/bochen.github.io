---
title: "Vesper: Learning to Manage Uncertainty in Video Streaming"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bo Chen
  - Mingyuan Wu
  - Hongpeng Guo
  - Zhisheng Yan
  - Klara Nahrstedt
date: "2024-01-1T00:00:00Z"

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2022-08-05T00:00:00Z'
# doi: '10.1145/3524273.3528178'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: "The 15th ACM Multimedia Systems Conference"
publication_short: "MMSys'24"

abstract: "Video codecs are crucial in video streaming systems. However, the quantization operation in existing codecs introduces irreversible jitters. Moreover, the common practice of fitting a single codec to diverse video content lacks the flexibility to adapt the parameters of a codec for specific content. They lead to the problem of quantization and content uncertainty. Our preliminary study shows an ideal codec without uncertainty gains a significant advantage over the conventional codec with uncertainty. However, realizing the ideal codec presents tremendous challenges in the generalizability and the costs of computation, transmission, and delay. In this paper, we present Vesper, a video streaming system that innovatively tackles uncertainty with two learning-based components, super-precision and self-evolution. The super-precision module builds a neural network that predicts original feature values from quantized feature values, which effectively mitigates the impact of quantization without inducing generalizability issues. The self-evolution module performs content-aware adaptation on the encoder and replaces non-content-aware video segments with content-aware ones on the fly, which addresses content uncertainty without adding significant costs to on-demand streaming. Evaluations demonstrate Vesper's superior Quality of Experience compared to streaming systems built with state-of-the-art codecs."

# Summary. An optional shortened abstract.
# summary: Todo.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3625468.3647621'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

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

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
