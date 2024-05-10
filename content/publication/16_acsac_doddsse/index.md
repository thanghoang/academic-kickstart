---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Practical and Secure Dynamic Searchable Encryption via Oblivious Access on Distributed Data Structure"
authors: [Thang Hoang, Attila A. Yavuz, Jorge Guajardo]
date: 2016-12-01T21:41:15-07:00
doi: "10.1145/2991079.2991088"
highlight: 1
# Schedule page publish date (NOT publication's date).
publishDate: 2016-12-01T21:41:15-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Annual Computer Security Applications Conference"
publication_short: "ACSAC"

abstract: "Dynamic Searchable Symmetric Encryption (DSSE) allows a client to perform keyword searches over encrypted files via an encrypted data structure. Despite its merits, DSSE leaks search and update patterns when the client accesses the encrypted data structure. These leakages may create severe privacy problems as already shown, for example, in recent statistical attacks on DSSE. While Oblivious Random Access Memory (ORAM) can hide such access patterns, it incurs significant communication overhead and, therefore, it is not yet fully practical for cloud computing systems. Hence, there is a critical need to develop private access schemes over the encrypted data structure that can seal the leakages of DSSE while achieving practical search/update operations.

In this paper, we propose a new oblivious access scheme over the encrypted data structure for searchable encryption purposes, that we call Distributed Oblivious Data structure DSSE (DOD-DSSE). The main idea is to create a distributed encrypted incidence matrix on two non-colluding servers such that no arbitrary queries on these servers can be linked to each other. This strategy prevents not only recent statistical attacks on the encrypted data structure but also other potential threats exploiting query linkability. Our security analysis proves that DOD-DSSE ensures the unlinkability of queries and, therefore, offers much higher security than traditional DSSE. At the same time, our performance evaluation demonstrates that DOD-DSSE is two orders of magnitude faster than ORAM-based techniques (e.g., Path ORAM), since it only incurs a small-constant number of communication overhead. That is, we deployed DOD-DSSE on geographically distributed Amazon EC2 servers, and showed that, a search/update operation on a very large dataset only takes around one second with DOD-DSSE, while it takes 3 to 13 minutes with Path ORAM-based methods."

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
url_code:
url_dataset:
url_poster:
url_project:
url_slides: slides/16_acsac_doddsse.pptx
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
