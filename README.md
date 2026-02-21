# Awesome Machine Learning for Crypto(Lattice Problem)

We would like to maintain a list of resources that focus on solving lattice problems, particularly the Shortest Vector Problem (SVP) and related tasks like lattice basis reduction, utilizing classical algorithms, heuristic methods, and modern machine learning technologies.

*Maintained by Jinchen Yu, Wenzheng Pan, Xinhao Zheng, Yuhao Zhang, Junchi Yan. We thank all the researchers who have contributed to this field.*

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey & Foundations</a></td></tr>
<tr><td colspan="2"><a href="#problems">2. Problems</a></td></tr>
<tr>
    <td>&emsp;<a href="#lattice-reduction">2.1 Lattice Reduction (LLL, BKZ, etc.)</a></td>
    <td>&emsp;<a href="#shortest-vector-problem-svp">2.2 Shortest Vector Problem (SVP)</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#closest-vector-problem-cvp">2.3 Closest Vector Problem (CVP)</a></td>
    <td>&emsp;<a href="#machine-learning-for-lattice-problems">2.4 Machine Learning for Lattice Problems</a></td>
</tr>
</table>

## [Survey Papers & Foundations](#content)

*This section includes foundational papers that define the problems and survey classical solution methods.*

1.  **Factoring polynomials with rational coefficients.** Mathematische Annalen, 1982. [journal](https://link.springer.com/article/10.1007/BF01457454)
    *Lenstra, A. K. and Lenstra, H. W. and Lovász, L.*

2.  **Improved algorithms for integer programming and related lattice problems.** STOC, 1983. [paper](https://dl.acm.org/doi/abs/10.1145/800061.808749)
    *Kannan, Ravi.*

3.  **Minkowski's convex body theorem and integer programming.** Mathematics of operations research, 1987. [journal](https://pubsonline.informs.org/doi/abs/10.1287/moor.12.3.415)
    *Kannan, Ravi.*

4.  **Improved methods for calculating vectors of short length in a lattice, including a complexity analysis.** Mathematics of computation, 1985. [journal](https://www.ams.org/mcom/1985-44-170/S0025-5718-1985-0777278-8/)
    *Fincke, Ulrich and Pohst, Michael.*

5.  **On the computation of lattice vectors of minimal length, successive minima and reduced bases with applications.** ACM Sigsam Bulletin, 1981. [journal](https://dl.acm.org/doi/abs/10.1145/1089242.1089247)
    *Pohst, Michael.*

6.  **Lattice basis reduction: Improved practical algorithms and solving subset sum problems.** Mathematical programming, 1994. [journal](https://link.springer.com/article/10.1007/BF01581121)
    *Schnorr, Claus-Peter and Euchner, Martin.*

7.  **Closest vector problem.** In *Complexity of lattice problems: a cryptographic perspective*, 2002. [journal](https://link.springer.com/chapter/10.1007/978-1-4615-0897-7_4)
    *Micciancio, Daniele and Goldwasser, Shafi.*

8.  **On lattices, learning with errors, random linear codes, and cryptography.** Journal of the ACM (JACM), 2009. [journal](https://dl.acm.org/doi/abs/10.1145/1568318.1568324)
    *Regev, Oded.*

## [Problems](#content)

### [Lattice Reduction](#content)

1.  **Factoring polynomials with rational coefficients.** Mathematische Annalen, 1982. [journal](https://link.springer.com/article/10.1007/BF01457454)
    *Lenstra, A. K. and Lenstra, H. W. and Lovász, L.*

2.  **Lattice basis reduction: Improved practical algorithms and solving subset sum problems.** Mathematical programming, 1994. [journal](https://link.springer.com/article/10.1007/BF01581121)
    *Schnorr, Claus-Peter and Euchner, Martin.*

3.  **Attacking the Chor-Rivest cryptosystem by improved lattice reduction.** EUROCRYPT, 1995. [paper](https://link.springer.com/chapter/10.1007/3-540-49264-X_1)
    *Schnorr, Claus-Peter and Hörner, Horst Helmut.*

4.  **BKZ 2.0: Better lattice security estimates.** ASIACRYPT, 2011. [paper](https://link.springer.com/chapter/10.1007/978-3-642-25385-0_1)
    *Chen, Yuanmi and Nguyen, Phong Q.*

5.  **PotLLL: a polynomial time version of LLL with deep insertions.** Designs, codes and cryptography, 2014. [journal](https://link.springer.com/article/10.1007/s10623-012-9696-6)
    *Fontein, Felix and Schneider, Michael and Wagner, Urs.*

6.  **Practical, predictable lattice basis reduction.** EUROCRYPT, 2016. [paper](https://link.springer.com/chapter/10.1007/978-3-662-49896-5_28)
    *Micciancio, Daniele and Walter, Michael.*

7.  **Improved progressive BKZ algorithms and their precise cost estimation by sharp simulator.** EUROCRYPT, 2016. [paper](https://link.springer.com/chapter/10.1007/978-3-662-49896-5_29)
    *Aono, Yoshinori and Wang, Yuntao and Hayashi, Takuya and Takagi, Tsuyoshi.*

8.  **Explicit formula for Gram-Schmidt vectors in LLL with deep insertions and its applications.** International Conference on Number-Theoretic Methods in Cryptology, 2017. [paper](https://link.springer.com/chapter/10.1007/978-3-319-76620-1_9)
    *Yamaguchi, Junpei and Yasuda, Masaya.*

9.  **A new polynomial-time variant of LLL with deep insertions for decreasing the squared-sum of Gram–Schmidt lengths.** Designs, Codes and Cryptography, 2019. [journal](https://link.springer.com/article/10.1007/s10623-019-00623-0)
    *Yasuda, Masaya and Yamaguchi, Junpei.*

10. **Self-dual DeepBKZ for finding short lattice vectors.** Journal of Mathematical Cryptology, 2020. [journal](https://www.degruyter.com/document/doi/10.1515/jmc-2017-0032/html)
    *Yasuda, Masaya.*

11. **Development of a dual version of DeepBKZ and its application to solving the LWE challenge.** AFRICACRYPT, 2018. [paper](https://link.springer.com/chapter/10.1007/978-3-319-89339-6_10)
    *Yasuda, Masaya and Yamaguchi, Junpei and Ooka, Michiko and Nakamura, Satoshi.*

### [Shortest Vector Problem (SVP)](#content)

1.  **The shortest vector problem in L2 is NP-hard for randomized reductions.** STOC, 1998. [paper](https://dl.acm.org/doi/abs/10.1145/276698.276705)
    *Ajtai, Miklós.*

2.  **A sieve algorithm for the shortest lattice vector problem.** STOC, 2001. [paper](https://dl.acm.org/doi/abs/10.1145/380752.380857)
    *Ajtai, Miklós and Kumar, Ravi and Sivakumar, Dandapani.*

3.  **Parallel enumeration of shortest lattice vectors.** Euro-Par, 2010. [paper](https://link.springer.com/chapter/10.1007/978-3-642-15277-1_20)
    *Dagdelen, Özgür and Schneider, Michael.*

4.  **Lattice enumeration using extreme pruning.** EUROCRYPT, 2010. [paper](https://link.springer.com/chapter/10.1007/978-3-642-13190-5_14)
    *Gama, Nicolas and Nguyen, Phong Q. and Regev, Oded.*

5.  **Faster exponential time algorithms for the shortest vector problem.** SODA, 2010. [paper](https://epubs.siam.org/doi/abs/10.1137/1.9781611973075.119)
    *Micciancio, Daniele and Voulgaris, Panagiotis.*

6.  **Sieve algorithms for the shortest vector problem are practical.** Journal of Mathematical Cryptology, 2008. [journal](https://www.degruyter.com/document/doi/10.1515/JMC.2008.009/html)
    *Nguyen, Phong Q. and Vidick, Thomas.*

7.  **Improved Nguyen-Vidick heuristic sieve algorithm for shortest vector problem.** ASIACCS, 2011. [paper](https://dl.acm.org/doi/abs/10.1145/1966913.1966915)
    *Wang, Xiaoyun and Liu, Mingjie and Tian, Chengliang and Bi, Jingguo.*

8.  **Solving shortest and closest vector problems: The decomposition approach.** IACR Cryptology ePrint Archive, 2013. [paper](https://eprint.iacr.org/2013/229)
    *Becker, Anja and Gama, Nicolas and Joux, Antoine.*

9.  **Speeding-up lattice sieving without increasing the memory, using sub-quadratic nearest neighbor search.** IACR Cryptology ePrint Archive, 2015. [paper](https://eprint.iacr.org/2015/522)
    *Becker, Anja and Gama, Nicolas and Joux, Antoine.*

10. **Sieving for shortest vectors in lattices using angular locality-sensitive hashing.** CRYPTO, 2015. [paper](https://link.springer.com/chapter/10.1007/978-3-662-47989-6_1)
    *Laarhoven, Thijs.*

11. **New directions in nearest neighbor searching with applications to lattice sieving.** SODA, 2016. [paper](https://epubs.siam.org/doi/abs/10.1137/1.9781611974331.ch2)
    *Becker, Anja and Ducas, Léo and Gama, Nicolas and Laarhoven, Thijs.*

12. **Shortest vector from lattice sieving: a few dimensions for free.** EUROCRYPT, 2018. [paper](https://link.springer.com/chapter/10.1007/978-3-319-78381-9_5)
    *Ducas, Léo.*

13. **The general sieve kernel and new records in lattice reduction.** EUROCRYPT, 2019. [paper](https://link.springer.com/chapter/10.1007/978-3-030-17656-3_25)
    *Albrecht, Martin R. and Ducas, Léo and Herold, Gottfried and Kirshanova, Elena and Postlethwaite, Eamonn W. and Stevens, Marc.*

14. **Darmstadt SVP challenges.** [website](https://www.latticechallenge.org/svp-challenge/)
    *Schneider, Michael and Gama, Nicolas.*

### [Closest Vector Problem (CVP)](#content)

1.  **Bounded-distance decoding: algorithms, decision regions, and pseudo nearest neighbors.** IEEE Transactions on Information Theory, 2002. [journal](https://ieeexplore.ieee.org/document/765146)
    *Amrani, Ofer and Be'ery, Yair.*

2.  **On bounded distance decoding, unique shortest vectors, and the minimum distance problem.** CRYPTO, 2009. [paper](https://link.springer.com/chapter/10.1007/978-3-642-03356-8_33)
    *Lyubashevsky, Vadim and Micciancio, Daniele.*

3.  **Closest vector problem.** In *Complexity of lattice problems: a cryptographic perspective*, 2002. [journal](https://link.springer.com/chapter/10.1007/978-1-4615-0897-7_4)
    *Micciancio, Daniele and Goldwasser, Shafi.*

4.  **Lattice reduction.** IEEE Signal Processing Magazine, 2011. [journal](https://ieeexplore.ieee.org/abstract/document/5740630)
    *Wübben, Dirk and Seethaler, Dominik and Jalden, Joakim and Matz, Gerald.*

### [Machine Learning for Lattice Problems](#content)

1.  **Neural Lattice Reduction: A Self-Supervised Geometric Deep Learning Approach.** arXiv, 2023. [paper](https://arxiv.org/abs/2311.08170)
    *Marchetti, Giovanni Luca and Cesa, Gabriele and Kumar, Pratik and Behboodi, Arash.*

2.  **Salsa: Attacking lattice cryptography with transformers.** NeurIPS, 2022. [paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/e5f1b398c18a8a1248239a3a47ec8d5d-Abstract-Conference.html)
    *Wenger, Emily and Chen, Mingjie and Charton, Francois and Lauter, Kristin E.*

3.  **Attack on Shortest Vector Problem of Lattice Using Machine Learning.** International Conference on Trends in Computational and Cognitive Engineering, 2023. [paper](https://link.springer.com/chapter/10.1007/978-981-99-7483-2_34)
    *Singh, Shaurya Pratap and Chaurasia, Brijesh Kumar and Tripathi, Tanmay and Gupta, Siddharth and Pal, Ayush.*

4.  **Heuristic time complexity of nisq shortest-vector-problem solvers.** arXiv, 2025. [paper](https://arxiv.org/abs/2502.05284)
    *Prokop, Miloš and Wallden, Petros.*

5.  **RL4CO: a Unified Reinforcement Learning for Combinatorial Optimization Library.** NeurIPS Workshop, 2023. [paper](https://openreview.net/forum?id=0eVwH7vN6a) [code](https://github.com/kaist-silab/RL4CO)
    *Berto, Federico and Hua, Chuanbo and Park, Junyoung and Kim, Minsu and Kim, Hyeonah and Son, Jiwoo and Kim, Haeyeon and Kim, Joungho and Park, Jinkyoo.*

6.  **DIFUSCO: Graph-based Diffusion Solvers for Combinatorial Optimization.** NeurIPS, 2023. [paper](https://openreview.net/forum?id=JV8Ff0lgVV) [code](https://github.com/Edward-Sun/DIFUSCO)
    *Sun, Zhiqing and Yang, Yiming.*

7.  **Fast T2T: Optimization consistency speeds up diffusion-based training-to-testing solving for combinatorial optimization.** NeurIPS, 2024. [paper](https://openreview.net/forum?id=xDrKZOZEOc) [code](https://github.com/Thinklab-SJTU/Fast-T2T)
    *Li, Yang and Guo, Jinpei and Wang, Runzhong and Zha, Hongyuan and Yan, Junchi.*

8.  **COExpander: Adaptive Solution Expansion for Combinatorial Optimization.** ICML, 2025. [paper](https://openreview.net/forum?id=KMaBXMWsBM) [code](https://github.com/Thinklab-SJTU/COExpander)
    *Ma, Jiale and Pan, Wenzheng and Li, Yang and Yan, Junchi.*

9.  **ML4CO-Bench-101: Benchmark Machine Learning for Classic Combinatorial Problems on Graphs.** NeurIPS, 2025. [paper](https://openreview.net/forum?id=ye4ntB1Kzi) [code](https://github.com/Thinklab-SJTU/ML4CO-Bench-101)
    *Ma, Jiale and Pan, Wenzheng and Li, Yang and Yan, Junchi.*

10. **UniCO: On Unified Combinatorial Optimization via Problem Reduction to Matrix-Encoded General TSP.** ICLR, 2025. [paper](https://openreview.net/forum?id=yEwakMNIex) [code](https://github.com/Thinklab-SJTU/UniCO)
    *Pan, Wenzheng and Xiong, Hao and Ma, Jiale and Zhao, Wentao and Li, Yang and Yan, Junchi.*

11. **A Diffusion Model Framework for Unsupervised Neural Combinatorial Optimization.** ICML, 2024. [paper](https://arxiv.org/abs/2406.01661) [code](https://github.com/ml-jku/DIffUCO)
    *Sanokowski, Sebastian and Hochreiter, Sepp and Lehner, Sebastian.*

12. **Unsupervised Learning for Combinatorial Optimization Needs Meta Learning.** ICLR, 2023. [paper](https://openreview.net/forum?id=-ENYHCE8zBp) [code](https://github.com/Graph-COM/Meta_CO)
    *Wang, Haoyu Peter and Li, Pan.*

## [Related Algorithms & Tools](#content)

1.  **Numerical aspects of Gram-Schmidt orthogonalization of vectors.** Linear algebra and its applications, 1983. [journal](https://www.sciencedirect.com/science/article/pii/0024379583905283)
    *Ruhe, Axel.*

2.  **Learning representations by back-propagating errors.** Nature, 1986. [journal](https://www.nature.com/articles/323533a0)
    *Rumelhart, David E. and Hinton, Geoffrey E. and Williams, Ronald J.*

3.  **A quantum approximate optimization algorithm.** arXiv, 2014. [paper](https://arxiv.org/abs/1411.4028)
    *Farhi, Edward and Goldstone, Jeffrey and Gutmann, Sam.*

4.  **Report on post-quantum cryptography.** National Institute of Standards and Technology, 2016. [journal](https://nvlpubs.nist.gov/nistpubs/ir/2016/NIST.IR.8105.pdf)
    *Chen, Lily and Jordan, Stephen and Liu, Yi-Kai and Moody, Dustin and Peralta, Rene and Perlner, Ray A. and Smith-Tone, Daniel.*

5.  **Proximal policy optimization algorithms.** arXiv, 2017. [paper](https://arxiv.org/abs/1707.06347)
    *Schulman, John and Wolski, Filip and Dhariwal, Prafulla and Radford, Alec and Klimov, Oleg.*

6.  **Proximal policy optimization and its dynamic version for sequence generation.** arXiv, 2018. [paper](https://arxiv.org/abs/1808.07982)
    *Tuan, Yi-Lin and Zhang, Jinzhi and Li, Yujia and Lee, Hung-yi.*

7.  **HEBO: Pushing The Limits of Sample-Efficient Hyperparameter Optimisation.** Journal of Artificial Intelligence Research, 2022. [journal](https://www.jair.org/index.php/jair/article/view/13652) [code](https://github.com/huawei-noah/HEBO)
    *Cowen-Rivers, Alexander and Lyu, Wenlong and Tutunov, Rasul and Wang, Zhi and Grosnit, Antoine and Griffiths, Ryan-Rhys and Maravel, Alexandre and Hao, Jianye and Wang, Jun and Peters, Jan and Ammar, Haitham Bou.*
