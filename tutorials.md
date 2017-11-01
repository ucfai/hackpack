---
layout: hackpack
title: Tutorials

list:
  blogs:
  - title:  "This Week in Machine Learning & AI"
    link:   "twimlai.com"
  - title:  "Import AI"
    link:   "jack-clark.net"
  - title:  "Talking Machines"
    link:   "thetalkingmachines.com"

  youtube:
  - title:  "Siraj Raval"
    link:   "channel/UCWN3xxRkmTPmbKwht9FuE5A"
    tags:   ["Tutorials", "Deep Learning", "YouTube"]
  - title:  "Two Minute Papers"
    link:   "user/keeroyz"
    tags:   ["Research", "YouTube"]
---

{% include modules/hackpack-item.html
  list1=page.list.blogs
  type1="blogs" 
  list2=page.list.youtube
  type2="youtube" %}
