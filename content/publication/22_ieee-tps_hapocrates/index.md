---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Harpocrates: Privacy-Preserving and Immutable Audit Log for Sensitive Data Operations"
authors: [Mohit Bhasi Thazhath*, Jan Michalak*, Thang Hoang]
date: 2022-12-14T00:00:00-07:00
doi: "10.1109/TPS-ISA56441.2022.00036"
highlight: 1
#award: "Best Paper Award"





# Schedule page publish date (NOT publication's date).
publishDate: 2022-10-26T00:00:00-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Trust, Privacy and Security in Intelligent Systems, and Applications"
publication_short: "IEEE TPS"

abstract: "The audit log is a crucial component to monitor fine-grained operations over sensitive data (e.g., personal, health) for security inspection and assurance. Since such data operations can be highly sensitive, it is vital to ensure that the audit log achieves not only validity and immutability, but also confidentiality against active threats to standard data regulations (e.g., HIPAA) com- pliance. Despite its critical needs, state-of-the-art privacy- preserving audit log schemes (e.g., Ghostor (NSDI’20), Calypso (VLDB’19)) do not fully obtain a high level of privacy, integrity, and immutability simultaneously, in which certain information (e.g., user identities) is still leaked in the log.\\

In this paper, we propose Harpocrates, a new privacy-preserving and immutable audit log scheme. Harpocrates permits data store, share, and access oper- ations to be recorded in the audit log without leaking sen- sitive information (e.g., data identifier, user identity), while permitting the validity of data operations to be publicly verifiable. Harpocrates makes use of blockchain techniques to achieve immutability and avoid a single point of failure, while cryptographic zero-knowledge proofs are harnessed for confidentiality and public verifiability. We analyze the security of our proposed technique and prove that it achieves non-malleability and indistinguishability. We fully implemented Harpocrates and evaluated its performance on a real blockchain system (i.e., Hyperledger Fabric) deployed on a commodity platform (i.e., Amazon EC2). Experimental results demonstrated that Harpocrates is highly scalable and achieves practical performance.
"

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

url_pdf: https://arxiv.org/pdf/2211.04741.pdf
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
