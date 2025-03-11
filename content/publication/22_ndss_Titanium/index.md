---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Metadata-Hiding File-Sharing System with Malicious Security"
authors: [Weikeng Chen, Thang Hoang, Jorge Guajardo, Attila A. Yavuz]
date: 2022-02-27T21:28:55-07:00
doi: "10.14722/ndss.2022.24161"
highlight: 1
#award: "Best Paper Award"





# Schedule page publish date (NOT publication's date).
publishDate: 2021-12-30T00:00:00-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Annual Network and Distributed System Security Symposium"
publication_short: "NDSS"

abstract: "
End-to-end encrypted file-sharing systems, such as Keybase Filesystem, enable users to share files stored in the cloud without revealing the contents to the servers. However, the servers still learn metadata, such as user identities and access patterns. Prior works have tried to remove such leakage but relied on strong trust assumptions. Metal (NDSS’20) is not secure against malicious servers. MCORAM (ASIACRYPT’20) offers confiden- tiality against malicious servers, but not integrity.\\

We present Titanium, a metadata-hiding file-sharing system with confidentiality and integrity against both malicious users and servers. Compared with MCORAM, the state-of-the-art with con- fidentiality (but not integrity) against malicious servers, Titanium additionally offers integrity. Experiments show that Titanium is 5× to 200× faster, or even more, than MCORAM.
"

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
