---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

My name is George Ma (Jiangyan Ma). I am an incoming EECS PhD student at UC Berkeley, advised by Prof. [Somayeh Sojoudi](https://people.eecs.berkeley.edu/~sojoudi/). Previously, I was an undergraduate student at Peking University, where I did research on graph learning at Prof. [Yisen Wang](https://yisenwang.github.io/)'s lab. My email: [georgem@stu.pku.edu.cn](mailto:georgem@stu.pku.edu.cn). My homepage: [George Ma's Homepage](https://georgemlp.github.io). I actively write blogs on Zhihu: [George M's Zhihu Homepage](https://www.zhihu.com/people/george-m-55/posts).

Education
======
- *Undergraduate; Information and Computing Science*

  I studied at School of Electronic Engineering and Computer Science, Peking University. I majored in Applied Physics in the first two years of college and switched to Information and Computing Science thereafter.

- *PhD student; Electrical Engineering and Computer Science*

  I am an incoming EECS PhD student at UC Berkeley.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research Experience
======

- July 2022 -- October 2022; **Universal Graph Neural Networks without Message-Passing**

  In this research experience, I focused on studying the expressive power of MLP-based graph neural networks for graph-level tasks. I developed a novel MLP-based GNN called UBoN (Universal Bag of Nodes), specifically designed to achieve universal expressive power on graphs. I submitted my paper titled *Universal Graph Neural Networks without Message Passing* to ICLR 2023, although it was unfortunately rejected.

- October 2022 -- August 2023; **Laplacian Canonization for GNN Spectral Embedding**

  During my research, I explored the concept of Laplacian eigenvectors as universal graph positional encodings. Although being universal, there are challenges associated with their universality, such as sign and basis ambiguity. To tackle these issues, I proposed an innovative pre-processing technique called Laplacian Canonization. I submitted my paper titled *Laplacian Canonization: A Minimalist Approach to Sign and Basis Invariant Spectral Embedding* to NeurIPS 2023, and it was accepted as a poster.

- June 2023 -- Present; **Baking Symmetry into GFlowNets**

  Currently, I am actively contributing to groundbreaking research as a member of Prof. Yoshua Bengio’s lab at Mila - Quebec AI Institute in Montréal. Leveraging my expertise in invariant networks, I am dedicated to incorporating symmetries into the graph construction process of GFlowNets. Preliminary experiments have demonstrated promising performance enhancements. I submitted my paper titled *Baking Symmetry into GFlowNets* to the NeurIPS 2023 AI4Science Workshop, and it was accepted as an **oral** presentation.

- June 2023 -- Present; **A Canonization Perspective on Invariant and Equivariant Learning**

  I am currently collaborating with researchers from MIT to investigate the correlation between the canonizability of Laplacian eigenvectors and the expressive power of invariant networks (such as SignNet and BasisNet) that employ Laplacian eigenvectors as positional encodings. We establish the theoretical framework of canonization, and apply it to solve the open problem of the expressive power of invariant networks with equivariance constraints. We also designed novel canonization algorithms for eigenvectors that are superior to prior work and even optimal. We are currently preparing our findings for submission to NeurIPS.

<!-- Community Involvement
======

- October 2020 -- June 2021; **Companionship Activity Volunteer**

  Engaged in Companionship Activities organized by the Love Society of Peking University, facilitating letter exchanges with students in impoverished areas across China.

- October 2020 -- June 2021; **Advanced Mathematics Tutoring Volunteer**

  Assisted students in Advanced Mathematics by volunteering as a tutor through the Youth Volunteer Association at the School of Mathematics.

- October 2020 -- June 2021; **Computer Repairing Volunteer**

  Provided regular computer repair assistance to fellow students at Peking University, utilizing my computer skills. Activities were organized by the Youth Volunteer Association at the School of EECS.

- January 2019; **Volunteer to Serve the Elderly**

  Visited an elderly care home in my hometown, Changzhi, along with my high school classmates. We engaged in conversations with the residents and presented them with thoughtful gifts. -->

Awards
======

- Provincial First Prize of National Mathematics Olympiad in Senior
- Second Prize of the Chinese Mathematics Competitions
- Successful Participant of the Mathematical Contest in Modeling
- Top 10 Excellent Graduation Thesis of School of EECS, Peking University
- Excellent Graduation Thesis, Peking University

Scholarships
======

- National Encouragement Scholarship, 2020--2024
- Cyrus Tang Scholarship, 2020--2024

Interests and Activities
======

- Learned Chinese Chess for 7 years, took part in various competitions
- Took soccer lessons for half a year
- Played badminton for 6 years
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
