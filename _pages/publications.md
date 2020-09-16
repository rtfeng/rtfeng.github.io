---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Selected Publications
### 2020
  * (TIFS 2020) **Ruitao Feng**, Sen Chen, Xiaofei Xie, Guozhu Meng, Shang-Wei Lin, and Yang Liu. **A Performance-Sensitive Malware Detection System Using Deep Learning on Mobile Devices.** In _the IEEE Transactions on Information Forensics and Security_.
  * (ICECCS 2020) **Ruitao Feng**, Jing Qiang Lim, Sen Chen, Shang-Wei Lin, and Yang Liu. **SeqMobile: An Efficient Sequence-Based Malware Detection System Using RNN on Mobile Devices.** In _Proceedings of the 25th International Conference on Engineering of Complex Computer Systems_.
### 2019
  * (ICECCS 2019) **Ruitao Feng**, Sen Chen, Xiaofei Xie, Lei Ma, Guozhu Meng, Yang Liu, and Shang-Wei Lin. **MobiDroid: A Performance-Sensitive Malware Detection System on Mobile Platform.** In _Proceedings of the 24th International Conference on Engineering of Complex Computer Systems_.
  * (ICFEM 2019) **Ruitao Feng**, Yang Liu, and Shang-Wei Lin. **A Performance-Sensitive Malware Detection System on Mobile Platform.** In _Proceedings of the 21st International Conference on FormalEngineering Methods_.
  * (ICSTW 2019) **Ruitao Feng**, Guozhu Meng, Xiaofei Xie, TingSu, Yang Liu, and Shang-Wei Lin. **Learning Performance Optimization from Code Changesfor Android Apps.** In _Proceedings of the 12th International Conference on Software Testing, Verification and Validation Workshops_.
### 2018
  * (Cybersecurity 2018) Guozhu Meng, **Ruitao Feng**, Guangdong Bai, Kai Chen, and Yang Liu. **DroidEcho: an in Depth Dissecti on of Malicious Behaviors in Android Applications.** In _Cybersecurity_.