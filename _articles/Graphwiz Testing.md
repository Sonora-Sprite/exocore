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


subgraph cluster_Rejewski {label="M. Rejewski"; labelloc="b"; Rejewski_icon};
    Rejewski_icon [label="", shapefile="staff3.jpg"];

Label2[
    label="Label2"
    imagepos="tc"
    labelloc="b"
    image="staff3.jpg"
];


imgnode -> Gallery
Rejewski_icon -> Turing_icon;

Gallery -> Label2;
name1-> Label3;
}
{% endgraphviz %}
