+++
title = "Development"
url = "/development/"
weight = 3
+++

A lot of the research and consulting work I do involves intensive statistical
computing. I also dabble a bit in R development.

<!--more-->

### Statistical Computing

If I had to give myself an academic label, it would probably be "computational
statistician". A great deal of my work revolves around statistical computing. In
my methodological research, I use Monte Carlo simulation as the primary tool by
which to explore the performance of the methods I'm developing or evaluating. As
these methods tend to be some flavor of multiple imputation---which is already
computationally intensive---these simulations often place prohibitive demands on
computing resources. Hence, I have become a serial abuser of high-performance
computing (HPC) clusters such as the [Lisa Compute Cluster][lisa]. My eternal
gratitude goes out to the folks at [SURF][surf] who administer Lisa and many
similar services and provide excellent support for their products.

Likewise, most of my collaborative work is computational. In my experience,
substantive researchers don't need statistical experts to help them run t-tests
or simple linear models, but these simple methods are often inadequate. As my
coauthors and I argue in [this paper][rhd], plausible representations of modern
social-scientific theories---and reasonable tests of the associated
hypotheses---often require advanced modeling approaches such as structural
equation modeling, multilevel modeling, conditional process analysis, or
Bayesian modeling. Similarly, when working with messy real-world data, the
asymptotic assumptions underlying simple, traditional statistical tools are
often grossly violated. In such cases, computationally intensive methods like
cross-validation or resampling methods (e.g., bootstrapping, permutation tests)
are often required to support reasonable statistical modeling, inference, and
prediction.

### Development

As a natural consequence of spending so much of my time immersed in statistical
computation, I also dabble in software development, particularly R package
development. I created my first R package ([MIBRR][mibrr]) after realizing that
my life would be much easier if I packaged the code I was using to implement the
imputation algorithm I was developing for my PhD project. During my postdoc at
[Texas Tech University][ttu], one of my primary tasks was developing the
[PcAux][pcaux] R package. After a few more people joined the PcAux project, I
took on the role of development team lead.

I have also done a few non-statistical programming projects such as [this
utility][examMerge] that I developed for the [Tilburg University][tiu] Student
Administration to merge the results from the online and on-campus versions of
hybrid exams.

Pretty much all of my potentially interesting programming/development work lives
on [my GitHub page][github]. If you would like to contribute to any of my
projects, feel free to submit a pull request.

[lisa]: https://www.surf.nl/en/lisa-compute-cluster-extra-processing-power-for-research
[surf]: https://www.surf.nl/en
[rhd]: https://www.doi.org/10.1080/15427609.2017.1371567
[mibrr]: https://github.com/kylelang/MIBRR
[ttu]: https://www.ttu.edu/
[pcaux]: https://github.com/PcAux-Package/PcAux
[tiu]: https://www.tilburguniversity.edu/
[examMerge]: https://github.com/kylelang/TiU-Exam-Merge
[github]: https://github.com/kylelang/