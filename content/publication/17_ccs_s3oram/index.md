---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "S3ORAM: A Computation-Efficient and Constant Client Bandwidth Blowup ORAM with Shamir Secret Sharing"
authors: [Thang Hoang, Ceyhun D. Ozkaptan, Attila A. Yavuz, Jorge Guajardo, Tam Nguyen]
date: 2017-10-06T21:41:20-07:00
doi: "10.1145/3133956.3134090"
highlight: 1
# Schedule page publish date (NOT publication's date).
publishDate: 2017-10-06T21:41:20-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM Conference on Computer and Communications Security"
publication_short: "CCS"

abstract: "Oblivious Random Access Machine (ORAM) enables a client to access her data without leaking her access patterns. Existing client-efficient ORAMs either achieve O(log N) client-server communication blowup without heavy computation, or O(1) blowup but with expensive homomorphic encryptions. It has been shown that O(log N) bandwidth blowup might not be practical for certain applications, while schemes with O(1) communication blowup incur even more delay due to costly homomorphic operations.

In this paper, we propose a new distributed ORAM scheme referred to as Shamir Secret Sharing ORAM (S3ORAM), which achieves O(1) client-server bandwidth blowup and O(1) blocks of client storage without relying on costly partial homomorphic encryptions. S3ORAM harnesses Shamir Secret Sharing, tree-based ORAM structure and a secure multi-party multiplication protocol to eliminate costly homomorphic operations and, therefore, achieves O(1) client-server bandwidth blowup with a high computational efficiency. We conducted comprehensive experiments to assess the performance of S3ORAM and its counterparts on actual cloud environments, and showed that S3ORAM achieves three orders of magnitude lower end-to-end delay compared to alternatives with O(1) client communication blowup (Onion-ORAM), while it is one order of magnitude faster than Path-ORAM for a network with a moderate bandwidth quality. We have released the implementation of S3ORAM for further improvement and adaptation."

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
url_code: https://github.com/thanghoang/s3oram
url_dataset:
url_poster:
url_project:
url_slides: slides/17_ccs_s3oram.pptx
url_source:
url_video: https://www.youtube.com/watch?v=v2KD2wF-SQI

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
