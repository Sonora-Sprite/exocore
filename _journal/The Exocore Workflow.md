digraph G {

    bgcolor="black"
    node [shape=rectangle, style=filled fillcolor=black, color=white, fontcolor=orange, labelfontcolor=orange];
    edge [color=white, fontcolor=orange, labelfontcolor=orange];

    new [label="New Discord Server:\l Brings Peace.\l (Re)builds infrastructure.\l Gives threads to peasants.\l Protects girls.\l"];
    old [label="Old Dynasty:\l Moderates People too much.\l Stops Protecting Girls.\l Lets infrastructure decay.\l Treats people unfairly.\l"]
    problems [label="Problems:\l Girl exodus.\l  Peasant Revolt  \l Invaders attack Emprire\l Bots raid \l"]
    

  new -> old [label="Generations go by,\l New Server becomes..."];

  old -> problems [label="Old Server loses\l Mandate of Heaven"];
  
  problems -> new [label="New Server claims\l Mandate of Heaven"];
  
  

}