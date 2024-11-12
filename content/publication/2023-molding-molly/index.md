---
title: 'A feasibility study on the use of machine learning models applied to cavity pressure curves in injection molding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - [Prof. Dr. Katsaggelos](https://scholar.google.com/citations?user=aucB85kAAAAJ&hl=de&oi=ao)
  - Hannes Badertscher

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-02-18'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-02-18'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: Eastern Switzerland University of Applied Sciences
publication_short: OST

abstract: The "Institut für Werkstofftechnik und Kunststoffverarbeitung" (IWK) is a leading Swiss institute in the area of materials technology and polymers processing. One area of interest is to optimize the yield of injection molding machines. Injection molding machines are typically commissioned by an experienced operator and then run for weeks and months, where they produce millions of identical goods. To lower the amount of defective goods during this contiuous manufacturing process, it needs to be monitored at all times. Thus anomalies can be detected and corrected in a early stage. To achieve this objective, the current state-of-the-art method monitors several measurement variables during the process and stores them as persistent data in memory. Based on these measurements, manually defined features are extracted and passed into an anomaly detector. The difficulty of this approach on the one hand is the accessability of the data, as there is no unified interface across the industry. On the other hand, the data quality fluctuates across all manufacturers. The cavity pressure curve represents the pressure inside the tool during the injection molding process over time. The shape of this curve greatly affects the quality of the produced goods. The presented approach in this project focuses on utilizing this cavity pressure curve as the only feature to predict an anomaly. Several modern machine learning anomaly detection models are introduced, evaluated and compared to a simple baseline model and the state-of-the-art method. The development of such a model strongly depends on the quality of the data. Even a non-domain expert is able to spot obvious problems with the original dataset. The labels of the original dataset contain obvious anomalies, which are labeled as normal and vice versa. Since the quality of the labels provided is not ideal, a well defined anomaly definition according to the injection molding theory has been introduced. Due to the nature of the labeling procedure of the calculated labels one could argue, that the labels have been adapted to fit the model assumptions. This is partly true, but the underlaying assumption that the cavity pressure curve of normal cavity pressure curves are very similar in nature, is backed by the known theory about the injection molding process. Therefore, the original dataset could provide a possible advantage for the existing state-of-the-art models and the calculated labels could provide a possible advantage for the molding-molly-models. Therefore, the best of both label worlds has been combined to the fusion labels to balance the benefits and to prevent a covariate shift as much as possible. All available models are then evaluated on all three label definitions and demonstrate, that it is possible to detect any significant differences in the cavity pressure curves and therefore potential anomalies. The potential of the presented approach lies in the massively reduced data volume, accessibility of the measurement variable and performance comparability with the current state-of-the-art method

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'https://rpg.ifi.uzh.ch/docs/CoRL20_Yunlong.pdf'
# url_code: 'https://github.com/uzh-rpg/flightmare'
url_dataset: ''
url_poster: 'https://www.ost.ch/fileadmin/dateiliste/97_daten/abstracts/aed5709c-5027-49c9-9bc6-83c05a705878.pdf'
url_project: ''
url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtu.be/m9Mx1BCNGFU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - 

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
