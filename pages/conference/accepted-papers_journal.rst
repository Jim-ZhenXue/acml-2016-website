.. title: Accepted Papers (Journal Track)
.. slug: accepted-papers-journal-track
.. date: 2015-12-10 10:09:26 UTC+13:00
.. tags: draft
.. category: 
.. link: 
.. description: 
.. type: text

.. raw:: html

   <ul class="simple">

   <li>
   <span class="paper-title"><strong>A Unified Probabilistic Framework for Robust Manifold Learning and Embedding</strong> - Qi Mao, Li Wang, Ivor W. Tsang <span class="paper-abstract-link">[abstract]</span>
   <div class="paper-abstract">This paper focuses on learning a smooth skeleton structure from noisy data - an emerging topic in the fields of computer vision and computational biology. Many dimensionality reduction methods have been proposed, but none are specially designed for this purpose. To achieve this goal, we propose a unified probabilistic framework that directly models the posterior distribution of data points in an embedding space so as to suppress data noise and reveal the smooth skeleton structure. Within the proposed framework, a sparse positive similarity matrix is obtained by solving a box-constrained convex optimization problem, in which the sparsity of the matrix represents the learned neighborhood graph and the positive weights stand for the new similarity. Embedded data points are then obtained by applying the maximum a posteriori estimation to the posterior distribution expressed by the learned similarity matrix. The embedding process naturally provides a probabilistic interpretation of Laplacian eigenmap and maximum variance unfolding. Extensive experiments on various datasets demonstrate that our proposed method obtains the embedded points that accurately uncover inherent smooth skeleton structures in terms of data visualization, and the method yields superior clustering performance compared to various baselines.</div></span>
   </li>

   <li>
   <span class="paper-title"><strong>Collaborative Topic Regression for Online Recommender Systems: An Online and Bayesian Approach</strong> - Chenghao Liu, Tao Jin, Steven C.H. Hoi, Peilin Zhao, Jianling Sun <span class="paper-abstract-link">[abstract]</span>
   <div class="paper-abstract">Collaborative Topic Regression (CTR) combines ideas of probabilistic matrix factorization (PMF) and topic modeling (e.g., LDA) for recommender systems, which has gained increasing successes in many applications. Despite enjoying many advantages, the existing Batch Decoupled Inference algorithm for CTR model (bdi-CTR) has some critical limitations. First of all, it is designed to work in a batch learning manner, making them unsuitable to deal with streaming data or big data in real-world recommender systems. Second, the item-specific topic proportions of LDA are fed to the downstream PMF, but not reverse, which is sub-optimal as the rating information is not exploited in discovering the low-dimensional representation of documents and thus can result in a sub-optimal representation for prediction. In this paper, we propose a novel inference algorithm, called the Online Bayesian Inference algorithm for CTR model (obi-CTR), which is efficient and scalable for learning from data streams. Particularly, we {\it jointly} optimize the combined objective function of both PMF and LDA in an online learning fashion, in which both PMF and LDA tasks can be reinforced each other during the online learning process. Our encouraging experimental results on real-world data validate the effectiveness of the proposed method.</div></span>
   </li>

   <li>
   <span class="paper-title"><strong>Multi-view Kernel Completion</strong> - Sahely Bhadra, Samuel Kaski, Juho Rousu <span class="paper-abstract-link">[abstract]</span>
   <div class="paper-abstract">In this paper, we introduce the first method that (1) can complete kernel matrices with completely missing rows and columns as opposed to individual missing kernel values, with help of information from other incomplete kernel matrices. Moreover, (2) the method does not require any of the kernels to be complete a priori, and (3) can tackle non-linear kernels. The kernel completion is done by finding, from the set of available incomplete kernels, an appropriate set of related kernels for each missing entry.These aspects are necessary in practical applications such as integrating legacy data sets, learning under sensor failures and learning when measurements are costly for some of the views. The proposed approach predicts missing rows by modeling both within-view and between-view relationships among kernel values. For within-view learning, we propose a new kernel approximation that generalizes and improves Nyström approximation. We show, both on simulated data and real case studies, that the proposed method outperforms existing techniques in the settings where they are available, and extends applicability to new settings.</div></span>
   </li>

   <li>
   <span class="paper-title"><strong>Non-redundant Multiple Clustering by Nonnegative Matrix Factorization</strong> - Sen Yang, Lijun Zhang <span class="paper-abstract-link">[abstract]</span>
   <div class="paper-abstract">Clustering is one of the basic tasks in data mining and machine learning which aims at discovering the hidden structure of the data. For many real-world applications, there often exist many different yet meaningful clusterings while most of existing clustering methods only produce a single clustering. To address this limitation, multiple clustering, which tries to generate clusterings that are with high quality and different from each other, has emerged recently. In this paper, we propose a novel alternative clustering method that generates non-redundant multiple clusterings sequentially. The algorithm is built upon Nonnegative Matrix Factorization (NMF), and we take advantage of the nonnegative property to enforce the non-redundancy. Specifically, we design a quadratic term to measure the redundancy between the reference clustering and the new clustering, and incorporate it into the objective. The optimization problem takes on a very simple form, and can be solved efficiently by multiplicative updating rules. Experimental results demonstrate that the proposed algorithm is comparable to or outperforms the existing multiple clustering methods.</div></span>
   </li>

   <li>
   <span class="paper-title"><strong>Progressive Random k-Labelsets for Cost-Sensitive Multi-Label Classification</strong> - Hsuan-Tien Lin, Yu-Ping Wu <span class="paper-abstract-link">[abstract]</span>
   <div class="paper-abstract">In multi-label classification, an instance is associated with multiple relevant labels, and the goal is to predict these labels simultaneously. Many real-world applications of multi-label classification come with different performance evaluation criteria. It is thus important to design general multi-label classification methods that can flexibly take different criteria into account. Such methods tackle the problem of cost-sensitive multi-label classification (CSMLC). Most existing CSMLC methods either suffer from high computational complexity or focus on only certain specific criteria. In this work, we propose a novel CSMLC method, named progressive random $k$-labelsets (PRA$k$EL), to resolve the two issues above. The method is extended from a popular multi-label classification method, random $k$-labelsets, and hence inherits its efficiency. Furthermore, the proposed method can handle arbitrary example-based evaluation criteria by progressively transforming the CSMLC problem into a series of cost-sensitive multi-class classification problems. Experimental results demonstrate that PRA$k$EL is competitive with existing methods under the specific criteria they can optimize, and is superior under several popular criteria.</div></span>
   </li>

   </ul>

