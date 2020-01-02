---
title: "Timings Matter: Standard Compliant IEEE 802.11 Channel Access for a Fully Software-based SDR Architecture"
authors:
- B. Bloessl
- admin
- C. Sommer
- Falko Dressler
date: "2015-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2015-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In ACM SIGMOBILE Mobile Computing and Communications Review (M2CR)

abstract: We present a solution for enabling standard compliant channel access for a fully softwarebased Software Defined Radio (SDR) architecture. With the availability of a GNU Radio implementation of an Orthogonal Frequency Division Multiplexing (OFDM) transceiver, there is substantial demand for standard compliant channel access. It has been shown that implementation of CSMA on a host PC is infeasible due to system-inherent delays. The common approach is to fully implement the protocol stack on the FPGA, which makes further updates or modifications to the protocols a complex and time consuming task. We take another approach and investigate the feasibility of a fully software-based solution and show that standard compliant broadcast transmissions are possible with marginal modifications of the FPGA. We envision the use of our system for example in the vehicular networking domain, where broadcast is the main communication paradigm. We show that our SDR solution exactly complies with the IEEE 802.11 Distributed Coordination Function (DCF) as well as Enhanced Distributed Channel Access (EDCA) timings. We were even able to identify shortcomings of commercial systems and prototypes. 
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
#- Source Themes
featured: False

links:
- name: ACM DL
  url: http://dl.acm.org/citation.cfm?id=2721913
url_pdf: http://www.puschmann.net/download/paper/Bloessl2015_timings.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
