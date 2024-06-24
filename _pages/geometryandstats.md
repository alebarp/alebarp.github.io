---
layout: archive
title: "Geometry Vs statistics"
permalink: /geometryandstats/
author_profile: true
redirect_from:
  - /resume
---

It is exciting to witness the surge of geometric tools permeating modern statistical and machine learning methodologies, from sampling and model inference to understanding the structure of data. 
My own work, deriving minimum discrepancy estimators with theoretical guarantees, and developing numerical integration/sampling algorithms, relied almost entirely on geometric ideas.

Despite this, there exists a profound skepticism among statisticians regarding geometry.
It seems this skepticism primarily stems from two reasons:
* Firstly, geometric tools in statistics often originate from mathematics and physics. Consequently, they tend to intertwine statistically relevant geometric concepts with superfluous ones from mathematical physics. This makes it challenging for statisticians to gain insights into these methods. For instance, Hamiltonian Monte Carlo is often explained through abstract concepts derived from Hamiltonian mechanics and symplectic structures, which are often not directly pertinent.
* Secondly, while the central objects of physics are inherently geometric, Statistics Departments often teach us the central objects of statistics, distributions, are formalised as probability measures. However, this viewpoint does not align with how distributions are actually employed in many statistical methodologies, such as reproducing kernel and "score"-based methods.




The unity of statistics 
======

Despite the fact geometric tools are being increasingly leveraged across statistical methodologies,
geometry remains notably absent from the curriculum of most statistics departments,
underscoring the perception it is not directly pertinent to the training of mathematical statisticians.
It turns out that as soon as we use appropriate formalisations of probability distributions, the gap between statistics and geometry disappears. 

The point is that the way mathematicians think of distributions has been continuously evolving. Continuous probability densities, p(x)dx, became absolutely continuous measures, sigma-normal weights, tensor 1-densities, twisted/pseudo differential forms, smooth deRham currents,
classes of Hochschild cycles, berezinian volumes, arrows in the Markov category, Zeta residues, and so on.
Each of these mathematical formalisation incorporates a new understanding of p(x)dx. For instance, tensor 1-densities formalise the probability rate of change which then allows us to correctly talk about the differential information of p(x)dx (which is not its log-density derivative). Without differential geometry we are forced to split p(x) and dx, so that we can differentiate p(x), which is noncanonical and thus isolates statistics from the rest of mathematics. 
On the other hand, von Neumann algebras shed light on the spaces on which probability measures are defined (which are neither measurable nor measure spaces, but something in between: measure class spaces), and their canonical description via C* algebras provides a first acquaintance with the duality between geometric spaces and algebras of ``coordinates" (i.e., functions).

To fully leverage the structure of probability distributions in statistical models, and facilitate the transfer of specialised geometric techniques across statistical applications, we need to stand on the shoulders of the giants that revolutionised mathematics and physics. This, in my opinion, requires acquiring a deeper understanding of statistical objects that goes (very far) beyond  measure/probability theory, as well as incorporating the unity of mathematics within statistical education and methodologies, by constructing a geometric backbone for statistics via the theory of smooth distributions.

<blockquote>
    <p> " [...] one of the most essential features of the mathematical world, [...] it is virtually impossible to isolate any of the above
parts from the others without depriving them from their essence. In that way the
corpus of mathematics does resemble a biological entity which can only survive as
a whole and would perish if separated into disjoint pieces." Alain Connes
    </p>
  </blockquote>


<!--
J'Accuse...! 
=======

To appropriately reference and leverage mathematical knowledge, it is crucial to understand the correct mathematical formalisations of the objects used in statistical computations. For example, the very idea of constructing the log-density derivative, to utilise the distribution's differential information, creates a divide between mathematics and statistics, since it introduces an arbitrary choice of reference "measure" and an unjustified logarithm, a practice mathematicians would rarely employ. 

In fact, within a single application distributions will often be formalised with different structures reflecting the property we are interested in. 
For instance, when constructing measure-preserving systems for sampling/inference we will typically rely on Lie algebroids and twisted cohomology structures, in which distributions are viewed as 1-densities or twisted top-forms.
On the other hand, when we construct bias-correction tools we often only leverage their cocycle structures; when we build discrepancies we typically should view them as continuous linear functionals on function spaces,
while when we study ergodicity we typically use their measure-class structure, in which distributions are viewed as faithful normal weights.

Understanding the foundations of distributions is vital to create a genuinely interdisciplinary environment that amalgamates insights from statisticians, physicists, and mathematicians. It is the reason why for the last three years I have been working on the "Unravelling a Geometric Conspiracy" article, currently in progress, see 
<a href="https://alebarp.github.io/">The unity of statistics</a>.


 Moreover these tools, e.g., Wasserstein gradients or Langevin processes use notions from geometric measure theory, distributional calculus, and stochastic differential equations. The foundational principles of these tools are hard to grasp for individuals without a background in geometry. For instance, the structure of SDEs, e.g., the Ito correction term, is described by second-order geometry (and cocycles of transformations). Yet, to quote Laurent Schwartz, there is no second-order calculus without tears. More precisely:

  <blockquote>
    <p> "Meyer a intitulé son article "Géométrie stochastique sans larmes";
            je ne suis pas sûr qu’il n’y ait pas de larmes, mais suis à peu près sûr qu’il
            y en a dans le mien. Les larmes paraissent un peu inévitablement liées au calcul
            du second ordre ; on ne pleure pas au premier ordre, on pleure au second, depuis
            déjà des générations."
    </p>
  </blockquote>
  
-->
  


