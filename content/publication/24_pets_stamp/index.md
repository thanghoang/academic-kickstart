---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Efficient Privacy-Preserving Machine Learning with Lightweight Trusted Hardware"
authors: [Pengzhi Huang, Thang Hoang,Yueying Li, Elaine Shi, G. Edward Suh]
date: 2024-07-15T00:00:00-07:00
doi: "https://doi.org/10.56553/popets-2024-0119"
highlight: 1
#award: "Best Paper Award"





# Schedule page publish date (NOT publication's date).
publishDate: 2024-05-01T00:00:00-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Privacy Enhancing Technologies Symposium"
publication_short: "PETS"

abstract: "In this paper, we propose a new secure machine learning inference platform assisted by a small dedicated security processor, which will be easier to protect and deploy compared to today's TEEs integrated into high-performance processors. Our platform provides three main advantages over the state-of-the-art:

(i) We achieve significant performance improvements compared to state-of-the-art distributed Privacy-Preserving Machine Learning (PPML) protocols, with only a small security processor that is comparable to a discrete security chip such as the Trusted Platform Module (TPM) or on-chip security subsystems in SoCs similar to the Apple enclave processor. In the semi-honest setting with WAN/GPU, our scheme is 4X-63X faster than Falcon (PoPETs'21) and AriaNN (PoPETs'22) and 3.8X-12X more communication efficient. We achieve even higher performance improvements in the malicious setting.

(ii) Our platform guarantees security with abort against malicious adversaries under honest majority assumption.

(iii) Our technique is not limited by the size of secure memory in a TEE and can support high-capacity modern neural networks like ResNet18 and Transformer.

While previous work investigated the use of high-performance TEEs in PPML, this work represents the first to show that even tiny secure hardware with really limited performance can be leveraged to significantly speed-up distributed PPML protocols if the protocol can be carefully designed for lightweight trusted hardware."

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

url_pdf: https://petsymposium.org/popets/2024/popets-2024-0119.php
url_code: https://github.com/HuangPZ/STAMP/tree/b7f9eab2b5d98da9883315075dd2a8066618a876
url_dataset: 
url_poster:
url_project:
url_slides: slides/24_pets_stamp.pptx
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
