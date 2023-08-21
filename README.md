# Code for ROBOT and MERWE

This repository contains the code (in Python and R) needed to replicate the results of the working paper 
*``Inference via robust optimal transportation: theory and methods''*, by Y. Ma, H. Liu, D. La Vecchia and M. Lerasle. Both Y. Ma and [H. Liu](https://bs.ustc.edu.cn/english/profile-1845.html) are affilited to the University of Science and Technology of China,  [D. La Vecchia](https://sites.google.com/view/davidelavecchia/home) is at the University of Geneva. [M. Lerasle](https://lerasle.perso.math.cnrs.fr) is at CREST-ENSAE, Paris. The working paper version of the manuscript is available on arXiv. Here we dispaly the abstract:

####################

**Abstract.** Optimal transportation theory and the related $p$-Wasserstein distance ($W_p$, $p\geq 1$) are widely-applied in statistics and machine learning. In spite of their popularity, inference based on these tools has some issues. For instance, it is sensitive to outliers and it may not be even defined when the underlying model has infinite moments. To cope with these problems, first we consider a robust version of the primal transportation problem and show that it defines the {robust Wasserstein distance}, $W^{(\lambda)}$, depending on a tuning parameter $\lambda > 0$.  Second, we illustrate the link between $W_1$ and  $W^{(\lambda)}$ and study its key measure theoretic aspects. Third, we derive some concentration inequalities for $W^{(\lambda)}$. Fourth, we use $W^{(\lambda)}$ to define  minimum distance estimators, we provide their statistical guarantees and we illustrate how to apply the derived concentration inequalities for a data driven selection of $\lambda$.  Fifth,  we provide the dual form of the robust optimal transportation problem and we apply it to machine learning problems (generative adversarial networks and domain adaptation).  Numerical exercises %(on simulated and real data) 
provide evidence of the benefits yielded by our novel methods. 

####################


Details abut the files:

1. the folder [MERWE](https://github.com/dvdlvc/Robust-optimal-transportation/tree/main/MERWE) contains the R files needed to reproduce the results in Section 5.2.1 and Section 5.2.2 of the paper (minimum robust Wasserstein estimation);

2. the folder [RWGAN](https://github.com/dvdlvc/Robust-optimal-transportation/tree/main/RWGAN) contains the Python files needed to reproduce the results in Section 5.3.1 and 5.3.2 of the paper (Robust Wasserstein GAN). The availanle code is for both sythetic and real data (see .zip folder);

3. the folder [Robust domain adaptation](https://github.com/dvdlvc/Robust-optimal-transportation/tree/main/Robust_domain_adatation) contains the Python files needed to reproduce the results in Appendix of the paper for the Machine Learning problem: Domain Adaptation via ROBOT.

4. the folder [ROBOT_estimation_oulierdetection](https://github.com/dvdlvc/Robust-optimal-transportation/tree/main/ROBOT_estimation_oulierdetection) contains the Python files needed to reproduce the results in Appendix of the paper in which the Authors illustrate how to use ROBOT to detect outliers first and then to estimate the model parameters via OLS in a regression problem.


Yiming Ma (mayiming@mail.ustc.edu.cn) is the author and the maintainer of the codes. Last update: **12-Jan-2023**.


