---
title: "Constrained distance based k-means clustering for satellite image time-series"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Lampert Thomas
- admin
- Gançarski Pierre

date: "2019-07-28T00:00:00Z"
doi: "https://doi.org/10.1109/IGARSS.2019.8900147"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-11-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In IGARSS 2019 - 2019 IEEE International Geoscience and Remote Sensing Symposium
publication_short: In IGARSS 2019

abstract: The advent of high-resolution instruments for time-series sampling poses added complexity for the formal definition of thematic classes in the remote sensing domain-required by supervised methods-while unsupervised methods ignore expert knowledge and intuition. Constrained clustering is becoming an increasingly popular approach in data mining because it offers a solution to these problems, however, its application in remote sensing is relatively unknown. This article addresses this divide by adapting publicly available k-Means constrained clustering implementations to use the dynamic time warping (DTW) dissimilarity measure, which is thought to be more appropriate for time-series analysis. Adding constraints to the clustering problem increases accuracy when compared to unconstrained clustering. The output of such algorithms are homogeneous in spatially defined regions.

tags: [Image time-series, constrained clustering, semi-supervised clustering, partition clustering]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://hal.archives-ouvertes.fr/hal-02356722/file/main.pdf'
url_code: 'https://icube-forge.unistra.fr/lampert/TSCC'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
