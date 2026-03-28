---
title: "Depth First Search"
date: 2026-03-28
tags: []
---


Searching Algorithm for Trees and Graph.

<img width="200" src="https://upload.wikimedia.org/wikipedia/commons/7/7f/Depth-First-Search.gif")>


**How it works** ? 

1. Starts from **Root** node. 
2. choose one neighbour and move to it.
3. Go as deep as possible.
4. You reach a dead end.
5. Backtrack (unvisited nodes) and go deep from that unvisited node.
6. End when all nodes are visited.

Thats why it is called **DFS**, because it always goes deep into one branch of the grapg before exploring others.


Path : A -> B -> D -> E -> H -> C -> F -> G