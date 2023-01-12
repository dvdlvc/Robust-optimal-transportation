# Code for ROBOT and MERWE

This repository contains the code (in Python and R) needed to replicate the results of the working paper 
*``Theoretical and computational aspects of robust optimal transportation, with applications to statistics and machine learning''*, by Y. Ma, H. Liu and D. La Vecchia. Both Y. Ma and [H. Liu](https://bs.ustc.edu.cn/english/profile-1845.html) are affilited to the University of Science and Technology of China, while [D. La Vecchia](https://sites.google.com/view/davidelavecchia/home) is at the University of Geneva. The working paper version of the manuscript is available on arXiv. Here we dispaly the abstract:

####################

**Abstract.** Optimal transport (OT) theory and the related p-Wasserstein distance (denoted by $W_p$  with $p \geq 1$) are popular tools in statistics and machine learning. Recent studies have been remarking that inference based on OT and on Wp is sensitive to outliers. To cope with this issue, we work on a robust version of the primal OT problem (ROBOT) and we show that it defines a robust version of $W_1$. This novel distance is able to downweight the impact of outliers: we label it robust Wasserstein distance, we study its properties and we use it to define minimum distance estimators. Our novel estimators do not impose any moment restrictions: this allows us to extend the use of OT methods to inference on heavy-tailed distributions. We provide the statistical guarantees of the proposed estimators. Moreover, we derive the dual form of the ROBOT, and we illustrate its applicability to machine learning. Numerical exercises provide evidence of the benefits yielded by our methods.

####################


Details abut the files:

1. the folder [MERWE](https://github.com/dvdlvc/Robust-optimal-transportation/tree/main/MERWE) contains the R files needed to reproduce the results in Section 5.2.1 and Section 5.2.2 of the paper (minimum robust Wasserstein estimation);

2. the folder [RWGAN](https://github.com/dvdlvc/Robust-optimal-transportation/tree/main/RWGAN) contains the Python files needed to reproduce the results in Section 5.3.1 and 5.3.2 of the paper (Robust Wasserstein GAN). The availanle code is for both sythetic and real data (see .zip folder);

3. the folder [Robust domain adaptation](https://github.com/dvdlvc/Robust-optimal-transportation/tree/main/Robust_domain_adatation) contains the Python files needed to reproduce the results in Appendix of the paper for the Machine Learning problem: Domain Adaptation via ROBOT.

4. the folder [ROBOT_estimation_oulierdetection](https://github.com/dvdlvc/Robust-optimal-transportation/tree/main/ROBOT_estimation_oulierdetection) contains the Python files needed to reproduce the results in Appendix of the paper in which the Authors illustrate how to use ROBOT to detect outliers first and then to estimate the model parameters via OLS in a regression problem.


Yiming Ma (mayiming@mail.ustc.edu.cn) is the author and the maintainer of the codes. Last update: **12-Jan-2023**.
