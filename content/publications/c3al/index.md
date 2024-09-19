---
title: 'Conflict-Aware Active Automata Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - tiago-ferreira
  - Léo Henry
  - admin
  - alexandra-silva

# Author notes (optional)

date: '2023-08-28T00:00:00Z'
doi: '10.4204/EPTCS.390.10'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Fourteenth International Symposium on Games, Automata, Logics, and Formal Verification*
publication_short: In *GandALF 2023*

abstract: Active automata learning algorithms cannot easily handle conflict in the observation data (different outputs observed for the same inputs). This inherent inability to recover after a conflict impairs their effective applicability in scenarios where noise is present or the system under learning is mutating. We propose the Conflict-Aware Active Automata Learning (C3AL) framework to enable handling conflicting information during the learning process. The core idea is to consider the so-called observation tree as a first-class citizen in the learning process. Though this idea is explored in recent work, we take it to its full effect by enabling its use with any existing learner and minimizing the number of tests performed on the system under learning, specially in the face of conflicts. We evaluate C3AL in a large set of benchmarks, covering over 30 different realistic targets, and over 18,000 different scenarios. The results of the evaluation show that C3AL is a suitable alternative framework for closed-box learning that can better handle noise and mutations.

# Summary. An optional shortened abstract.
# summary: 

tags:
  - Active Automata Learning
  - Formal Methods

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: DOI
#   url: https://doi.org/10.48550/arXiv.2310.01003

url_pdf: 'https://arxiv.org/pdf/2308.14781'
url_code: 'https://github.com/UCL-PPLV/learnlib'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

