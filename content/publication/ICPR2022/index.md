---
title: 'Improving Weakly Supervised Scene Graph Parsing through Object Grounding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zhaoheng Zheng
  - Ram Nevatia
  - Yan Liu




date: '2022-12-02'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-12-02'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent

publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of 2022 26th International Conference on Pattern Recognition*


publication_short: In *ICPR 2022* (Submitted to ICLR 2021, which is earlier than ICCV 2021)

abstract: Weakly supervised scene graph parsing, which learns structured image representations without annotated correspondences between graph nodes and visual objects, has been prevalent in recent computer vision research. Existing methods mainly focus on designing task-specific loss functions, model architectures, or optimization algorithms. We argue that correspondences between objects and graph nodes are crucial for the weakly supervised scene graph parsing task and are worth learning explicitly. Thus we propose GroParser, a framework that improves weakly supervised scene graph parsing models by grounding visual objects. The proposed weakly supervised grounding method learns a metric among visual objects and scene graph nodes by incorporating information from both object features and relational features. Specifically, we apply multi-instance learning to learn the object category information and exploit a two-stream graph neural network to model the relational similarity metric. Extensive experiments on the scene graph parsing task verify the grounding found by our model can reinforce the performance of the existing weakly supervised scene graph parsing methods, including the current state-of-the-art. Further experiments on Visual Genome (VG) and Visual Relation Detection (VRD) datasets verify that our model brings an improvement on scene graph grounding task over existing approaches.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.computer.org/csdl/proceedings-article/icpr/2022/09956641/1IHoHmmLiEw'
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
