---
title: 'Identifying Coordinated Accounts on Social Media through Hidden Influence and Group Behaviours'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Karishma Sharma*
  - **Yizhou Zhang**
  - Emilio Ferrara
  - Yan Liu

date: '2021-05-18'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-08-14'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery and Data Mining*
publication_short: In *KDD 2021*

abstract: Disinformation campaigns on social media, involving coordinated activities from malicious accounts towards manipulating public opinion, have become increasingly prevalent. Existing approaches to detect coordinated accounts either make very strict assumptions about coordinated behaviours, or require part of the malicious accounts in the coordinated group to be revealed in order to detect the rest. To address these drawbacks, we propose a generative model, AMDN-HAGE (Attentive Mixture Density Network with Hidden Account Group Estimation) which jointly models account activities and hidden group behaviours based on Temporal Point Processes (TPP) and Gaussian Mixture Model (GMM), to capture inherent characteristics of coordination which is, accounts that coordinate must strongly influence each other's activities, and collectively appear anomalous from normal accounts. To address the challenges of optimizing the proposed model, we provide a bilevel optimization algorithm with theoretical guarantee on convergence. We verified the effectiveness of the proposed method and training algorithm on real-world social network data collected from Twitter related to coordinated campaigns from Russia's Internet Research Agency targeting the 2016 U.S. Presidential Elections, and to identify coordinated campaigns related to the COVID-19 pandemic. Leveraging the learned model, we find that the average influence between coordinated account pairs is the highest. On COVID-19, we found coordinated group spreading anti-vaccination, anti-masks conspiracies that suggest the pandemic is a hoax and political scam.





tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3447548.3467391'
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
