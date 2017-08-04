<h1> Triad Motif Significance Profile </h1>
Project for AIT-Budapest's networks course.



<h2>Background</h2>
A motif is a small, connected subgraph in which the configuration of the links is predefined. It is a 
subgraph pattern that appears significantly more often than expected at random.

It is the building block for complex networks and can assist us in understanding the structural design principles of a complex network.

<a href="https://en.wikipedia.org/wiki/Network_motif">Network Motif</a>

There are 13 triad motifs in a directed graph.

We analyze each motif by giving it a z-score, which will tell us if we observe a
motif occurring more often than one would expect, indicating it is important to the functioning of the network. Likewise,
an under-representation can tell us a great deal.

<a href="http://mavisto.ipk-gatersleben.de/z_score.html">Z-score</a>

The signifcance profile is the vector of normalized Z-scores for a network.

<h2>Main Objective</h2>
To extract and visualize various triad motif significance profiles
<ol>
  <li>Determine input networks</li>
  <li>Calculate Z-score of each motif and creating the SP</li>
  <li>Plot and display profiles and networks</li>
</ol>

<h2>Input Networks</h2>

Biological networks
<ul>
  <li>E-coli transcription</li>
  <li>Yeast transcription</li>
</ul>
Social networks
<ul>
  <li>Prison network</li>
</ul>

<h2>Calculating Z-scores</h2>
Get the frequency of each of the thirteen triad motifs in a graph
<ul>
  <li>networkx's triadic_census</li>
</ul>

Get the average frequency of each of the thirteen triad motifs in a set of randomized graph
<ul>
  <li>Implement a randomization method</li>
  <li>Need degree preservation</li>
</ul>
  
</ul>
Get the standard deviation for this random average frequency
<ul>
  <li>python numpy.std</li>
</ul>

Generating the significance profile is simply a matter of taking the vector of the normalized z-scores.

<h2>Plotting Results</h2>
<ul>
  <li>Plot graphs after and before randomization w/Cytoscape + networkx</li>
  <li>Plot the significance profile w/networkx</li>
 
</ul>

<h2>Graphs</h2>
Visual results and graphs can be found in the main .ipynb files. A slide presentation is also available.





