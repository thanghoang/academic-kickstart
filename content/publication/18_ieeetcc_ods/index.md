---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Efficient Oblivious Data Structures for Database Services on the Cloud"
authors: [Thang Hoang, Ceyhun D. Ozkaptan, Gabriel Hackebeil, Attila A. Yavuz]
date: 2018-12-06T21:42:40-07:00
doi: "10.1109/TCC.2018.2879104"
highlight: 1

# Schedule page publish date (NOT publication's date).
publishDate: 2018-12-06T21:42:40-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Cloud Computing"
publication_short: "IEEE TCC"

abstract: "Database-as-a-service (DBaaS) allows the client to store and manage structured data on the cloud remotely. Despite its merits, DBaaS also brings significant privacy issues. Existing encryption techniques (e.g., SQL-aware encryption) can mitigate privacy concerns, but they still leak information through access patterns which are vulnerable to statistical inference attacks. Oblivious Random Access Machine (ORAM) can seal such leakages, but the recent studies showed significant challenges on the integration of ORAM into databases. Specifically, the direct usage of ORAM on databases is not only costly but also permits very limited query functionalities. We propose new oblivious data structures called Oblivious Matrix Structure (OMAT) and Oblivious Tree Structure (OTREE), which allow tree-based ORAM to be integrated into database systems in a more efficient manner with diverse query functionalities supported. OMAT provides special ORAM packaging strategies for table structures, which not only offers a significantly better performance but also enables a broad range of query types that may not be practical in existing frameworks. OTREE allows oblivious conditional queries to be deployed on tree-indexed databases more efficient than existing techniques. We fully implemented our proposed techniques and evaluated their performance on a real cloud database with various metrics, compared with state-of-the-art counterparts."

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
url_code: https://github.com/ceyhunozkaptan/OMAT-OTREE
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
