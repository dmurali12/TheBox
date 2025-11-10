```Kroki
digraph G {
  rankdir=LR;
  graph [bgcolor="transparent"];
  node [shape=box, style="rounded,filled", fillcolor="#f8fafc", color="#cbd5e1"];
  edge [color="#94a3b8"];
  H -> AP [label="TRH"];
  AP -> T [label="TSH"];
  T -> T3;
  T3 -> H [style=dashed, arrowhead=tee, label="– feedback"];
}
```

```
blockdiag {
  Kroki -> generates -> "Block diagrams";
  Kroki -> is -> "very easy!";

  Kroki [color = "greenyellow"];
  "Block diagrams" [color = "pink"];
  "very easy!" [color = "orange"];
}
```

