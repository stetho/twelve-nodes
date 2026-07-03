# twelve-nodes

The cranial nerves as a graph.

I had temporal lobe epilepsy, controlled since a partial hippocampectomy. As with everything else about me I learned a lot by osmosis and quite a few MRI scans and filled int he gaps from books. That has given me a solid working knowledge of neuroanatomy - not clinical expertise, but enough to know my way around brain structure and function without needing a reference open the whole time. This project encodes one small, well-defined piece of that knowledge because it's Neuroscience 101 - the twelve cranial nerves, their nuclei, targets, and functions - as a graph, and then applies formal graph theory to see what falls out because why not?

It's a companion piece to the [ML notebook series](https://github.com/stetho/what-i-learned-about-ai) Graph Theory addendum, using the same toolkit (adjacency matrices, degree, centrality, BFS/DFS, shortest path) but here the data is hand-built from domain knowledge rather than illustrative.

## Notebooks

1. **Building the graph** - defining nodes (nerves, nuclei, targets) and edges (anatomical/functional connections), and looking at basic structure
2. *(planned)* Centrality and hubs - which nerves/nuclei sit at structurally important points
3. *(planned)* Comparing against real connectome data - how does a hand-built, function-scale network relate to brain-scale structural connectivity

## Style

First-person research journal voice, thinking out loud rather than tutorial-style.

## Status

Active. Notebook 1 in progress.
