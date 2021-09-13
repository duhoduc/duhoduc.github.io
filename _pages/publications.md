---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Journals
- D. Ho, G. Hendeby, M. Enqvist. "On separation of closed‑loop sensor and system faults for quadcopters". To be submitted IEEE Robotics ans Automation Letters (RA‑L), 2021.
[[Preprint]](/files/paper1.pdf) . 
- D. Ho, G. Hendeby, M. Enqvist. "On improvement of the Instrumental variable method in estimating nonlinear models".
## Conferences
- D. Ho, G. Hendeby, M. Enqvist. "A sensor‑to‑sensor model‑based change detection approach for quadcopters". In IFAC World
Congress 2020, July 11‑17 2020, Germany.  
- D. Ho, M. Enqvist. "On the equivalence of forward and inverse IV estimators with application to quadcopter modeling". In
Proceedings of the 18th IFAC Symposium on System Identification (SYSID), July 9‑11 2018, Stockholm, Sweden.
- D. Ho, J. Linder, G. Hendeby, M. Enqvist. "Vertical modeling of a quadcopter for mass estimation and diagnosis purposes". In
2017 Workshop on Research, Education and Development of Unmanned Aerial Systems (RED‑UAS), 3‑5 October 2017,
Linköping, Sweden.
- D. Ho, J. Linder, G. Hendeby, M. Enqvist. "Mass estimation of a quadcopter using IMU data". In 2017 International Conference
on Unmanned Aircraft Systems (ICUAS), June 13‑16 2017, Miami, FL, USA.
- A.T. Phan, D. Ho, G. Hermann, P. Wira. "A new state‑space model for three‑phase systems for Kalman filtering with
application to power quality estimation". AIP Conference Proceedings. Vol. 1702. No. 1. AIP Publishing LLC, 2015.
- D. Ho, R. Mura, L. Piroddi, M. Lovera, G.L. Ghiringhelli. "Robust harmonic control: an application to structural vibration
reduction in helicopters". In proceeding of the 1st IFAC Workshop on Advanced Control and Navigation for Autonomous
Aerospace Vehicles (ACNAAV 2015), Jun 10 2015, Seville, Spain    

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
