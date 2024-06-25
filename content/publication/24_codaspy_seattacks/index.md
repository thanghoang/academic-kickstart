---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Exploiting Update Leakage in Searchable Symmetric Encryption"
authors: [Jacob Haltiwanger*, Thang Hoang]
date: 2024-06-19T00:00:00-07:00
doi: "https://doi.org/10.1145/3626232.3653260"
highlight: 1
#award: "Best Paper Award"





# Schedule page publish date (NOT publication's date).
publishDate: 2024-04-01T00:00:00-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM Conference on Data and Application Security and Privacy"
publication_short: "CODASPY"

abstract: "Dynamic Searchable Symmetric Encryption (DSSE) provides efficient techniques for securely searching and updating an encrypted database. However, efficient DSSE schemes leak some sensitive information to the server. Recent works have implemented forward and backward privacy as security properties to reduce the amount of information leaked during update operations. Many attacks have shown that leakage from search operations can be abused to compromise the privacy of client queries. However, the attack literature has not rigorously investigated techniques to abuse update leakage.

In this work, we investigate update leakage under DSSE schemes with forward and backward privacy from the perspective of a passive adversary. We propose two attacks based on a maximum likelihood estimation approach, the UFID Attack and the UF Attack, which target forward-private DSSE schemes with no backward privacy and Level-2 backward privacy, respectively. These are the first attacks to show that it is possible to leverage the frequency and contents of updates to recover client queries. We propose a variant of each attack which allows the update leakage to be combined with search pattern leakage to achieve higher accuracy. We evaluate our attacks against a real-world dataset and show that using update leakage can improve the accuracy of attacks against DSSE schemes, especially those without backward privacy."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://dl.acm.org/doi/pdf/10.1145/3626232.3653260
url_code: https://github.com/vt-asaplab/DSSE-Attacks
url_dataset: 
url_poster:
url_project:
url_slides: slides/24_codaspy_upattack.pdf
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

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
