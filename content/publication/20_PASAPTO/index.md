---
title: "PASAPTO: Policy-aware Security and Performance Trade-off Analysis--Computation on Encrypted Data with Restricted Leakage"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Andreas Fischer
  - admin
  - Jörn Kussmaul
  - Nicolas Krätzschmar
  - Florian Kerschbaum
  - Eric Bodden

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-05-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: CSF 2020
publication_short: []

abstract: This work considers the trade-off between security and performance when revealing partial information about encrypted data computed on. The focus of our work is on information revealed through control flow side-channels when executing programs on encrypted data. We use quantitative information flow to measure security, running time to measure performance and program transformation techniques to alter the trade-off between the two. Combined with information flow policies, we perform a policy-aware security and performance trade-off (PASAPTO) analysis. We formalize the problem of PASAPTO analysis as an optimization problem, prove the NP-hardness of the corresponding decision problem and present two algorithms solving it heuristically. We implemented our algorithms and combined them with the Dataflow Authentication (DFAuth) approach for outsourcing sensitive computations. Our DFAuth Trade-off Analyzer (DFATA) takes Java Bytecode operating on plaintext data and an associated information flow policy as input. It outputs semantically equivalent program variants operating on encrypted data which are policy-compliant and approximately Pareto-optimal with respect to leakage and performance. We evaluated DFATA in a commercial cloud environment using Java programs, e.g., a decision tree program performing machine learning on medical data. The decision tree variant with the worst performance is 357% slower than the fastest variant. Leakage varies between 0% and 17% of the input.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: EPRINT
#   url: https://eprint.iacr.org/2023/1480

url_pdf: 'pasapto.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
doi: '10.1109/CSF49147.2020.00024'

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
