---
published: true
topic:
subtitle: 
date: 2022-10-06
tags: 
---

# Graphwiz Testing

{% graphviz %}
digraph {
graph [compound=true, labelloc="b"];
node [shape=box];
edge [dir=none];

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
    rank=same
    Label1 -> h0 -> Label2;
    h0[shape=circle,label="",height=0.01,width=0.01];
}
{
    h0_0;
    h0_0[shape=circle,label="",height=0.01,width=0.01];
}

h0 -> h0_0;
h0_0 -> Label3;
}
{% endgraphviz %}
