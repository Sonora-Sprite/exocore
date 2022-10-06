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

Label1[
    label="Staff 1"
    image="assets/images/staff1.webp"
];

Label2[
    label="Staff 2"
    image="images/staff2.webp"
];
Label3[
    label="Staff 3"
    image="images/staff3.jpg"
];

{ 
    Label1 -> h0 -> Label2;
}

Label1 -> Label2;
Label2-> Label3;
}
{% endgraphviz %}
