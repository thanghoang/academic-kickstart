---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Breaking Privacy in Model-Heterogeneous Federated Learning"
authors: [Atharva Haldankar*, Arman Riasi*, Hoang-Dung Nguyen*, Tran Phuong, Thang Hoang]
date: 2024-09-30T00:00:00-07:00
doi: "https://doi.org/10.1145/3678890.3678905"
highlight: "1"
#award: "Best Paper Award"





# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-25T00:00:00-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Symposium on Research in Attacks, Intrusions and Defenses"
publication_short: "RAID"

abstract: "Federated learning (FL) allows multiple distrustful clients to collaboratively train a machine learning model. In FL, data never leaves client devices; instead, clients only share locally computed gradients with a central server. As individual gradients may leak information about a given client’s dataset, secure aggregation was proposed. With secure aggregation, the server only receives the aggregate gradient update from the set of all sampled clients without being able to access any individual gradient. One challenge in FL is the systems-level heterogeneity that is quite often present among client devices. Specifically, clients in the FL protocol may have varying levels of compute power, on-device memory, and communication bandwidth. These limitations are addressed by model-heterogeneous FL schemes, where clients are able to train on subsets of the global model. Despite the benefits of model-heterogeneous schemes in addressing systems-level challenges, the implications of these schemes on client privacy have not been thoroughly investigated.\\

In this paper, we investigate whether the nature of model distribution and the computational heterogeneity among client devices in model-heterogeneous FL schemes may result in the server being able to recover sensitive data from target clients. To this end, we propose two attacks in the model-heterogeneous FL setting, even with secure aggregation in place. We call these attacks the Convergence Rate Attack and the Rolling Model Attack. The Convergence Rate Attack targets schemes where clients train on the same subset of the global model, while the Rolling Model Attack targets schemes where model parameters are dynamically updated each round. We show that a malicious adversary can compromise the model and data confidentiality of a target group of clients. We evaluate our attacks on the MNIST and CIFAR-10 datasets and show that using our techniques, an adversary can reconstruct data samples with near perfect accuracy for batch sizes of up to 20 samples."

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
url_code: https://github.com/vt-asaplab/model-hetero-fl-attacks
url_dataset: 
url_poster:
url_project:
url_slides: slides/24_raid_heteroFL
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
