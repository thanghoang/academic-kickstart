---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "MOSE: Practical Multi-User Oblivious Storage via Secure Enclaves"
authors: [Thang Hoang, Rouzbeh Behnia, Yeongjin Jang, Attila A. Yavuz]
date: 2020-03-06T21:41:50-07:00
doi: "10.1145/3374664.3375749"
highlight: 1
# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-06T21:41:50-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM Conference on Data and Application Security and Privacy"
publication_short: "CODASPY"

abstract: "Multi-user oblivious storage allows users to access their shared data on the cloud while retaining access pattern obliviousness and data confidentiality simultaneously. Most secure and efficient oblivious storage systems focus on the utilization of the maximum network bandwidth in serving concurrent accesses via a trusted proxy. However, since the proxy executes a standard ORAM protocol over the network, the performance is capped by the network bandwidth and latency. Moreover, some important features such as access control and security against active adversaries have not been thoroughly explored in such proxy settings. In this paper, we propose MOSE, a multi-user oblivious storage system that is efficient and enjoys from some desirable security properties. Our main idea is to harness a secure enclave, namely Intel SGX, residing on the untrusted storage server to execute proxy logic, thereby, minimizing the network bottleneck of proxy-based designs. In this regard, we address various technical design challenges such as memory constraints, side-channel attacks and scalability issues when enabling proxy logic in the secure enclave. We present a formal security model and analysis for secure enclave multi-user ORAM with access control. We optimize MOSE to boost its throughput in serving concurrent requests. We implemented MOSE and evaluated its performance on commodity hardware. Our evaluation confirmed the efficiency of MOSE, where it achieves approximately two orders of magnitudes higher throughput than the state-of-the-art proxy-based design, and also, its performance is scalable proportional to the available system resources."

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
url_slides: slides/20_codaspy_mose.pptx
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
