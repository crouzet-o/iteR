# i(nformation) t(ransmission and) e(ntropy with) R

A package for computing Information Transfer rates / Mutual Information and Entropy in R

This package is currently in active development. It has been designed for linguists as well as speech and cognitive scientists and will provide functions for the computation of Information Transfer Rates in Confusion Matrices as described in Miller & Nicely (1955) and later in Christiansen & Greenberg (2012) as well as for the computation of Mutual Information in coarticulated speech (Iskarous et al, 2013).

Although some packages exist that alread provide access to such tools (entropy, infotheo) they are rather complementary to each other and also lack some coherence (e.g. in terms of input objects). There is also a freely available script that computes SINFA analyses but is not published as a package. iteR will serve in part as a common interface to existing packages and will also provide specific utilities (computation of relative / normalized MI, manipulation of confusion matrices, graphical tools, inference tools), relying partly on the power of available tools while providing specific functions and documentation that will be more easily accessible to non-specialists (esp. linguists, speech scientists, cognitive scientists).


# Notes (TODO)

SINFA (Sequential INFormation Analysis) is a method that can provide analyses of the relative information transfer rates between features (Wang & Bilger, 1973).
