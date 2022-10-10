---
title: 'PolSIRD: Modeling Epidemic spread under intervention policies'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nitin Kamra
  - admin
  - Sirisha Rambhatla
  - Chuizheng Meng
  - Yan Liu



date: '2021-06-14'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-06-14'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent

publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Journal of Healthcare Informatics Research*
publication_short: In *JHIR*

abstract: Epidemic spread in a population is traditionally modeled via compartmentalized models which represent the free evolution of disease in the absence of any intervention policies. In addition, these models assume full observability of disease cases and do not account for under-reporting. We present a mathematical model, namely PolSIRD, which accounts for the under-reporting by introducing an observation mechanism. It also captures the effects of intervention policies on the disease spread parameters by leveraging intervention policy data along with the reported disease cases. Furthermore, we allow our recurrent model to learn the initial hidden state of all compartments end-to-end along with other parameters via gradient-based training. We apply our model to the spread of the recent global outbreak of COVID-19 in the USA, where our model outperforms the methods employed by the CDC in predicting the spread. We also provide counterfactual simulations from our model to analyze the effect of lifting the intervention policies prematurely and our model correctly predicts the second wave of the epidemic.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/article/10.1007/s41666-021-00099-3'
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
