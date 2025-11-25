---
title: 'Modeling Emails: On the Deniability of BCCs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Aysan Nishaburi
  - Guilherme Rito

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-09-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-09-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: Cryptology ePrint Archive
publication_short: []

abstract: Emails are one of the main forms of digital communication. They were designed to provide many guarantees that have surprisingly not yet been formalized in cryptography. Yet many of the guarantees emails were designed to provide have not been formalized in cryptography. This paper models an important feature of email applications":" the plausible deniability of including Bcc recipients. Concretely, (1) we define a basic (theoretical) email application capturing these guarantees in Constructive Cryptography (Maurer and Renner, ICS '11); (2) we introduce Email Encryption":" a new cryptographic primitive that is tailor-made to construct our email application; (3) we define game-based notions for Email Encryption schemes, proving that their combination is sufficient to construct our simple email application and; (4) we give a generic (proof-of-concept) construction of an Email Encryption scheme that provides all these guarantees.

Our work identifies and formalizes missing theoretical foundations for the security of emails providing the first step towards practical solutions.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprint.iacr.org/2025/1750'
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
