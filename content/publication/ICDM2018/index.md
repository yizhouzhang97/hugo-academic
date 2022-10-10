---
title: 'Chinese Medical Concept Normalization by Using Text and Comorbidity Network Embedding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xiaojun Ma
  - Guojie Song


date: '2018-11-17'

# Schedule page publish date (NOT publication's date).
publishDate: '2018-12-30'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of 2018 IEEE International Conference on Data Mining (ICDM)*
publication_short: In *ICDM 2018*

abstract: Chinese medical concept normalization, which maps non-standard medical concepts to standard expressions, is a NLP task with wide-ranging applications in medical big data research and clinical statistic. Many previous works apply supervised methods which require a lot of annotated data. However, they can not address the challenge brought by the high cost of medical data annotation, which requires sufficient professional knowledge and experience. Meanwhile, existing unsupervised methods perform poorly facing the various non-standard expression from different data sources. In this paper, we propose DUNE, Disease Unsupervised Normalization by Embedding, an unsupervised Chinese medical concept normalization framework by applying denoising auto-encoder (DAE) and network embedding. We formulate this task as finding mention-entity pairs with great text and comorbidity similarity. To handle the noise in text, we design a multi-view attention based denoising auto-encoder (MADAE) to capture text information from multiple views, reduce the influence of noise, and transform text to denoised vectors. To introduce comorbidity information, we construct a comorbidity network with both standard and non-standard disease names as nodes from medical records. Because of the diversity of nonstandard expressions, one disease perhaps corresponds to several different nodes, which causes noise in comorbidity network. To handle such network structure noise, we propose a denoising network embedding framework, which reduce the structure noise with the help of text information, to embed the nodes to vectors for comorbidity similarity measurement. Convincing experiment results show that our method performs better than existing unsupervised baselines and approaches the performance of classical supervised machine learning model on this task.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8594902'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
