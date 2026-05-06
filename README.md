# Technical Appendix

**Title:** Top-$k$ Sparsification for Enhancing Privacy-Utility Tradeoff in AirComp Federated Learning

## Overview
This repository contains the supplementary mathematical proofs and detailed convergence analysis for our submitted IEEE conference paper. Due to strict page limits in the main text, we provide the complete theoretical framework here.

The attached PDF document presents a rigorous, self-contained mathematical analysis of the proposed "sparsification-then-clipping" mechanism. 

## Core Theoretical Contributions Included

* **Error Feedback Contraction:** A tight bound on the error memory sequence, proving that the accumulation of unsent Top-$k$ residuals is strictly controlled by the local gradient updates (Lemma 1 & 2).
* **Virtual Model Separation:** The exact algebraic construction of the virtual global model sequence, smoothly decoupling the sparsification error from the physical transmission noise.
* **Bounded Local Divergence:** The derivation of the physical local model drift under data heterogeneity and stochastic gradient variance (Lemma 3).
* **Main Convergence Bound (Theorem 2):** The complete unrolling of the recursive descent inequality, establishing the final $\mathcal{O}(1/T)$ convergence rate while explicitly capturing the interplay between the privacy-induced power scaling, Top-$k$ sparsification ratio, and channel noise.

## File Structure
* `proof of Theorem 2.pdf`: The complete Technical Appendix document.

---
If you have any questions, please feel free to contact us via email at dliu@buaa.edu.cn or songjinning@buaa.edu.cn.
