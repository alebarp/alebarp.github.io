---
permalink: /
title: "My background"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a [senior research associate](https://www.turing.ac.uk/people/research-associates/alessandro-barp) at the Alan Turing Institute, working on geometric statistics and machine learning within the [Turing-Roche partnership](https://www.turing.ac.uk/research/research-projects/alan-turing-institute-roche-strategic-partnership).

My academic journey includes completing the MMathPhys course at the University of Warwick, and then Part III of the Mathematical Tripos at the University of Cambridge.
As we enter the large data sets era, there is a growing necessity to comprehend the structure of data, encompassing aspects like reduction, missing data handling, and the integration of misspecification, uncertainty, and domain knowledge into our models. 
This motivated my doctoral research in statistics at Imperial College London and Postdoc at Cambridge, more specfically on Markov Chain Monte Carlo and statistical inference, which aim to sample and approximate complex distributions (see my [thesis](https://spiral.imperial.ac.uk/bitstream/10044/1/84749/1/Barp-A-A-2020-PhD-Thesis.pdf) introducing the bracket-measure formalism).
Recently, my research scope has expanded to include work on geometric deep learning, in order to gain insights in the learning process, so that we can ultimately leverage these tools to improve our understanding patient health heterogeneity.




The unity of statistics and the bracket measure-formalism
======

Despite the fact geometric tools are being increasingly leveraged acrosss statistical methodologies,
geometry remains notably absent from the curriculum of most statistics departments,
underscoring the perception it is not directly pertinent to the training of mathematical statisticians.
It turns out that as soon as we use appropriate formalisations of probability distributions, the gap between statistics and geometry disappears. 
Find out why [here with the bracket-measure formalism](https://drive.google.com/file/d/1OSgegqVHNjGN3XQElhmzm-D4UecBHveu/view?usp=sharing)!

The point is that the way mathematicians think of distributions has been continuously evolving. Continuous probability densities, p(x)dx, became absolutely continuous measures, sigma-normal weights, tensor 1-densities, twisted/pseudo differential forms, smooth continuous linear functionals,
classes of Hochschild cycles, arrows in the Markov category, and so on.
Each of these mathematical formalisation incorporates a new understanding of p(x)dx. For instance tensor 1-densities formalise the probability rate of change which then allows us to correctly talk about the differential information of p(x)dx (which is not its log-density derivative). Without differential geometry we are forced to split p(x) and dx, so that we can differentiate p(x), which is noncanonical and thus isolates statistics from the rest of mathematics. Without von Neumann algebras we are unable to understand the spaces on which probability measures are defined (which are neither measurable nor measure spaces, but something in between: measure class spaces), and their canonical description via C* algebras.
On this aspect I like the related quote by André Lichnerowicz

<blockquote>
    <p> " [...] if we compare what was called
‘physics’ or ‘mathematics’ in the nineteenth century
with today’s physics, what would surprise us would
not be all the equations we write, but rather the
pseudo-rational entities we make up to give them
meaning. What has changed is the discourse, not
the form of the equations."
    </p>
  </blockquote>

To fully leverage the power of probability distributions, we need to stand on the shoulders of the giants that revolutionised mathematics and physics. This requires acquiring a deeper understanding of statistical objects that goes (very far) beyond the measure/probability theory, and incorporating the unity of mathematics within statistical education and methodologies.

<blockquote>
    <p> " [...] one of the most essential features of the mathematical world, [...] it is virtually impossible to isolate any of the above
parts from the others without depriving them from their essence. In that way the
corpus of mathematics does resemble a biological entity which can only survive as
a whole and would perish if separated into disjoint pieces." Alain Connes
    </p>
  </blockquote>
