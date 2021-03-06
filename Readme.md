# Social Network Analysis in R #

The purpose of this repository is to learn how to run SNA in R during the summer of 2012.

## Examples

Here's a great example of SNA on GitHub using R:
http://www.r-chart.com/2012/05/github-follower-graph-with-r.html

## Characteristics of the Network Data at GitHub ##

The network data consists of the following edges:

* Coders following other coders
* Coders watching repositories
* Repositories being forked off of other repositories
* Coders connected to repositories through commits, comments etc.
* Coders connected to coders through committing or commenting on the same repository, branch, or the same file/commit/issue etc.
* Coders who are on the same team/organization

Hence, there are both directed and undirected graphs, as well as multidimensional since there are both human (coders) and non-human (repositories and their constituent parts) vertices.

N.B. The graph package cannot mix directed and undirected graphs in the same model. Can we work around this within the package or do we need a different package?

These are whole networks, not ego networks, meaning that they are not centered on any given individual.

Anything else?

Strong ties?
Weak ties?

## Potentially Interesting Measures That We Could Correlate With Various Sequence Characteristics ##

* The density (actual ties/possible ties) of a repository network
* Size of network
* Cohesion/Geodesics, i.e. the number of direct paths in the network
* How many other repositories do the coders contribute to?
* Dispersion of code contribution
* Are there cliques in the repository network?
* Centrality of actors in relation to sequences or sequence aspects
* Network centralization (a measure of inequality of contribution in the network as a whole)
* Graph hierarchy (do coders follow each other mutually, or do only certain coders get followed?)
* Least upper boundedness
* Efficiency
* Changes in any of these measures over time

## Thoughts on How to Manage the Summer Course ##

* Maybe we could divide the 10 workshops from the [Stanford SNA in R/SoNIA](http://sna.stanford.edu/rlabs.php) between ourselves, and then go through them one by one?

## Videos ##

* [Issues in Social Network Analysis (CARMA)](http://carma.wayne.edu/Stream.asp?peid=667770c8946c4e10934e102c37c3dd941d)
* [Simple Models for Analyzing Network Changes](http://carma.wayne.edu/Stream.asp?peid=b4d529f13cf24838b20148c22bf3e72c1d)
* [Analyzing Social Networks on Twitter](https://www.youtube.com/watch?v=mK7qmZ2-wxc)
* [Social Network Analysis -- Finding communities and influencers](http://youtu.be/WERsvhCkHhU)
* [Using Whole Genome Sequencing and Social Network Analysis to Track Disease](http://youtu.be/JrwNjqVD5-8)
* [Social Network Analysis, Behavioral Research on HIV/AIDS, UCLA](http://youtu.be/CrYx25m8J9g)

## Resources ##

Here are some resources to get us started:

* [Introduction to social network methods](http://faculty.ucr.edu/~hanneman/nettext/)
* [The R Podcast](http://www.r-podcast.org/)
* [RStudio IDE](http://rstudio.org/)
* [Social Network Analyis Labs - Stanford](http://sna.stanford.edu/rlabs.php)
* [Brief Introduction to SNA](http://www.orgnet.com/sna.html)
* [igraph package - tutorial](http://igraph.sourceforge.net/igraphbook/)
* [Introduction to Social Network Methods](http://faculty.ucr.edu/~hanneman/networks/nettext.pdf)
* [An Introduction to Social Network Analysis with R and NetDraw](http://econometricsense.blogspot.com/2012/04/introduction-to-social-network-analysis.html)
* [Social Network Analysis with sna](http://www.jstatsoft.org/v24/i06/paper)
* [The SIENA package for longitudinal network analysis](http://www.stats.ox.ac.uk/~snijders/siena/)

## References ##

Crowston, K., & Howison, J. 2006. Hierarchy and centralization in free and open source software team communications. **Knowledge, Technology & Policy**, 18(4): 65-85.
	
