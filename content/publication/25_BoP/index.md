---
title: 'Bird of Prey: Practical Signature Combiners Preserving Strong Unforgeability'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-10-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: Cryptology ePrint Archive
publication_short: []

abstract: Following the announcement of the first winners of the NIST post-quantum cryptography standardization process in 2022, cryptographic protocols are now undergoing migration to the newly standardized schemes. In most cases, this transition is realized through a hybrid approach, in which algorithms based on classical hardness assumptions, such as the discrete logarithm problem, are combined with post-quantum algorithms that rely on quantum-resistant assumptions, such as the Short Integer Solution (SIS) problem. A combiner for signature schemes can be obtained by simply concatenating the signatures of both schemes. This construction preserves unforgeability of the underlying schemes; however, it does not extend to stronger notions, such as strong unforgeability. Several applications, including authenticated key exchange and secure messaging, inherently require strong unforgeability, yet no existing combiner is known to achieve this property. This work introduces three practical combiners that preserve strong unforgeability and all BUFF (beyond unforgeability features) properties. Each combiner is tailored to a specific class of classical signature schemes capturing all broadly used schemes that are strongly unforgeable. Remarkably, all combiners can be instantiated with any post-quantum signature scheme in a black-box way making deployment practical and significantly less error prone. The proposed solutions are further highly efficient and have signatures that are at most the size of the (insecure) concatenation combiner. For instance, our most efficient combiner enables the combination of EdDSA with ML-DSA, yielding a signature size that is smaller than the sum of an individual EdDSA signature and an individual ML-DSA signature. Additionally, we identify a novel signature property that we call random-message validity and show that it can be used to replace the BUFF transform with the more efficient Pornin-Stern transform. The notion may be of independent interest.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprint.iacr.org/2025/1844.pdf'
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
