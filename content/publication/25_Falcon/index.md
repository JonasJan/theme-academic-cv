---
title: 'A Closer Look at Falcon'

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

date: '2024-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: []

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: In EPRINT
publication_short: []

abstract: Falcon is a winner of NIST’s six-year post-quantum cryptography standardisation competition. Based on the celebrated full-domain-hash framework of Gentry, Peikert and Vaikuntanathan (GPV) (STOC’08), Falcon leverages NTRU lattices to achieve the most compact signatures among lattice-based schemes.
Its security hinges on a R´enyi divergence-based argument for Gaussian samplers, a core element of the scheme. However, the GPV proof, which uses statistical distance to argue closeness of distributions, fails when applied naively to Falcon due to parameter choices resulting in statistical distances as large as 2−34. Additional implementation-driven deviations from the GPV framework further invalidate the
original proof, leaving Falcon without a security proof despite its selection for standardisation.
This work takes a closer look at Falcon and demonstrates that introducing a few minor, conservative modifications allows for the first formal proof of the scheme in the random oracle model. At the heart of our analysis lies an adaptation of the GPV framework to work with the R´enyi divergence, along with an optimised method for parameter selection under this measure. Furthermore, we obtain a provable version of the GPV framework over NTRU rings. Both these tools may be of independent interest.
Unfortunately, our analysis shows that despite our modification of Falcon-512 and Falcon-1024 we do not achieve strong unforgeability for either scheme. For plain unforgeability we are able to show that our modifications to Falcon-512 barely satisfy the claimed 120-bit security target and for Falcon-1024 we confirm the claimed security level. As such we recommend revisiting Falcon and its parameters.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprint.iacr.org/2024/1769.pdf'
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
