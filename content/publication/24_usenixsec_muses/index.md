---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "MUSES: Efficient Multi-User Searchable Encrypted Database"
authors: [Tung Le*, Rouzbeh Behnia, Jorge Guajardo, Thang Hoang]
date: 2024-08-12T00:00:00-07:00
doi: ""
highlight: "1"
#award: "Best Paper Award"





# Schedule page publish date (NOT publication's date).
publishDate: 2024-05-06T00:00:00-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "USENIX Security Symposium"
publication_short: "USEC"

abstract: "Searchable encrypted systems enable privacy-preserving key- word search on encrypted data. Symmetric systems achieve high efficiency (e.g., sublinear search), but they mostly sup- port single-user search. Although systems based on public- key or hybrid models support multi-user search, they incur inherent security weaknesses (e.g., keyword-guessing vulner- abilities) and scalability limitations due to costly public-key operations (e.g., pairing). More importantly, most encrypted search designs leak statistical information (e.g., search, re- sult, and volume patterns) and thus are vulnerable to devas- tating leakage-abuse attacks. Some pattern-hiding schemes were proposed. However, they incur significant user band- width/computation costs, and thus are not desirable for large- scale outsourced databases with resource-constrained users.\\

In this paper, we propose MUSES, a new multi-writer en- crypted search platform that addresses the functionality, se- curity, and performance limitations in the existing encrypted search designs. Specifically, MUSES permits single-reader, multi-writer functionalities with permission revocation and hides all statistical information (including search, result, and volume patterns) while featuring minimal user overhead. In MUSES, we demonstrate a unique incorporation of various emerging distributed cryptographic protocols including Dis- tributed Point Function, Distributed PRF, and Oblivious Lin- ear Group Action. We also introduce novel distributed proto- cols for oblivious counting and shuffling on arithmetic shares for the general multi-party setting with a dishonest majority, which can be found useful in other applications. Our experi- mental results showed that the keyword search by MUSES is two orders of magnitude faster with up to 97× lower user bandwidth cost than the state-of-the-art."

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

url_pdf: https://eprint.iacr.org/2023/720.pdf
url_code: https://github.com/vt-asaplab/MUSES
url_dataset: 
url_poster:
url_project:
url_slides: slides/24_usenix_muses.pptx
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
