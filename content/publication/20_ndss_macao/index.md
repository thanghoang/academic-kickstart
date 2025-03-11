---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "MACAO: A Maliciously-Secure and Client-Efficient Active ORAM Framework"
authors: [Thang Hoang, Jorge Guajardo, Attila A. Yavuz]
date: 2020-02-06T21:41:54-07:00
doi: "10.14722/ndss.2020.24313"
highlight: 1

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-06T21:41:54-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Annual Network and Distributed System Security Symposium"
publication_short: "NDSS"

abstract: "Oblivious Random Access Machine (ORAM) allows a client to hide the access pattern and thus, offers a strong level of privacy for data outsourcing. An ideal ORAM scheme is expected to offer desirable properties such as low client bandwidth, low server computation overhead and the ability to compute over encrypted data. S3ORAM (CCS’17) is an efficient active ORAM scheme, which takes advantage of secret sharing to provide ideal properties for data outsourcing such as low client bandwidth, low server computation and low delay. Despite its merits, S3ORAM only offers security in the semi-honest setting. In practice, an
ORAM protocol is likely to operate in the presence of malicious adversaries who might deviate from the protocol to compromise the client privacy.

In this paper, we propose MACAO, a new multi-server ORAM framework, which offers integrity, access pattern obliviousness against active adversaries, and the ability to perform secure computation over the accessed data. MACAO harnesses authenticated secret sharing techniques and tree-ORAM paradigm to achieve low client communication, efficient server computation, and low storage overhead at the same time. We fully implemented MACAO and conducted extensive experiments in real cloud platforms (Amazon EC2) to validate the performance of MACAO compared with the state-of-the-art. Our results indicate that MACAO can achieve comparable performance to S3ORAM while offering security against malicious adversaries. MACAO is a suitable candidate for integration into distributed file systems with encrypted computation capabilities towards enabling an oblivious functional data outsourcing infrastructure."

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
url_code: https://github.com/thanghoang/macao
url_dataset:
url_poster:
url_project:
url_slides: slides/20_ndss_macao.pptx
url_source:
url_video: https://www.youtube.com/watch?v=hFQdpePZeZY

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
