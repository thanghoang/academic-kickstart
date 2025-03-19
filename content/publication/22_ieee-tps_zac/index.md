---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ZAC: Efficient Zero-Knowledge Dynamic Universal Accumulator and Application to Zero-Knowledge Elementary Database"
authors: [Hai-Van Dang, Tran Phuong, Thuc Nguyen, Thang Hoang]
date: 2022-12-14T00:00:00-07:00
doi: "10.1109/TPS-ISA56441.2022.00038"
highlight: 0
#award: "Best Paper Award"





# Schedule page publish date (NOT publication's date).
publishDate: 2022-10-26T00:00:00-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Trust, Privacy and Security in Intelligent Systems, and Applications"
publication_short: "TPS"

abstract: "Zero-knowledge universal accumulator generates the succinct commitment to a set and produces the short (non) membership proof (universal) without leaking information about the set (zero-knowledge). In order to further support a generic set and zero-knowledge, existing techniques generally combine the zero-knowledge universal accumulator with other protocols, such as digital signatures and hashes to primes, which incur high overhead and may not be suitable for real-world use. It is desirable to commit a set of membership concealing the information with the optimal complexity. We devise ZAC, a new zero-knowledge Dynamic Universal Accumulator by taking the existing cryptographic primitives into account to produce a new efficient accumulator. Our underlying building blocks are Bloom Filter and vector commitment scheme in [19], utilizing the binary expression and aggregation to achieve efficiency, generic set support, zero-knowledge and universal properties. As a result, our scheme is improved in terms of proof size and proof time, also comparable to the RSA-based set accumulator in [8] in the verifying complexity. With 128 bit security, our proof size is 48 bytes while theirs is 1310 bytes and the running time of elliptic curve-based methods is faster than RSA-based counterpart. ZAC is proved to be complete, $ε$-sound and zero-knowledge. Extensively, based on ZAC as building block, we construct a new Zero-Knowledge Elementary Database (ZKEDB), which consumes 5 times less storage space, O(log N ) less bandwidth, and O(log N ) more efficient in proving and verification than the state-of-art work in [13] (where N is the domain space size). ZKEDB is proved to be complete, $ε$-sound and zero-knowledge. ZKEDB supports a new type of SELECT TOP $l$ query, and can be extended to non-elementary databases."

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
