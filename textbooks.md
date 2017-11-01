---
layout: hackpack
title: Textbooks

list:
  general:
    - title:  "Machine Learning: A Probabilistic Perspective"
      author: "Kevin Murphy"
      link:
    - title: "Artificial Intelligence: A Modern Approach"
      author: "Stuart Russel and Peter Norvig"
      link:

  specific:
    - title:  "Make Your Own Neural Network"
      author: "Tariq Rashid"
      link:
    - title:  "Neural Networks and Deep Learning"
      author: "Michael Nielson"
      link:   "http://neuralnetworksanddeeplearning.com/"
    - title:  "Deep Learning"
      author: "Ian Goodfellow, Yoshua Bengio, and Aaron Courville"
      link:   "http://www.deeplearningbook.org/"
---

{% include modules/hackpack-item.html
  list1=page.list.general
  type1="general" 
  list2=page.list.specific
  type2="specific" %}
