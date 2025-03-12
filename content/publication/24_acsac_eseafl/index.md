---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Efficient Secure Aggregation for Privacy-Preserving Federated Machine Learning"
authors: [Rouzbeh Behnia, Arman Riasi*, Mohammadreza Ebrahimi, Sherman S. M. Chow, Balaji Padmanabhan, Thang Hoang]
date: 2024-12-09T00:00:00-07:00
doi: "10.1109/ACSAC63791.2024.00069"
highlight: "1"
#award: "Best Paper Award"





# Schedule page publish date (NOT publication's date).
publishDate: 2024-08-20T00:00:00-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The Annual Computer Security Applications Conference"
publication_short: "ACSAC"
abstract: "Secure aggregation protocols ensure the privacy of users' data in federated learning by preventing the disclosure of local gradients. Many existing protocols impose significant communication and computational burdens on participants and may not efficiently handle the large update vectors typical of machine learning models. Correspondingly, we present e-SeaFL, an efficient verifiable secure aggregation protocol taking only one communication round during the aggregation phase. e-SeaFL allows the aggregation server to generate proof of honest aggregation to participants via authenticated homomorphic vector commitments. Our core idea is the use of assisting nodes to help the aggregation server, under similar trust assumptions existing works place upon the participating users. Our experiments show that the user enjoys an order of magnitude efficiency improvement over the state-of-the-art (IEEE S&P 2023) for large gradient vectors with thousands of parameters."

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

url_pdf: https://arxiv.org/pdf/2304.03841
url_code: https://github.com/vt-asaplab/e-SeaFL
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
