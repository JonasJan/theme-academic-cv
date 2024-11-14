---
title: The Pre-Shared Key Modes of HPKE

event: ''
event_url: ''

location: ''

abstract: 'The Hybrid Public Key Encryption (HPKE) standard was recently published as RFC 9180 by the Crypto Forum Research Group (CFRG) of the Internet Research Task Force (IRTF). The RFC specifies an efficient public key encryption scheme, combining asymmetric and symmetric cryptographic building blocks. Out of HPKE’s four modes, two have already been formally analyzed by Alwen et al. (EUROCRYPT 2021). This work considers the remaining two modes&#58; HPKE_PSK and HPKE_AuthPSK . Both of them are “pre-shared key” modes that assume the sender and receiver hold a symmetric pre-shared key. We capture the schemes with two new primitives which we call pre-shared key public-key encryption (pskPKE) and pre-shared key authenticated public-key encryption (pskAPKE). We provide formal security models for pskPKE and pskAPKE and prove (via general composition theorems) that the two modes HPKE_PSK and HPKE_AuthPSK offer active security (in the sense of insider privacy and outsider authenticity) under the Gap Diffie-Hellman assumption. We furthermore explore possible post-quantum secure instantiations of the HPKE standard and propose new solutions based on lattices and isogenies. Moreover, we show how HPKE’s basic HPKEPSK and HPKEAuthPSK modes can be used black-box in a simple way to build actively secure post-quantum/classic-hybrid (authenticated) encryption schemes. Our hybrid constructions provide a cheap and easy path towards a practical post-quantum secure drop-in replacement for the basic HPKE modes HPKE_Base and HPKE_Auth.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-12-07T00:00:00Z'
#date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2023-12-07T00:00:00Z'

authors:
  - Asiacrypt

publication: Guangzhou, China

tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
