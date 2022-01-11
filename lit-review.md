# Learning phylogenetic networks

0. Introduction to phylogenetics
    - [Evolution 101](https://threadreaderapp.com/thread/1477332222206423041.html)
    - Phylogenetics 101 youtube videos by Paul Lewis [Part 1](https://www.youtube.com/watch?v=1r4z0YJq580). Other parts 2,3,4 are also good to check out
    - [Phylogenomics book](https://hal.inria.fr/PGE/page/table-of-contents)

1. Understanding probabilities of gene trees under a species tree with the coalescent model: [Degnan2005](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.0014-3820.2005.tb00891.x)

2. Understanding probabilities of gene trees under a species network with the coalescent model: 
    - [Yu2012](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1002660)
    - [Yu2014](https://www.pnas.org/content/111/46/16448)

3. Understanding maximum likelihood estimation on species networks and traversals of network space: [Yu2014](https://www.pnas.org/content/111/46/16448)

4. Understanding maximum pseudolikelihood estimation on species networks to improve scalability: [SolisLemus2016](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1005896)

5. Understanding bayesian inference on species networks:
    - [Wen2016](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1006006)
    - [Zhang2017](https://academic.oup.com/mbe/article/35/2/504/4705834)

6. Understanding identifiability of networks:
    - from pseudolikelihood perspective: [SolisLemus2016](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1005896), [SolisLemus2020](https://arxiv.org/abs/2010.01758)
    - from likelihood perspective: [Zhu2017](https://academic.oup.com/sysbio/article/66/2/283/2682287)
    - from displayed trees (not coalescent-based): [Pardi2015](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004135)

7. Review papers on phylogenetic networks:
    - [Degnan2018](https://academic.oup.com/sysbio/article/67/5/786/5017269)
    - [Blair2019](https://academic.oup.com/sysbio/advance-article/doi/10.1093/sysbio/syz056/5552158)
    - [Kong2021](https://arxiv.org/abs/2109.10251)

8. Moves in network space: [Gambette2017](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005611)

8. Understanding the julia package PhyloNetworks:
    - [Tutorial](https://github.com/crsl4/PhyloNetworks.jl/wiki)
    - [SolisLemus2017](https://academic.oup.com/mbe/article/34/12/3292/4103410?guestAccessKey=1d2c94f2-f064-42ae-a652-ce14cd095442)

9. Other helpful software
    - [TREEasy](https://onlinelibrary.wiley.com/doi/full/10.1111/1755-0998.13149?af=R) to infer gene trees, species trees/networks from multilocus data

10. Simulators
    - [Zombi (python)](https://academic.oup.com/bioinformatics/article/36/4/1286/5578480)
    - [ipcoal (python)](https://www.biorxiv.org/content/10.1101/2020.01.15.908236v1)
    - [HybridSim (java)](https://academic.oup.com/gbe/article/8/5/1299/2939560). [Github](https://github.com/MichaelWoodhams/HybridSim)
    - [NetGen (C)](https://academic.oup.com/bioinformatics/article/22/15/1921/242472)
    - [Birth-Hybridization (BEAST2)](https://academic.oup.com/mbe/article/35/2/504/4705834)
    - [SiPhyNetwork](https://github.com/jjustison/SiPhyNetwork)
