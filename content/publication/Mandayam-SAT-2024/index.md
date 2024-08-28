---
# Documentation: https://wowchemy.com/docs/managing-content/

title: SWIFT-SAT Software Defined Radio based Emulation of SAT-Terrestrial Network Coexistence in “FR3” Bands 
subtitle: ''
summary: ''
authors:
- N. Mandayam
- C. Michael Wu
- I. Seskar
tags:
- 'Spectrum Coexistence'
- 'Heterodyne Transceiver'
- 'Machine Learning'
categories: []
date: '2023-10-13'
lastmod: 2021-01-15T21:34:36Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-01-15T21:34:36.812355Z'
publication_types:
- '3'
abstract: The radio frequency band between 7.125 GHz and 24 GHz, known as Frequency Range 3 (FR3), is promising for next generation cellular systems. This project creates an over-the-air indoor FR3 testbed for experimental studies of coexistence between terrestrial and satellite systems, using software-defined radios (SDR) to emulate dense 5G cellular networks and satellite equipment. The FR3 testbed is an extension of an existing testbed, the COSMOS sandbox at Rutgers University WINLAB, and is an open resource remotely accessible to other researchers. This project uses the FR3 testbed to investigate technologies supporting terrestrial-satellite coexistence, including Machine Learning for radio resource management, interference identification and mitigation. Experimental studies enabled by the testbed are important as a complement to more widely performed modeling and analysis studies, to help make better decisions about how to share FR3 between new cellular systems, existing actively transmitting commercial satellites (e.g. digital broadcast) and existing passively observing scientific satellites (e.g. weather forecasting) without harmful interference to the satellites. Additionally, the project engages students at multiple levels, leveraging the broad outreach capabilities of WINLAB and Rutgers. The project focuses on spectrum sharing between terrestrial 5G and active commercial satellites in the 12.2-12.7 GHz band, and adjacent band coexistence between terrestrial 5G at 10-10.5 GHz and passive scientific satellites in the 10.6-10.7 GHz band. Software and hardware are designed that emulate 5G radio networks, commercial satellite transceivers, and passive radiometers in the targeted frequency bands. Metamaterial software-defined beamforming is used to emulate coexistence with satellites like non-geostationary orbit fixed satellite service (NGSO-FSS), and hot-cold calibration and comparison to datasets from on-orbit AMSR-E and AMSR2 sensors is used to enhance the reliability and realism of radiometer interference experiments. There are three thrusts - (1) design, validate and deploy FR3 SDR-based heterodyne devices, emulation of 5G New Radio (NR) and SAT waveforms, and coexistence emulation methods; (2) use emulation experiments to develop centralized Machine Learning algorithms for integrated radio resource management in sharing between terrestrial 5G and active commercial satellites; and (3) use emulation experiments to assess radiometer sensitivity to terrestrial 5G interference and to develop Machine Learning algorithms for interference identification and mitigation by passive scientific satellites. One outcome of the work in thrust 2 and thrust 3 is a measurement of the fraction of spectrum assigned to the terrestrial 5G cellular system that is "lost" due to the strategies used to mitigate interference to satellites.
url_pdf: /files/SAT.pdf
doi: https://www.nsf.gov/awardsearch/showAward?AWD_ID=2332637 

---
