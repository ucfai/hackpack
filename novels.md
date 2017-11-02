---
layout: hackpack
title: Novels

list:
  nonfiction:
  - title:  "Godel, Escher, Bach: An Eternal Golden Braid"
    author: "Douglas Hofstadter"
    link:
  - title:  "Mind Design II"
    author: "John Haugeland (Editor)"
    link:
  - title:  "The Master Algorithm"
    author: "Pedro Domingos"
    link:
  - title:  "The Society of Mind"
    author: "Marvin Minsky"
    link:
  - title:  "The Emotion Machine"
    author: "Marvin Minsky"
    link:

  fiction:
---

{% include modules/hackpack-item.html
  list1=page.list.nonfiction
  type1="novels-nonfiction" 
  list2=page.list.fiction
  type2="novels-fiction" %}
