---
title: 'Active Domain Transfer on Network Embedding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Lichen Jin
  - admin
  - Guojie Song
  - Yilun Jin



date: '2020-04-20'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-04-20'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of The Web Conference 2020*
publication_short: In *TheWebConf 2020*

abstract: Recent works show that end-to-end, (semi-) supervised network embedding models can generate satisfactory vectors to represent network topology, and are even applicable to unseen graphs by inductive learning. However, domain mismatch between training and testing network for inductive learning, as well as lack of labeled data often compromises the outcome of such methods. To make matters worse, while transfer learning and active learning techniques, being able to solve such problems correspondingly, have been well studied on regular i.i.d data, relatively few attention has been paid on networks. Consequently, we propose in this paper a method for active transfer learning on networks named active-transfer network embedding, abbreviated ATNE. In ATNE we jointly consider the influence of each node on the network from the perspectives of transfer and active learning, and hence design novel and effective influence scores combining both aspects in the training process to facilitate node selection. We demonstrate that ATNE is efficient and decoupled from the actual model used. Further extensive experiments show that ATNE outperforms state-of-the-art active node selection methods and shows versatility in different situations.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3366423.3380024'
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
