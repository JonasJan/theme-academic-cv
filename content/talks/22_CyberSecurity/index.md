---
title: Private Set Intersection based on Fully Homomorphic Encryption

event: ''
event_url: ''

location: ''

abstract: "In this paper, we propose a new protocol for private computation on set intersection (PCI) which is an extension of private set intersection (PSI). In PSI, each party has a private set and both want to securely compute the intersection of their sets such that only the result is revealed and nothing else. In PCI, we want to additionally apply a private computation on the result. The goal is to reveal only the result of such a secure evaluation on the intersection and nothing else. We particularly focus on a client-server setting where the server's set is significantly larger than the client's set and the result of the computation should be revealed only to the client. The protocol aims at a low communication overhead which is sublinear in the server's set size. Such PSI protocols have already been realized using fully homomorphic encryption (FHE). However, they do not allow for private post-processing to enable PCI. There are also protocols enabling PCI which are in addition very fast with respect to the computational overhead. Their drawback is that they have a communication overhead which is at least linear in the larger set. We present a PSI protocol which can be used for arbitrary post-processing without creating a new protocol for every special-purpose PCI functionality. Our construction relies on the evaluation of a branching program using an FHE scheme. Using the properties of an FHE scheme, we build a non-interactive protocol with extendable functionalities. That means, we can not only securely compute the intersection but use the encrypted result to apply further computations without revealing the intersection itself. To the best of our knowledge, this results in the first PCI protocol with communication cost sublinear in the larger set. Compared to previous work, we can reduce the communication by factor 47."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-11-01T00:00:00Z'
#date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2022-11-01T00:00:00Z'

authors:
  - Cybersecurity Conference

publication: Mannheim, Germany

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
