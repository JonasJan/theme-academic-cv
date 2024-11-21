---
title: "Computation on encrypted data using dataflow authentication"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Andreas Fischer
  - Benny Fuhry
  - Jörn Kußmaul
  - admin
  - Florian Kerschbaum
  - Eric Bodden

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-06-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: ACM Transactions on Privacy and Security 2022
publication_short: []

abstract: Encrypting data before sending it to the cloud ensures data confidentiality but requires the cloud to compute on encrypted data. Trusted execution environments, such as Intel SGX enclaves, promise to provide a secure environment in which data can be decrypted and then processed. However, vulnerabilities in the executed program give attackers ample opportunities to execute arbitrary code inside the enclave. This code can modify the dataflow of the program and leak secrets via SGX side channels. Fully homomorphic encryption would be an alternative to compute on encrypted data without data leaks. However, due to its high computational complexity, its applicability to general-purpose computing remains limited. Researchers have made several proposals for transforming programs to perform encrypted computations on less powerful encryption schemes. Yet current approaches do not support programs making control-flow decisions based on encrypted data. We introduce the concept of dataflow authentication (DFAuth) to enable such programs. DFAuth prevents an adversary from arbitrarily deviating from the dataflow of a program. Our technique hence offers protections against the side-channel attacks described previously. We implemented two flavors of DFAuth, a Java bytecode-to-bytecode compiler, and an SGX enclave running a small and program-independent trusted code base. We applied DFAuth to a neural network performing machine learning on sensitive medical data and a smart charging scheduler for electric vehicles. Our transformation yields a neural network with encrypted weights, which can be evaluated on encrypted inputs in 12.55 ms. Our protected scheduler is capable of updating the encrypted charging plan in approximately 1.06 seconds.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: EPRINT
#   url: https://eprint.iacr.org/2023/1480

url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3513005'
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
