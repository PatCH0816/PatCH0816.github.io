---
title: 'Trade-that! A quantitative trading engine'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin, Florian Merz, Hannes Badertscher

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-08-08'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-08-08'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: Eastern Switzerland University of Applied Sciences
publication_short: OST

abstract: There are numerous individuals and institutions in this world, who earned more than is needed to cover their fixed costs and living expenses. Due to different motivations, these parties try to protect themself against inflation with a small associated risk or to increase their wealth with a higher associated risk. The objective of this project is to increase the size of its portfolio by using an algorithmic trading approach to trade the worlds first cryptocurrency called Bitcoin. Instead of trading Bitcoin by hand and driven by emotions, a quantitative trading engine is used to identify and capitalize available trading opportunities for the asset according to a multi-label classification model. The core idea is not to predict the prices in the future and execute the trades accordingly but to follow a more recent trend in the quantitative trading environment, where the state of the market is classified using a buy, hold or sell label. During the training phase, these labels are generated using future data. These labels serve as the target to train a classifier with an appropriate set of features. To find a set of distinct features to approximate the labels, an unique measure called the label separation power is used. This process is applied to generate multiple feature and label sets. Each feature and label set is used to train a separate classifier. The outputs of the classifiers are combined and form a trading strategy. Based on the scorer, which penalizes undesired characteristics, the trading strategies are optimized. The best performing strategies end up in an ensemble, which makes the resulting ensemble trading strategy more robust and can determine to buy, hodl or sell discrete amounts of the portfolio value in an optimized fashion according to the data it has been trained on. Backtesting the trading engine over two periods ranging over about one year according to the reference paper results in a positive total return. On one period the total return is around 1.5% per month and on the other period the total return is about 20% per month depending on the market trends. The average position size over both periods is about 50%, which enables the trading engine to quickly adapt to any changes in the market with maximized dynamics at any time. “Trade-that!” is able to demonstrate the feasibility of classifying the state of the market. Nevertheless, past profits do not guarantee future profits. Therefore it is essential to improve the trading engine and to adapt the properties of the trading engine continuously to the most recent market conditions.

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
url_poster: 'https://www.ost.ch/fileadmin/dateiliste/97_daten/abstracts/483a419f-55ac-42e0-882c-bd48219d3f5c.pdf'
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
