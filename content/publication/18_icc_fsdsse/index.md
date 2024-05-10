---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Forward-Private Dynamic Searchable Symmetric Encryption with Efficient Search"
authors: [Muslum O. Ozmen, Thang Hoang, Attila A. Yavuz]
date: 2018-05-06T21:41:37-07:00
doi: "https://doi.org/10.1109/ICC.2018.8422480"
highlight: 0
# Schedule page publish date (NOT publication's date).
publishDate: 2018-05-06T21:41:37-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Communications"
publication_short: "ICC"

abstract: "Dynamic Searchable Symmetric Encryption (DSSE) allows to delegate keyword search and file update over an encrypted database via encrypted indexes, and therefore provides opportunities to mitigate the data privacy and utilization dilemma in cloud storage platforms. Despite its merits, recent works have shown that efficient DSSE schemes are vulnerable to statistical attacks due to the lack of forward-privacy, whereas forward-private DSSE schemes suffers from practicality concerns as a result of their extreme computation overhead. Due to significant practical impacts of statistical attacks, there is a critical need for new DSSE schemes that can achieve the forward-privacy in a more practical and efficient manner. We propose a new DSSE scheme that we refer to as Forward-private Sublinear DSSE (FS-DSSE). FS-DSSE harnesses special secure update strategies and a novel caching strategy to reduce the computation cost of repeated queries. Therefore, it achieves forward-privacy, sublinear search complexity, low end-to-end delay, and parallelization capability simultaneously. We fully implemented our proposed method and evaluated its performance on a real cloud platform. Our experimental evaluation results showed that the proposed scheme is highly secure and highly efficient compared with state-of-the-art DSSE techniques. Specifically, FS-DSSE is up to three magnitude of times faster than forward-secure DSSE counterparts, depending on the frequency of the searched keyword in the database."

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

url_pdf:
url_code: https://github.com/ozgurozmen/FS-DSSE
url_dataset:
url_poster:
url_project:
url_slides:
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
