---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "MAPLE: A Metadata-Hiding Policy-Controllable Encrypted Search Platform with Minimal Trust"
authors: [Tung Le*, Thang Hoang]
date: 2023-07-11T00:00:00-07:00
doi: "10.56553/popets-2023-0105"
highlight: 1
#award: "Best Paper Award"





# Schedule page publish date (NOT publication's date).
publishDate: 2023-05-03T00:00:00-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Privacy Enhancing Technologies Symposium"
publication_short: "PETS"

abstract: "Commodity encrypted storage platforms (e.g., IceDrive, pCloud) permit data store and sharing across multiple users while preserving data confidentiality. However, end-to-end encryption may not be sufficient since it only offers confidentiality when the data is at rest or in transit. Meanwhile, sensitive information can be leaked from metadata representing activities during data operations (e.g., query, processing). Recent encrypted search platforms such as DORY (OSDI’20) or DURASIFT (WPES’19) permit multi-user data query functionalities, while protecting metadata privacy. However, they either incur a high processing overhead or offer limited secu- rity/functionality, and require strong trust assumptions.\\

We propose MAPLE, a new metadata-hiding encrypted search platform that offers query functionalities (search, update) on the shared data across multiple users with complex policy controls. MAPLE protects metadata privacy all the time during query processing, while achieving significantly (asymptotically) lower processing overhead than state-of-the-art platforms. The core technique of MAPLE is the design of oblivious data structures for search index and access control coupled with secure computation techniques to enable efficient query processing with a minimal trust. We fully implemented MAPLE and evaluated its performance on commodity cloud (Amazon EC2) under real settings. Experimental results showed that MAPLE achieved a concrete performance comparable with its counterparts, while offering provably stronger security guarantees and more diverse functionalities."

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

url_pdf: https://eprint.iacr.org/2023/1105.pdf
url_code: https://github.com/vt-asaplab/maple
url_dataset: 
url_poster:
url_project:
url_slides: slides/23_pets_maple.pptx
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
