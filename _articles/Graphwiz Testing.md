---
published: true
topic:
subtitle: 
date: 2022-10-06
tags: 
---

# Graphwiz Testing

{% graphviz %}

digraph G{

imgnode [shapefile="staff3.jpg", label="Staff 3"];

{ 
   imgnode -> Gallery
}

Gallery -> Label2;
name1-> Label3;
}
{% endgraphviz %}
