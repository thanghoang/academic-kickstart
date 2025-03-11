---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Hardware-Supported ORAM in Effect: Practical Oblivious Search and Update on Very Large Dataset"
authors: [Thang Hoang, Muslum O. Ozmen, Yeongjin Jang, Attila A. Yavuz]
date: 2019-07-06T21:41:45-07:00
doi: "10.2478/popets-2019-0010"
highlight: 1
# Schedule page publish date (NOT publication's date).
publishDate: 2019-07-06T21:41:45-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Privacy Enhancing Technologies Symposium"
publication_short: "PETS"

abstract: "The ability to query and update over encrypted data is an essential feature to enable breach-resilient cyber-infrastructures. Statistical attacks on searchable encryption (SE) have demonstrated the importance of sealing information leaks in access patterns. In response to such attacks, the community has proposed the Oblivious Random Access Machine (ORAM). However, due to the logarithmic communication overhead of ORAM, the composition of ORAM and SE is known to be costly in the conventional client-server model, which poses a critical barrier toward its practical adaptations.

In this paper, we propose a novel hardware-supported privacy-enhancing platform called Practical Oblivious Search and Update Platform (POSUP), which enables oblivious keyword search and update operations on large datasets with high efficiency. We harness Intel SGX to realize efficient oblivious data structures for oblivious search/update purposes. We implemented POSUP and evaluated its performance on a Wikipedia dataset containing ≥229 keyword-file pairs. Our implementation is highly efficient, taking only 1 ms to access a 3 KB block with Circuit-ORAM. Our experiments have shown that POSUP offers up to 70× less end-to-end delay with 100× reduced network bandwidth consumption compared with the traditional ORAM-SE composition without secure hardware. POSUP is also at least 4.5× faster for up to 99.5% of keywords that can be searched compared with state-of-the-art Intel SGX-assisted search platforms."

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
url_code: https://github.com/thanghoang/posup
url_dataset:
url_poster:
url_project:
url_slides:   slides/19_pets_posup.pptx
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
