---
title: 'DANE: Domain Adaptive Network Embedding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Guojie Song
  - Lun Du
  - Shuwen Yang
  - Yilun Jin

# Author notes (optional)


date: '2019'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the Twenty-Eighth International Joint Conference on Artificial Intelligence*
publication_short: In *IJCAI 2019*

abstract: Recent works reveal that network embedding techniques enable many machine learning models to handle diverse downstream tasks on graph structured data. However, as previous methods usually focus on learning embeddings for a single network, they can not learn representations transferable on multiple networks. Hence, it is important to design a network embedding algorithm that supports downstream model transferring on different networks, known as domain adaptation. In this paper, we propose a novel Domain Adaptive Network Embedding framework, which applies graph convolutional network to learn transferable embeddings. In DANE, nodes from multiple networks are encoded to vectors via a shared set of learnable parameters so that the vectors share an aligned embedding space. The distribution of embeddings on different networks are further aligned by adversarial learning regularization. In addition, DANE's advantage in learning transferable network embedding can be guaranteed theoretically. Extensive experiments reflect that the proposed framework outperforms other state-of-the-art network embedding baselines in cross-network domain adaptation tasks.



tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/1906.00684'
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
projects:
  - example

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
