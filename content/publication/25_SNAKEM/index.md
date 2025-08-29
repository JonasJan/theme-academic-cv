---
title: 'Snake Mackerel: An Isogeny-Based AKEM Leveraging Randomness Reuse'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jonas Meers
  - Massimo Ostuzzi
  - Doreen Riepel

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-08-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-08-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: Cryptology ePrint Archive
publication_short: []

abstract: An Authenticated Key Encapsulation Mechanism (AKEM) combines public-key encryption and digital signatures to provide confidentiality and authenticity. AKEMs build the core of Hybrid Public Key Encryption (RFC 9180) and serve as a useful abstraction for messaging applications like the Messaging Layer Security (MLS) protocol (RFC 9420) and Signal’s X3DH protocol. To date, most existing AKEM constructions either rely on classical (non post-quantum) assumptions or on unoptimized black-box approaches leading to suboptimal efficiency. In this work, we choose a different abstraction level to combine KEMs and identification schemes more efficiently by leveraging randomness reuse. We construct a generic scheme and identify the necessary security requirements on the underlying KEM and identification scheme when reusing parts of their randomness. This allows for a concrete instantiation from isogenies based on the POKÉ KEM (EUROCRYPT’25) and the SQIsignHD identification scheme (EUROCRYPT’24). To be used in our black-box construction, the identification scheme requires the more advanced security property of response non-malleability. Hence, we further show that a slight modification of SQIsignHD satisfies this notion, which might be of independent interest. Putting everything together, our final scheme yields the most compact AKEM from PQ assumptions with public keys of 366 bytes and ciphertexts of 216 bytes while fulfilling the strongest confidentiality and authenticity notions.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprint.iacr.org/2025/1474.pdf'
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
