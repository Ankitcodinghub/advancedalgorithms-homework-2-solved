# advancedalgorithms-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [AdvancedAlgorithms Homework 2 Solved](https://www.ankitcodinghub.com/product/advancedalgorithms-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93133&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;AdvancedAlgorithms Homework 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Question 1

Reduce the Independent Set optimization problem to the Independent Set decision problem. Directions: Assume that you have an algorithm Ad for the decision problem. Formally, Ad(G,k) returns TRUE if G has an Independent Set of size k and FALSE otherwise. You need to describe an algorithm Ao that may run Ad a polynomial number of times. Ao(G) should return a set of vertices forming a maximal Independent Set (MIS) in G. Divide the task into two stages, first find the size of the MIS, then the vertices forming it.

Question 2

Oren works in the HR department of a high-tech company. He organizes a big event with n fun activities to the workers. There are m workers in the company, each of them selects her two favorite activities. Some of the activities will take place in the morning and some in the afternoon. Oren needs to partition the activities into the two shifts, morning and afternoon, in a way that maximizes the number of workers that can participate in their two favorite activities (one of their favorite activities is in the morning shift and the other is in the afternoon shift).

2.0. (warm-up, 0 pts.) Model the above problem as an optimization problem in an undirected and unweighted graph. The answer is below, skip it for now if you want to challenge yourself.

Given an undirected graph G=(V,E), a cut is a bipartition (S,V-S) of V. The size of a cut (S,V- S) is the number of edges with one endpoint on each side of the cut. The maximum cut problem is that of finding a cut of maximum size.

Forasetofvertices⊆andavertex,letc,=| ∈ , ∈|,thatis,the number of ’s neighbors that are in . Consider the following algorithm for finding a cut:

1. Let v1,v2 be two arbitrary distinct vertices

2. Init A  {v1}, B  {v2}

3. Consider the vertices of V -{v1,v2} in arbitrary order

For every considered v  V -{v1,v2}:

If c(v,A)  c(v,B) then B B  {v} else A  A  {v}

4. Return (A,B)

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2.1. (16 pts.) Prove that this is a 2-approximation algorithm for maximum cut.

2.2. (6 pts.) Give the simplest example you can think of on which the algorithm returns a cut whose weight is exactly half the maximum cut.

Question 3

Let G=(V,E) be an undirected graph with nonnegative edge costs. Let RV be a given set of terminal vertices. A Steiner tree is a tree in G that contains all the terminal vertices and any subset of the other vertices.

The Steiner tree problem is the problem of finding a minimum-cost Steiner tree.

The case R=V is simply the Minimum Spanning Tree problem that, as you know, has an optimal polynomial time algorithm. However, the general problem is known to be NP- complete.

Given a complete graph G with weights that obey the triangle inequality, and a subset of vertices R, a possible algorithm for constructing a Steiner tree for R simply finds an MST on the subgraph induced by R (since the graph is complete this subgraph is also complete, and in particular is connected). Prove that this algorithm is a 2-approximation algorithm.

Guidelines: Let T* be an optimal Steiner tree for R. Consider doubling each edge, and finding an Euler cycle P on the resulting graph (with parallel edges, as we did in class in the TSP approximation alg.). Next consider the path H that results from removing from P all vertices that do not belong to R and keeping only the first appearance of every vertex in R (shortcuts).

Question 4

Given an instance of Bin-Packing in which all items have size at most 1/5.

4.1. (14 pts.) Show that Next-fit algorithm packs the items in less than  ∙OPT+  bins, where OPT is the minimal number of bins required to pack the items.

4.2. (8 pts.) Show that the analysis is tight. Specifically, given n, describe an instance with (n) items such that Next-fit uses at least  ∙OPT –  bins (which is one bin less than the bound provided by the analysis).

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Question 5

Read and understand the following example, showing that the analysis of Christofides’ Algorithm (3/2-approx to TSP) is tight. Consider the graph in the figure.

It consists of 2n+1 nodes: n in the top row and n+1 in the lower row. All solid edges have weight 1, all dashed edges have weight 1+. The other edges are omitted from the figure, each has the maximal weight satisfying the triangle inequality (for example, (u,v) has cost (1+)n).

Algorithm: The only MST consists of all solid lines, it is a path, and has length 2n.

The first and last nodes have odd degree. The min-weight matching is simply the edge connecting them, which has length (1+)n (not drawn, by the -ineq). All together, the TSP path detected by the algorithm has length ~3n.

An optimal tour: the dashed edges + the leftmost and rightmost edges.

Its length is (2n-1)(1+) +2 =~2n.

For full credit, declare that you read and understood the example and why it shows that the analysis is tight. For partial credit, specify what you failed to understand.

</div>
</div>
</div>
