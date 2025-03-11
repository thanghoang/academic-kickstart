---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "An Efficient and Zero-Knowledge Classical Machine Learning Inference Pipeline"
authors: [Haodi Wang*, Rongfang Bie, Thang Hoang]
date: 2024-08-18T00:00:00-07:00
doi: "10.1109/TDSC.2024.3435010"
highlight: "1"
#award: "Best Paper Award"





# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-18T00:00:00-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Dependable and Secure Computing"
publication_short: "TDSC"

abstract: "Machine Learning as a Service (MLaaS) offers powerful data analytics services to clients with limited resources. However, it still raises concerns about the integrity of delegated computation and the privacy of the server's model parameters. To address these issues, zero-knowledge Machine Learning (zkML) has been suggested for computation verifiability with privacy guarantee for ML models. Nevertheless, the existing zkML schemes focus on only one classical ML classification algorithm or deep neural networks, which may not achieve satisfactory accuracy or require large-scale training data and model parameters, thus limiting their usefulness in certain applications. In this paper, we propose ezDPS, an efficient and zero-knowledge scheme for classical ML inference that processes data in multiple stages for improved accuracy. Unlike prior works, each stage of the ezDPS pipeline is based on a well-established classical ML algorithm, including Discrete Wavelet Transformation, Zero-Score Normalization, Principal Components Analysis, and Support Vector Machine. We design new gadgets to prove various ML operations effectively. Our implementation of ezDPS has been fully tested on real datasets, and experimental results show that it is up to three orders of magnitude more efficient than generic circuit-based approaches, while also maintaining greater accuracy than single ML classification approaches."

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
