---
title: "Towards Causal Credit Assignment"
authors:
- admin
date: "2022-12-22"
doi: "10.48550/arXiv.2212.11636"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint"
publication_short: ""

abstract: Adequately assigning credit to actions for future outcomes based on their contributions is a long-standing open challenge in Reinforcement Learning. The assumptions of the most commonly used credit assignment method are disadvantageous in tasks where the effects of decisions are not immediately evident. Furthermore, this method can only evaluate actions that have been selected by the agent, making it highly inefficient. Still, no alternative methods have been widely adopted in the field. Hindsight Credit Assignment is a promising, but still unexplored candidate, which aims to solve the problems of both long-term and counterfactual credit assignment. In this thesis, we empirically investigate Hindsight Credit Assignment to identify its main benefits, and key points to improve. Then, we apply it to factored state representations, and in particular to state representations based on the causal structure of the environment. In this setting, we propose a variant of Hindsight Credit Assignment that effectively exploits a given causal structure. We show that our modification greatly decreases the workload of Hindsight Credit Assignment, making it more efficient and enabling it to outperform the baseline credit assignment method on various tasks. This opens the way to other methods based on given or learned causal structures.

tags:
- Source Themes
featured: false

links:
url_pdf: https://arxiv.org/pdf/2212.11636.pdf
url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
