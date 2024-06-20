---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Using Benchmarking Infrastructure to Evaluate LLM Performance on CS Concept Inventories: Challenges, Opportunities, and Critiques"
authors: ["Murtaza Ali", "Prerna Rao", "Yifan Mai", "Benjamin Xie"]
date: 2024-06-15
doi: "10.1145/3632620.3671097"

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-04T13:49:23-08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM Conference on International Computing Education Research"
publication_short: "ICER 2024"

abstract: "BACKGROUND AND CONTEXT. The pace of advancement of large language models (LLMs) motivates the use of existing infrastructure to automate the evaluation of LLM performance on computing education tasks. Concept inventories are well suited for evaluation because of their careful design and prior validity evidence.


OBJECTIVES. Our research explores the feasibility of using an automated benchmarking framework to evaluate computer science (CS) concept inventories. We explore three primary objectives: evaluation of LLM performance on the SCS1 and BDSI concept inventories; informal expert panel review of items which had variations between LLM and expected student performance; and description of challenges with using benchmarking infrastructure as a methodological innovation.


METHOD. We used the Holistic Evaluation of Language Models (HELM) framework to evaluate the SCS1 and BDSI against 10 LLMS with zero-shot and few-shot in-context learning: GPT (3.5, 4.0), Claude (1.3, 2.0, 2.1), Llama (7B, 13B, 70B), Mistral v0.1 7B, and Mixtral 8x7B. We used psychometric data from prior studies to measure knowledge levels for each LLM run. We then conducted an informal expert review to qualitatively explore how question design, CS content knowledge, and LLM design may explain differences between LLM and expected student performances.


FINDINGS. Our quantitative analysis found that most LLM response patterns reflected a below average introductory computing student with the SCS1 and did not fit the psychometric 2PL model for the BDSI. Our qualitative analysis identified that LLMs performed well on code infill questions, but poorly on nested conditionals, runtime analysis, and longer questions. We also identified several methodological challenges related to item security, translation, the structure when using HELM.


IMPLICATIONS. We consider the feasibility of using automated benchmarking as a methodology to support more reproducible, replicable, and rigorous investigations to understand the intersection of LLM capabilities, computing concepts, and assessment design. We also consider connections between psychometric approaches and LLM evaluations to inform the design of computing assessments that are more resilient to LLM advancements."

# Summary. An optional shortened abstract.
summary: "Used automated benchmarking infrastructure and expert review to understand differences in LLM and student performance on CS assessments with validity evidence."

tags: [computing education, large language models, benchmarking, psychometrics, concept inventories]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

links:
- name: Supplementary Material
  url: https://github.com/Murtz5253/csed-benchmark-supplemental/tree/main
# - name: Blog Post
#   url: https://medium.com/bits-and-behavior/a-decade-of-demographics-in-computing-education-research-7c78812ef0fb
# - name: ICER '22 Activity
#   url: https://padlet.com/olesona4/mzzjwpod4hwevbml
# - name: Demonstration Video
#  url: https://vimeo.com/699278789
url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
# url_video: https://vimeo.com/849679040

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Benchmarking 10 LLMs on a CS concept inventory identified that their responses reflected below average introductory computing students."
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
