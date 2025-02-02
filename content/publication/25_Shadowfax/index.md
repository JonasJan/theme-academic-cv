---
title: 'Shadowfax: Combiners for Deniability'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Phillip Gajland
  - Vincent Hwang
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-02-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: EPRINT
publication_short: []

abstract: "As cryptographic protocols transition to post-quantum security, most adopt hybrid solutions combining pre-quantum and post-quantum assumptions. However, this shift often introduces trade-offs in terms of efficiency, compactness, and in some cases, even security. One such example is deniability, which enables users, such as journalists or activists, to deny authorship of potentially incriminating messages. While deniability was once mainly of theoretical interest, protocols like X3DH, used in Signal and WhatsApp, provide it to billions of users. Recent work (Collins et al., PETS'25) has further bridged the gap between theory and real-world applicability. In the post-quantum setting, however, protocols like PQXDH, as well as others such as Apple’s iMessage with PQ3, do not support deniability. This work investigates how to preserve deniability in the post-quantum setting by leveraging unconditional (statistical) guarantees instead of computational assumptions - distinguishing deniability from confidentiality and authenticity. As a case study, we present a hybrid authenticated key encapsulation mechanism (AKEM) that provides statistical deniability, while maintaining authenticity and confidentiality through a combination of pre-quantum and post-quantum assumptions. To this end, we introduce two combiners at different levels of abstraction. First, at the highest level, we propose a black-box construction that combines two AKEMs, showing that deniability is preserved only when both constituent schemes are deniable. Second, we present Shadowfax, a non-black-box combiner that integrates a pre-quantum NIKE, a post-quantum KEM, and a post-quantum ring signature. We demonstrate that Shadowfax ensures deniability in both dishonest and honest receiver settings. When instantiated, we rely on statistical security for the former, and on a pre- or post-quantum assumption in the latter. Finally, we provide an optimised, yet portable, implementation of a specific instantiation of Shadowfax yielding ciphertexts of 1781 bytes and public keys of 1449 bytes. Our implementation achieves competitive performance: encapsulation takes 1.9 million cycles and decapsulation takes 800000 cycles on an Apple M1 Pro."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprint.iacr.org/2025/154.pdf'
url_code: 'https://github.com/vincentvbh/shadowfax'
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
