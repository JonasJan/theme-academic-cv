---
title: "A method for securely comparing integers using binary trees"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Anselme Tueno
  - admin
  - David Boehm

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: PoPETS 2023
publication_short: []

abstract: In this paper, we propose a new protocol for secure integer comparison which consists of parties having each a private integer. The goal of the computation is to compare both integers securely and reveal to the parties a single bit that tells which integer is larger. Nothing more should be revealed. To achieve a low communication overhead, this can be done by using homomorphic encryption (HE). Our protocol relies on binary decision trees that is a special case of branching programs and can be implemented using HE. We assume a client-server setting where each party holds one of the integers, the client also holds the private key of a homomorphic encryption scheme and the evaluation is done by the server. In this setting, our protocol outperforms the original DGK protocol of Damgård et al. and reduces the running time by at least 45%. In the case where both inputs are encrypted, our scheme reduces the running time of a variant of DGK by 63%.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: EPRINT
#   url: https://eprint.iacr.org/2023/1480

url_pdf: 'https://petsymposium.org/popets/2023/popets-2023-0092.pdf'
url_code: ''
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
