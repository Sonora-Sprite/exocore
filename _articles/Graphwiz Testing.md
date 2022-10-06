---
published: true
topic:
subtitle: 
date: 2022-10-06
tags: 
---

# Graphwiz Testing
![[staff3.jpg]]
{% graphviz %}

digraph G{
layout=fdp
  e
  Sprite -> a;
  subgraph clusterA [label="AuctionCore"] {
    a -> b;
    b -> D;
    subgraph clusterC {
      C -> D;
    }
  }
  subgraph clusterB {
    d -> f
  }
  d -> D
  e -> clusterB
  clusterC -> clusterB
}
{% endgraphviz %}
