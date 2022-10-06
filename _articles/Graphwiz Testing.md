---
published: true
topic:
subtitle: 
date: 2022-10-06
tags: 
---

# Graphwiz Testing
digraph G{
layout=fdp

{rank=same; clusterA clusterB;}
{rank=same; clusterAudience;}
  Milady -> "Captivating Image";
  subgraph clusterA  {
    "Captivating Image" -> Faction;
 Faction -> "Violent expansion";
    subgraph clusterC {
      "Violent expansion" ->  clusterAudience;
      
    }
  }
  subgraph clusterB {
    "Shake out" -> "cooling off period"
  }

 subgraph clusterD {
      RemiliaChat
      "Yayo Supplements"
      "Remilia Fashion"
      "Exocore"
      label = "Neet Ascension";
      

  }
  subgraph clusterAudience{
 "Remilia Publishing"
 "Milady Rave" -> "Remilia Records" ;
 label = "Audience"
  }

  clusterA -> clusterB;
  clusterB -> clusterAudience
  clusterAudience -> clusterD
  
 
}
{% endgraphviz %}
