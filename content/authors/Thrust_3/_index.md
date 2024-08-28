---
# Display name
title: Thrust_3

#Use 1 for PI, 100 for Current Postdocs, 200 for current phds, 300 for current masters, 400 for current undergrads, 800 for alum postdocs, 810 for alum phds, 820 for alum masters, and 830 for alum undergrads, 900 for tools, 1000 for projects, 900 for tools, 1000 for projects
weight: 1000

# Username (this should match the folder name)
authors:
- Thrust_3

# Is this the primary user of the site?
superuser: false

# Organizations/Affiliations
organizations:
- name: Spectrum Coexistence for Radiometry
  url: ""
#- name: Formal Verification of Cyber-Physical Systems
#  url: ""
#- name: Asynchronous Circuit Design and Verification
#  url: ""
#- name: Analog Circuit Design and Verification
#  url: ""

# Short bio (displayed in user profile at end of posts)
# bio: My research interests include distributed robotics, mobile computing and programmable matter.



department:
- Computer Science

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:

#- icon: github
#  icon_pack: fab
#  link: https://github.com/fluentverification
#- icon: file-alt
#  icon_pack: fas
#  link: https://fluentverification.github.io/



# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ""

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
- Projects
- Thrust_3
- FLUENT Project
---

The 10.6-10.7 GHz SDR development to emulate a passive radiometer will allow its deployment in COSMOS along with multiple 5G BS and UEs occupying adjacent bands, e.g. 10-10.5 GHz. The AMSR sensors in the 10.6-10.7 GHz band reside on Earth Observation Satellites that are at distances ranging from 666-812 kms from the earth’s surface. The RFI observed at these sensors is a function of the density of 5G terrestrial transmitters, their transmit powers, bandwidths, locations, angles of transmission, and the propagation losses from the earth’s surface to the AMSR sensor. The propagation losses at these distances can be emulated on COSMOS using the noise injection mechanism that can arbitrarily dampen the signal strengths. The radio mapping algorithm mentioned earlier allows the creation of arbitrary 5G network topologies on the testbed that will be used to create aggregate levels of RFI based on transmit powers, bandwidths, locations and angles of transmission. Using this emulation framework, we will use both the centralized server and distributed control plane implementations to study the following.
