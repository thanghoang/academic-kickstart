---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Polynomial Commitment with a One-to-Many Prover and Applications"
authors: [Jiaheng Zhang, Tiancheng Xie, Thang Hoang, Elaine Shi, Yupeng Zhang]
date: 2022-08-10T21:28:55-07:00
#doi: " "
highlight: 1
#award: "Best Paper Award"





# Schedule page publish date (NOT publication's date).
publishDate: 2021-09-04T21:28:55-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "USENIX Security Symposium"
publication_short: "USENIX"

abstract: "Verifiable Secret Sharing (VSS) is a foundational cryptographic primitive that serves as an essential building block in multi-party computation and decentralized blockchain applications. One of the most practical ways to construct VSS is through a polynomial commitment, where the dealer commits to a random polynomial whose 0-th coefficient encodes the secret to be shared, and proves the evaluation of the committed polynomial at a different point to each of N verifiers, i.e., the polynomial commitment is used in a “one-to-many” fashion. The recent work of Tomescu et al. (IEEE S&P 2020) was the first to consider polynomial commitment with “one-to- many prover batching”, such that the prover can prove evaluations at N different points at the cost of O(1) proofs. However, their scheme is not optimal and requires a trusted setup.\\

In this paper, we asymptotically improve polynomial commitment with one-to-many prover batching. We propose two novel schemes. First, we propose a scheme with optimal asymptotics in all dimensions in the trusted setup setting. Second, we are the first to consider one-to-many prover batching for transparent polynomial commitments, and we propose a transparent scheme whose performance approximately matches the best-known scheme in the trusted setup setting. We implement our schemes and evaluate their performance. Our scheme in the trusted setup setting improves the proof size by 20× and the verifier time by 7.8× for 221 parties, with a small overhead on the prover time. Our transparent polynomial commitment removes the trusted setup and further improves the prover time by 2.3×."

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
url_code: https://github.com/sunblaze-ucb/Virgo/tree/evss
url_dataset:
url_poster:
url_project:
url_slides: slides/22_usenix_pc.pptx
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
