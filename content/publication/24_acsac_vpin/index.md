---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Privacy-Preserving Verifiable Neural Network Inference Service"
authors: [Arman Riasi*, Jorge Guajardo, Thang Hoang]
date: 2024-12-09T00:00:00-07:00
doi: "10.1109/ACSAC63791.2024.00063"
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

abstract: "Machine learning has revolutionized data analysis and pattern recognition, but its resource-intensive training has limited accessibility. Machine Learning as a Service (MLaaS) simplifies this by enabling users to delegate their data samples to an MLaaS provider and obtain the inference result using a pre-trained model. Despite its convenience, leveraging MLaaS poses significant privacy and reliability concerns to the client. Specifically, sensitive information from the client inquiry data can be leaked to an adversarial MLaaS provider. Meanwhile, the lack of a verifiability guarantee can potentially result in biased inference results or even unfair payment issues. While existing trustworthy machine learning techniques, such as those relying on verifiable computation or secure computation, offer solutions to privacy and reliability concerns, they fall short of simultaneously protecting the privacy of client data and providing provable inference verifiability.

In this paper, we propose vPIN, a privacy-preserving and verifiable CNN inference scheme that preserves privacy for client data samples while ensuring verifiability for the inference. vPIN makes use of partial homomorphic encryption and commit-and-prove succinct non-interactive argument of knowledge techniques to achieve desirable security properties. In vPIN, we develop various optimization techniques to minimize the proving circuit for homomorphic inference evaluation thereby, improving the efficiency and performance of our technique. We fully implemented and evaluated our vPIN scheme on standard datasets (e.g., MNIST, CIFAR-10). Our experimental results show that vPIN achieves high efficiency in terms of proving time, verification time, and proof size, while providing client data privacy guarantees and provable verifiability."

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

url_pdf: https://arxiv.org/pdf/2411.07468
url_code: https://github.com/vt-asaplab/vPIN
url_dataset: 
url_poster:
url_project:
url_slides: slides/24_acsac_vpin.key
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
