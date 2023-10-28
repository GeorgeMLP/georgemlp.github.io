---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

My name is Jiangyan Ma (George Ma). I am an undergraduate student at Peking University. I am interested in machine learning theories and applications, and am currently doing research on graph learning at Prof. Yisen Wang's lab. I am particularly interested in invariant and universal neural networks. My email: [georgem@stu.pku.edu.cn](mailto:georgem@stu.pku.edu.cn). My homepage: [Jiangyan Ma's Homepage](https://georgemlp.github.io). I actively write blogs on Zhihu: [George M's Zhihu Homepage](https://www.zhihu.com/people/george-m-55).

Education
======
- *Undergraduate; Information and Computing Science*

  I study at School of Electronic Engineering and Computer Science, Peking University. I majored in Applied Physics in the first two years of college and switched to Information and Computing Science thereafter.

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

- June 2023 -- Present; **On the Canonizability of Spectral Embedding**

  In addition to my ongoing research on Laplacian canonization, I am collaborating with researchers from MIT to investigate the correlation between the canonizability of Laplacian eigenvectors and the expressive capabilities of Graph Neural Networks (GNNs) that employ Laplacian eigenvectors as positional encodings. Our focus is on understanding the properties of sign/basis invariance, permutation equivariance, and universal expressiveness within GNNs. We have discovered that these properties cannot be simultaneously achieved in certain GNN structures. We are currently preparing our findings for submission to ICML.

Community Involvement
======

- October 2020 -- June 2021; **Companionship Activity Volunteer**

  Engaged in Companionship Activities organized by the Love Society of Peking University, facilitating letter exchanges with students in impoverished areas across China.

- October 2020 -- June 2021; **Advanced Mathematics Tutoring Volunteer**

  Assisted students in Advanced Mathematics by volunteering as a tutor through the Youth Volunteer Association at the School of Mathematics.

- October 2020 -- June 2021; **Computer Repairing Volunteer**

  Provided regular computer repair assistance to fellow students at Peking University, utilizing my computer skills. Activities were organized by the Youth Volunteer Association at the School of EECS.

- January 2019; **Volunteer to Serve the Elderly**

  Visited an elderly care home in my hometown, Changzhi, along with my high school classmates. We engaged in conversations with the residents and presented them with thoughtful gifts.

Awards
======

- Provincial First Prize of National Mathematics Olympiad in Senior
- Second Prize of the Chinese Mathematics Competitions
- Successful Participant of the Mathematical Contest in Modeling

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
