---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Efficient Dynamic Proof of Retrievability for Cold Storage"
authors: [Tung Le*, Pengzhi Huang, Attila A. Yavuz, Elaine Shi, Thang Hoang]
date: 2023-02-01T00:00:00-07:00
doi: "10.14722/ndss.2023.23307"
highlight: 1
#award: "Best Paper Award"





# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-22T00:00:00-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Annual Network and Distributed System Security Symposium"
publication_short: "NDSS"

abstract: "Storage-as-a-service (STaaS) permits the client to outsource her data to the cloud thereby, reducing data management and maintenance costs. However, STaaS also brings significant data integrity and soundness concerns since the storage provider might not keep the client data intact and retrievable all the time (e.g., cost saving via deletions). Proof of Retrievability (PoR) can validate the integrity and retrievability of remote data effectively. This technique can be useful for regular audits to monitor data compromises, as well as to comply with standard data regulations. In particular, cold storage applications (e.g., MS Azure, Amazon Glacier) require regular and frequent audits but with less frequent data modification. Yet, despite their merits, existing PoR techniques generally focus on other metrics (e.g., low storage, fast update, metadata privacy) but not audit efficiency (e.g., low audit time, small proof size). Hence, there is a need to develop new PoR techniques that achieve efficient data audit while preserving update and retrieval performance.\\

In this paper, we propose Porla, a new PoR framework that permits efficient data audit, update, and retrieval functionalities simultaneously. Porla permits data audit in both private and public settings, each of which features asymptotically (and concretely) smaller audit-proof size and lower audit time than all the prior works while retaining the same asymptotic data update overhead. Porla achieves all these properties by composing erasure codes with verifiable computation techniques which, to our knowledge, is a new approach to PoR design. We address several challenges that arise in such a composition by creating a new homomorphic authenticated commitment scheme, which can be of independent interest. We fully implemented Porla and evaluated its performance on commodity cloud (i.e., Amazon EC2) under various settings. Experimental results demonstrated that Porla achieves two to four orders of magnitude smaller audit proof size with 4× – 2,000× lower audit time than all prior schemes in both private and public audit settings at the cost of only 2× – 3× slower update."

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

url_pdf: https://eprint.iacr.org/2022/1417.pdf
url_code: https://github.com/vt-asaplab/porla
url_dataset:
url_poster:
url_project:
url_slides:  slides/23_ndss_porla.pptx
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
