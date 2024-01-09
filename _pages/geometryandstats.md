---
layout: archive
title: "The geometry of statistics"
permalink: /geometryandstats/
author_profile: true
redirect_from:
  - /resume
---

It is exciting to witness the surge of geometric tools permeating modern statistical and machine learning methodologies, spanning from sampling and statistical inference to understanding the underlying data structures. 
My own work, deriving minimum discrepnacie estimators with theoretical guarantees, and numerical integration/sampling algorithms, relied almost
entirely on geometric tools.

Despite this, there exists profound skepticism among statisticians regarding geometry.
In my view, this skepticism primarily stems from two reasons
* Firstly, geometric tools in statistics often originate from mathematics and physics, intertwining statistical notions with irrelevant ones from these fields. This makes it challenging for statisticians to gain insights on these methods. For instance Hamiltonian Monte Carlo is often explained through abstract concepts derived from Hamiltonian mechanics and symplectic structures, which are often unrelated to understanding HMC.
Moreover these tools, e.g., Wasserstein gradients or Langevin processes use notions from geometric measure theory, distributional calculus, and stochastic differential equations. The foundational principles of these tools are hard to grasp for individuals without a background in geometry. For instance, the structure of SDEs, e.g., the Ito correction term, is described by second-order geometry (and cocycles of transformations). Yet, to quote Laurent Schwartz, there is no second-order calculus without tears. More precisely:

  <blockquote>
    <p> "Meyer a intitulé son article "Géométrie stochastique sans larmes";
            je ne suis pas sûr qu’il n’y ait pas de larmes, mais suis à peu près sûr qu’il
            y en a dans le mien. Les larmes paraissent un peu inévitablement liées au calcul
            du second ordre ; on ne pleure pas au premier ordre, on pleure au second, depuis
            déjà des générations."
    </p>
  </blockquote>

* Secondly, while the central objects of physics are inherently geometric, Statistics Departments often teach us the central objects of statistics, distributions, are formalised as measures. However, this viewpoint does not align with how distributions are actually utilised in many statistical methodologies, such as reproducing kernel and "score"-based methods

Fairness towards mathematicians 
=======

To appropriately reference, and leverage, mathematical knowledge, it is crucial to understand the correct mathematical formalizations of the objects used in statistical computations. For example, the very idea of constructing the log-density derivative to utilise the distribituion's differential information, creates a divide between mathematics and statistics, since it introduces an arbitrary choice of reference "measure" and an unjustified logarithm, a practice mathematicians would rarely employ. 

In fact within a single application, distributions will be often be formalised with different structures. 
For instance, when constructing measure-preserving systems for sampling/inference we will typically rely on Lie algebroids and twisted cohomology structures, in which distributions are viewed as 1-densities and twisted top-forms.
On the other hand, when we construct bias-correction tools, we often only use its cocycle structures, while when we study ergodicity we typically use its measure-class structure, in which distributions are viewed as faithful normal weights.

Understanding the foundations of distributions is vital to create a genuinely interdisciplinary environment that amalgamates insights from statisticians, physicists, and mathematicians. It is the reason why for the last three years I have been working on the "Unravelling a Geometric Conspiracy" article, currently in progress, see 
<a href="https://alebarp.github.io/">Geometry of Statistics</a>.

  


