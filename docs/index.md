---
layout: homepage
---

## About Me

I am a PhD candidate at Brown University with interest in econometrics and machine learning. I am deeply passionate about solving complex real-world problems with an engineering mindset -- improving algorithms, optimizing processes and uncovering hidden facts in data to enable a better understanding of the world around us.

Before joining Brown, I completed my Bachelor's degree at the University of Cambridge and my Master's degree at Imperial College London.


## Research Interests

-   **Causal Inference:** high dimensional data, noisy environments, scalability to big data.
-   **Prediction:** time series, finance and macroeconomic forecasting.
-   **Reinforcement Learning:** multi-armed bandit, contextual bandit, deep RL.


## Work-In-Progress

-   **Best Arm Identification for Variable Selection:**
    <details>
      <summary>Abstract</summary>
      This research explores variable selection in a high-dimensional setting through an application of best-arm identification algorithms. Building on the framework of Rockova & Liu 2021, this research demonstrates how combinatorial bandits can be welded to algorithms such as LASSO and random forest to improve the accuracy of variable selection compared to running such algorithms directly on high-dimensional data. This research also augments the existing Thompson variable selection framework by integrating top-two Thompson sampling and bootstrap aggregation, which are shown to yield robust results and improve on accuracy and variance of variable selection in numerical experiments. Future work aims to explore the theoretical reasons to why these algorithms work and prove properties such as regret bound and consistency.
    </details>
    **[Code](https://github.com/eddie1wu/best_arm_bandit)** | **[Slides](assets/files/BAI_variable_selection.pdf)**
    
-   **Augmenting Economic Data Using Variational Autoencoder:**
    <details>
      <summary>Abstract</summary>
      Economic data often suffers from being limited or insufficient, making robust inference and prediction challenging. This research explores the usage of variational autoencoders (VAEs) to generate synthetic tabular economic data that closely mirrors the true data distribution. Building on the work of Athey, Imbens, Metzger, and Munro (2021), who use Wasserstein GANs to simulate data from the classic Lalonde datasets, which are widely employed to evaluate causal inference methods, this research applies VAE to the same datasets to demonstrate its capability in simulating tabular data. Beyond cross-sectional data, this study aims to develop VAEs to generate sequential data such as time series. The ultimate goal is to create a systemic way of augmenting economic datasets to enhance the performances of causal inference methods and forecasting models.
    </details>
    **[Code](https://github.com/eddie1wu/econ_VAE)**
    
-   **Using Synthetic Control to Study the Economic Impact of the Brexit Referendum:**
    <details>
      <summary>Abstract</summary>
      This research uses synthetic control methods, including the augmented synthetic control and the synthetic difference-in-differences, to evaluate the impacts of the Brexit referendum on the real GDP per capita and real gross disposable income per capita in the UK. I examine the short and medium term impacts till 2023Q3, and estimate that the Brexit referendum has caused a persistent drop in real GDP since 2016Q3, which accumulates to a 10% gap by 2023Q3. The same goes for real per capita gross disposable income, which amounts to a 16-22% gap by 2023Q3. By comparing the different methods, I find that the original synthetic control estimates are greater than those of the augmented synthetic control in magnitudes, although the assumptions for the original synthetic control are largely satisfied and there is no need to extrapolate beyond the convex hull of the control countries.
    </details>
    **[Code](https://github.com/eddie1wu/applied_synthetic_control)** | **[Draft](assets/files/applied_sc_paper.pdf)** | **[Slides](assets/files/applied_sc_slides.pdf)**


## Experiences

-   **[Jun-Aug, 2024]** <ins>Brown University research assistant</ins> for Prof. Soonwoo Kwon and Prof. Jon Roth: wrote R package for inferring causal mechanisms, and constructed confidence intervals for high-dimensional linear regression.
-   **[Jun-Aug, 2023]** <ins>Brown University research assistant</ins> for Prof. Andriy Norets: implemented Bayesian conditional mixture model with variable number of components in Stan.
-   **[Sep 2021 - Apr 2022]** <ins>Institute for Fiscal Studies research assistant</ins> for Prof. Eric French: estimated structural models in MATLAB using simulated method of moments to study the economic dynamics of aging.
-   **[Sep 2021 - Feb 2022]** <ins>University of Cambridge research assistant</ins> for Prof. Kai Liu and Prof. Noriko Amano-Patino: conducted event studies on census data and used NLP methods to link and preprocess massive datasets.
-   **[Jun-Aug, 2019]** <ins>J.P. Morgan London summer intern</ins> in global markets: exposure to hedging, pricing and risk management of equities, FX and rates derivatives.


## Teaching

-   **Current lecturer for ECON0170:** Essential Mathematics for Economic Analysis.
-   **TA for ECON2020:** Applied Economic Analysis (R coding).
-   **TA for ECON1630:** Mathematical Econometrics.
