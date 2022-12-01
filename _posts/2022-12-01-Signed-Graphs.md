---
layout: post
title:  "Analysing Signed Graphs with Raphtory"
categories: [Analysis with Raphtory]
author: 'John Pougué-Biyong'
---

## What is a signed graph?

A signed graph is a graph whose edges may be positive or negative. Positive edges typically represent attraction, support, or similarity while negative edges represent repulsion, opposition, antagonism. 

![]({{ site.baseurl }}/images/signedgraphs/signed_graph.jpeg)
*A signed graph.*

We can find these types of interactions with various complex systems. 
* In finance, correlations between stock indexes may be positive or negative. [These correlations can be used to cluster correlated stocks together](https://www.science.org/doi/full/10.1126/sciadv.aav1478). 
* In neuroscience, the brain can be considered as a signed graph where different brain regions are positively or negatively connected based on whether their activity patterns are synchronous or anti-synchronous. [Neuroscientists have used such an approach to explore brain structure](https://www.nature.com/articles/s41598-021-81767-7).
* In the same vein, signed graphs are employed in biology to understand gene regulatory interactions.
* In debates, positive and negative edges represent [agreements and disagreements between actors](https://openreview.net/forum?id=udVUN__gFO). One direct and popular application is the [mining of political factions and opinion groups in online social networks](https://arxiv.org/abs/2201.11675) such as Twitter, Reddit, etc.  

## Analysing your signed graph with Raphtory