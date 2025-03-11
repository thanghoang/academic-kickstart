---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "A Multi-Server Oblivious Dynamic Searchable Encryption Framework"
authors: [Thang Hoang, Attila A. Yavuz, F. Betül Durak, Jorge Guajardo]
date: 2019-01-06T21:42:55-07:00
doi: "10.3233/JCS-191300"
highlight: 0
# Schedule page publish date (NOT publication's date).
publishDate: 2019-01-06T21:42:55-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Computer Security"
publication_short: "JCS"

abstract: "Data privacy is one of the main concerns for data outsourcing on the cloud. Although standard encryption can provide confidentiality, it prevents the client from searching/retrieving meaningful information on the outsourced data thereby, degrading the benefits of using cloud services. To address this data utilization versus privacy dilemma, Dynamic Searchable Symmetric Encryption (DSSE) has been proposed. DSSE enables encrypted search and update functionality over the encrypted data via a secure index. However, the state-of-the-art DSSE constructions leak information from the access pattern, making them vulnerable against various attacks. While generic Oblivious Random Access Machine (ORAM) can hide the access pattern, it incurs a heavy communication overhead, which was shown costly to be directly used in the DSSE setting. In this article, by exploiting the multi-cloud infrastructure, we develop a comprehensive Oblivious Distributed DSSE (ODSE) framework that allows oblivious search and updates on the encrypted index with high security and improved efficiency over the use of generic ORAM. Our framework contains a series of ODSE schemes each featuring different levels of performance and security required by various types of real-life applications. ODSE offers desirable security guarantees such as information-theoretic security and robustness in the presence of a malicious adversary. We fully implemented ODSE framework and evaluated its performance in a real cloud environment (Amazon EC2). Our experiments showed that ODSE schemes are 3×-57× faster than using generic ORAMs on a DSSE encrypted index under real network settings."

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
url_code: https://github.com/thanghoang/odse
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
