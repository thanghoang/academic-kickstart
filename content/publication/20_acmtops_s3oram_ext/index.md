---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Multi-server ORAM Framework with Constant Client Bandwidth Blowup"
authors: ['Thang Hoang', Attila A. Yavuz, Jorge Guajardo]
date: 2020-01-01T21:43:01-07:00
doi: "10.1145/3369108"
highlight: 1
# Schedule page publish date (NOT publication's date).
publishDate: 2020-01-01T21:43:01-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Privacy and Security"
publication_short: "TOPS"

abstract: "Oblivious Random Access Machine (ORAM) allows a client to hide the access pattern when accessing sensitive data on a remote server. It is known that there exists a logarithmic communication lower bound on any passive ORAM construction, where the server only acts as the storage service. This overhead, however, was shown costly for some applications. Several active ORAM schemes with server computation have been proposed to overcome this limitation. However, they mostly rely on costly homomorphic encryptions, whose performance is worse than passive ORAM. In this article, we propose S3ORAM, a new multi-server ORAM framework, which features O(1) client bandwidth blowup and low client storage without relying on costly cryptographic primitives. Our key idea is to harness Shamir Secret Sharing and a multi-party multiplication protocol on applicable binary tree-ORAM paradigms. This strategy allows the client to instruct the server(s) to perform secure and efficient computation on his/her behalf with a low intervention thereby, achieving a constant client bandwidth blowup and low server computational overhead. Our framework can also work atop a general k-ary tree ORAM structure (k ≥ 2). We fully implemented our framework, and strictly evaluated its performance on a commodity cloud platform (Amazon EC2). Our comprehensive experiments confirmed the efficiency of S3ORAM framework, where it is approximately 10× faster than the most efficient passive ORAM (i.e., Path-ORAM) for a moderate network bandwidth while being three orders of magnitude faster than active ORAM with O(1) bandwidth blowup (i.e., Onion-ORAM). We have open-sourced the implementation of our framework for public testing and adaptation."

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
url_code:  https://github.com/thanghoang/s3oram
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
