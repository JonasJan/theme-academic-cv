---
title: "Ring Signatures for Deniable AKEM: Gandalf's Fellowship"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Phillip Gajland
  - admin
  - Eike Kiltz

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-08-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-16T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: CRYPTO 2024
publication_short: []

abstract: Ring signatures, a cryptographic primitive introduced by Rivest, Shamir and Tauman (ASIACRYPT 2001), offer signer anonymity within dynamically formed user groups. Recent advancements have focused on lattice-based constructions to improve efficiency, particularly for large signing rings. However, current state-of-the-art solutions suffer from significant overhead, especially for smaller rings. In this work, we present a novel NTRU-based ring signature scheme, Gandalf, tailored towards small rings. Our post-quantum scheme achieves a 50% reduction in signature sizes compared to the linear ring signature scheme Raptor (ACNS 2019). For rings of size two, our signatures are approximately a quarter the size of DualRing (CRYPTO 2021), another linear scheme, and remain more compact for rings up to size seven. Compared to the sublinear scheme Smile (CRYPTO 2021), our signatures are more compact for rings of up to 26. In particular, for rings of size two, our ring signatures are only 1236 bytes. Additionally, we explore the use of ring signatures to obtain deniability in authenticated key exchange mechanisms (AKEMs), the primitive behind the recent HPKE standard used in MLS and TLS. We take a fine-grained approach at formalising sender deniability within AKEM and seek to define the strongest possible notions. Our contributions extend to a black-box construction of a deniable AKEM from a KEM and a ring signature scheme for rings of size two. Our approach attains the highest level of confidentiality and authenticity, while simultaneously preserving the strongest forms of deniability in two orthogonal settings. Finally, we present parameter sets for our schemes, and show that our deniable AKEM, when instantiated with our ring signature scheme, yields ciphertexts of 2004 bytes.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: EPRINT
  icon: document
  url: https://eprint.iacr.org/2024/890

url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-031-68376-3_10'
doi: 'https://link.springer.com/chapter/10.1007/978-3-031-68376-3_10'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://iacr.org/submit/files/slides/2024/crypto/crypto2024/471/slides.pdf'
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
