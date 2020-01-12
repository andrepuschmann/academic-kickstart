---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Self-Optimization of Software Defined Radios Through Evolutionary Algorithms"
authors:
- Z. M. Shaik
- admin
- A. Mitschele-Thiel
date: 2016-09-06T23:06:37+01:00
doi: ""
event: 28th International Teletraffic Congress (ITC)
location: Wuerzburg, Germany


# Schedule page publish date (NOT publication's date).
publishDate: 2016-09-06T23:06:37+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "This paper presents a framework for building software-defined radios that are able to self-optimize their parameters using evolutionary algorithms. The framework has been implemented using the DEAP library for Python, which is based on the Genetic Algorithms (GAs). The paper discusses the overall system architecture and presents a system prototype that has been employed to optimize radio transmission parameters in an unknown radio environment in order to maximize the achievable throughput. Although GAs have been used before for optimizing the radio parameters of Software Defined Radios (SDRs), they have been limited to the number of parameters given as an input to the GA. The proposed algorithm is much more generic and comprehensive to utilize the advantages of genetic algorithms, by providing the flexibility to include any of the parameters of the configuration of the SDR, which needs to be optimized through the GA. Moreover, the entire project is based on opensource solutions. The current prototype targets Iris-based SDRs. However, as the entire software employs standard components for interfacing the SDR, it can easily be ported to GNU Radio or other SDR frameworks. We will also present preliminary results that have been obtained through over-the-air experiments in which we optimized different power parameters, modulation, coding schemes, etc., in an unknown radio environment."  
# Summary. An optional shortened abstract.
summary: "[Best demo award]"

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

#links:
#- name: IEEExplore
#  url: http://ieeexplore.ieee.org/document/7920784
url_pdf: http://www.puschmann.net/download/paper/Shaik2016_self_opt_sdr.pdf
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
