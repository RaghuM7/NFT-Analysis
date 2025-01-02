# NFT-Analysis

A directed acyclic graph of buyer ID’s as vertices is to be built. A directed edge from a buyer i to another buyer j is to be established if there was a transaction to trigger a change of the ownership of the NFT from i to j at the price of the NFT to be assigned as a weight to the edge. Each buyer vertex will record the price of the current buyer paid and carry a time (not the finish time in DFS) tag so no cycles be formed. 

Output the graph in a form of an adjacency matrix. 

Perform DFS, topological sort and then strongly connected components. 

Then, output the acyclic component graph of the strongly connected components in a form of adjacency matrix. 

Ignore the directions on the edges, and then identify a minimum spanning tree and a maximum spanning tree.

Then, output each tree in a form of adjacency matrix along with min or max total and the NFTs involved.

Identify a shortest path tree from an arbitrary buyer.

Then, output the shortest path tree in a form of a adjacency matrix filled with the shortest weight sum and the NFT’s on the path.

