---
published: true
topic:
subtitle: 
date: {{date:YYYY-MM-DD}}
tags: 
---

# Graphwiz Testing
{% graphviz %}
digraph {
graph [compound=true, labelloc="b"];
node [shape=box];
edge [dir=none];

Label1[
    label="Label1"
    height="2.1"
    imagepos="tc"
    labelloc="b"
    image="assets/images/Avatar1.png"
];
Label2[
    label="Label2"
    height="2.1"
    imagepos="tc"
    labelloc="b"
    image="images/Avatar2.png"
];
Label3[
    label="Label3"
    height="2.1"
    imagepos="tc"
    labelloc="b"
    image="images/Avatar3.png"
];

{ 
    rank=same;
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
