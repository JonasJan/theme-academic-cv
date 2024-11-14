---
title: A Closer Look at Falcon

event: ''
event_url: ''

location: ''

abstract: 'Falcon is a winner of NIST’s six-year post-quantum cryptography standardisation competition. Based on the celebrated full-domain-hash framework of Gentry, Peikert and Vaikuntanathan (GPV) (STOC’08), Falcon leverages NTRU lattices to achieve the most compact signatures among lattice-based schemes. Its security hinges on a Renyi divergence-based argument for Gaussian samplers, a core element of the scheme. However, the GPV proof, which uses statistical distance to argue closeness of distributions, fails when applied naively to Falcon. Additional implementation-driven deviations from the GPV framework further invalidate the original proof, leaving Falcon without a security proof despite its selection for standardisation. In this talk, I want to give an overview of our results which demonstrate that introducing a few minor, conservative modifications allows for the first formal proof of the scheme in the random oracle model. At the heart of our analysis lies an adaptation of the GPV framework to work with the Renyi divergence, along with an optimised method for parameter selection under this measure. Furthermore, we obtain a provable version of the GPV framework over NTRU rings. Unfortunately, our analysis shows that despite our modification of Falcon-512 and Falcon-1024 we do not achieve strong unforgeability for either scheme. For plain unforgeability we are able to show that our modifications to Falcon-512 barely satisfy the claimed 120-bit security target and for Falcon-1024 we confirm the claimed security level.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-11-05T00:00:00Z'
#date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-11-05T00:00:00Z'

authors:
  - Microsoft Research

publication: Redmond, WA, USA

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
