---
title: Secure Branching Program Evaluation

event: ''
event_url: ''

location: ''

abstract: 'We address the problem of privately evaluating a branching program on encrypted data. This scenario is a 2-party protocol consisting of a server and a client. The server privately holds a branching program which is a representation of a boolean function using a directed acyclic graph. The client holds a secret input to the branching program. The goal of the computation is to evaluate the client's input on the server program such that only the result is revealed to the client, and nothing is revealed to the server. To solve this problem Ishai-Paskin introduced a public-key encryption scheme that is based on Damgård-Jurik additively homomorphic encryption and has the property, that given a branching program P and an encryption c of an input y, it is possible to efficiently compute a succinct ciphertext c' corresponding to P(y). The entire computation is done by the server relying on the fact that Damgård-Jurik scheme has length-flexible ciphertexts which allows multiplications between ciphertexts of different sizes under the same encryption key. Although the decryption of the Damgård-Jurik scheme is theoretically efficient, the size of  and the decoding time depend on the depth of the branching program. In this paper, we propose a new scheme where the input is instead encrypted using fully homomorphic encryption and discuss different variants and optimizations. The entire computation is also done by the server but the size of the resulting ciphertext is independent of the depth of the program. We implement Ishai-Paskin and our scheme and show that the running time of our scheme is an order of magnitude smaller.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2021-09-01T00:00:00Z'
#date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2021-09-01T00:00:00Z'

authors:
  - Crypto Day

publication: Virtual

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
