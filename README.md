# VK groups network analysis

This repository contains a Jupyter notebook which presents a notework of VK public communities, its analysis and the process of its creation.

The source of this network is VK.

It is a community model – I used [МИЭМ НИУ ВШЭ](https://vk.com/miem_hse) community in VK. It has links to 25 other communities. Those communities also have links to communities and so on. I gathered data those communities and communities linked on their VK pages. The information about 436 was scrapped.

I used BeautifulSoup Python package to parse the webpages.

The characteristics of the network:

- This a directed graph; arrows (nodes) show to which groups one single group refers to.
- As it only shows link connection between groups, it is homogenous.
- It is unweighted.
- It is neither weakly nor strongly connected.
- It doesn't consist of a single attracting component but 1034.
- It is also not semiconnected.
- Nodes don’t have attributes.
- The graph has 1320 nodes and 1757 edges.
- Global clustering coefficient is ~0,0642.
- As the graph is not strongly connected, its diameter and radius are infinite.


The network layout here shows the graph where node size corresponds to node’s degree.

![изображение](https://user-images.githubusercontent.com/55365753/232055801-9eef2dca-0fc9-48ca-853f-b2ff75826a83.png)
