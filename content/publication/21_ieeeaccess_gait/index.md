---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multi-Model Long Short-Term Memory Network for Gait Recognition Using Window-Based Data Segment"
authors: [Lam Tran*, Thang Hoang, Thuc Nguyen, Hyunil Kim, Deokjai Choi]
date: 2021-01-25T21:28:55-07:00
doi: "10.1109/ACCESS.2021.3056880"
highlight: 0
#award: "Best Paper Award"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-02-03T21:28:55-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access"
publication_short: "Access"

abstract: "Inertial Measurement Units (IMUs)-based gait analysis is a promising and attractive approach for user recognition. Recently, the adoption of deep learning techniques has gained significant performance improvement. However, most existing studies focused on exploiting the spatial information of gait data (using Convolutional Neural Network (CNN)) while the temporal part received little attention. In this study, we propose a new multi-model Long Short-term Memory (LSTM) network for learning the gait temporal features. First, we observe that LSTM is able to capture the pattern hidden inside the gait data sequences that are out-of-synchronization. Thus, instead of using the gait cycle-based segment, our model accepts the gait cycle-free segment (i.e., fixed-length window) as the input. By this, the classification task does not depend on the gait cycle detection task, which usually suffers from noise and bias. Second, we propose a new LSTM network architecture, in which, one LSTM is used for each gait data channel and a group of consecutive signals is processed in each step. This strategy allows the network to effectively handle the long input data sequence and achieve improved performance compared to existing LSTM-based gait models. In addition, besides using the LSTM alone, we extend it by combining with a CNN model to construct a hybrid network, which further improves the recognition performance. We evaluated our LSTM and hybrid networks under different settings using the whuGAIT and OU-ISIR datasets. The experiments showed that our LSTM network outperformed the existing LSTM networks, and its combination with CNN established new state-of-the-art performance on both the verification and identification tasks."

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
