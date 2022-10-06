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
 bgcolor="black"
    node [shape=rectangle, style=filled fillcolor=black, color=orange, fontcolor=orange, labelfontcolor=orange];
    edge [color=orange, fontcolor=orange, labelfontcolor=orange];
    
imgnode [image="../images/staff3.jpg", label="Staff 3"];

{ 
   imgnode -> Gallery
}

Gallery -> Label2;
name1-> Label3;
}
{% endgraphviz %}
