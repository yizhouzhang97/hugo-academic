---
title: 'Domain Adaptive Network Embedding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Guojie Song
  - admin
  - Lingjun Xu
  - Haibing Lu



date: '2020-10-27'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-10-27'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent

publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Big Data*
publication_short: In *TBD*

abstract: Recent works reveal that network embedding techniques enable many machine learning models to handle diverse downstream tasks on graph-structured data. However, as previous methods usually focus on learning embedding for a single network, they cannot learn representations transferable on multiple networks. Hence, it is important to design a network embedding algorithm that supports downstream model transferring on different networks, known as domain adaptation. In this article, we propose a Domain Adaptive Network Embedding framework, which applies Graph Convolutional Network to learn transferable embedding. In DANE, nodes from multiple networks are encoded to vectors via a shared and aligned embedding space. The distribution of embedding on different networks are further aligned by Adversarial Learning Regularization. To achieve better performance in scenarios where labels are provided, DANE adopts a cross-entropy error term of the GCN framework and class centroid aligning method. Moreover, DANE's advantages in learning transferable network embedding can be guaranteed theoretically. Extensive experiments reflect that the proposed framework outperforms other well-recognized network embedding baselines in cross-network domain adaptation tasks, and the semi-supervised components improve the performance significantly.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9241052'
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
#slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
