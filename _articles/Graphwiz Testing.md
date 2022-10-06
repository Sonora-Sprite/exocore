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

name1 [shape=box, style=filled, fillcolor=white, color=blue, label=<<TABLE border="0" cellborder="0"><TR><TD width="100" height="100" fixedsize="true"><IMG SRC="/images/staff3.jpg" scale="true"/></TD><td>name1</td></TR></TABLE>>];

imgnode [image="../images/staff3.jpg", label="Staff 3"];

{ 
   imgnode -> Gallery
}

Gallery -> Label2;
name1-> Label3;
}
{% endgraphviz %}
