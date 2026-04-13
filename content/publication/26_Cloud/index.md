---
title: 'Secure Cloud Storage: Modularization, Network Adversaries and Adaptive Corruptions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Doreen Riepel

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-03-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-03-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: EUROCRYPT 2026
publication_short: []

abstract: End-to-end cloud storage solutions are deployed at large scale, yet recent works have demonstrated severe attacks against their confidentiality and integrity. Motivated by this, a first formal treatment of secure cloud storage was given at CRYPTO 2024 by Backendal, Davis, Günther, Haller and Paterson (BDGHP). They define syntax and security notions, capturing client-to-client security of cloud storage schemes with respect to a password distribution. They also give an eﬃcient construction using the Two-Hash Diﬃe-Hellman (2HDH) OPRF and standard cryptographic building blocks, which they prove secure under selective corruptions in the random oracle model. However, several aspects of practical security guarantees remain open. We extend and refine the work of BDGHP along multiple dimensions, advancing the analysis of secure cloud storage schemes. First, we prove that their construction can be proven secure against adaptive corruptions (with a slight modification), circumventing technical challenges posed by file sharing. Second, we modularize the scheme further by introducing an abstraction for the authentication procedure. This allows us to identify the concrete role of 2HDH and alternative instantiations. Third, we introduce a weaker model that captures adversaries who can arbitrarily control the network, except during registration. This allows us to prove concrete guarantees about online password guessing attacks, whereas the stronger model inherently allows for oﬄine guessing. Finally, we formalize and prove explicit authentication, relying on the security of our new authentication abstraction and the MAC scheme, where the latter was previously not used in the security analysis.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprint.iacr.org/2026/434'
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
