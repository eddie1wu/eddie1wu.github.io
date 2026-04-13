---
layout: homepage
---

## About Me

I am a PhD candidate at Brown University with interest in econometrics and machine learning. I am deeply passionate about solving complex real-world problems with an engineering mindset -- improving algorithms, optimizing processes and uncovering hidden facts in data.

Before joining Brown, I completed my Bachelor's degree at the University of Cambridge and my Master's degree at Imperial College London.

## Research Interests

-   **Causal Inference:** high dimensional data, noisy environments, feature importance, scalability to big data.
-   **Prediction:** time series, finance and macroeconomic forecasting.
-   **Reinforcement Learning:** multi-armed bandit, contextual bandit, deep RL.

## Working Paper

-   **Policy Learning in High Dimensional Settings**

    <details>

    <summary>Abstract</summary>

    This paper studies policy learning in high-dimensional settings and documents a "double ascent" phenomenon in welfare, analogous to the double descent phenomenon in machine learning. Leveraging the equivalence between additive welfare maximization and weighted classification risk minimization, we analyze the performance of linear treatment assignment rules estimated via gradient descent as model complexity increases. We show via simulations that out-of-sample welfare is non-monotonic in model complexity, with a decline near the interpolation threshold followed by improvement in the overparameterized regime, demonstrating that more complex policies can potentially outperform parsimonious ones. Then, we derive weighted versions of the Vapnik–Chervonenkis generalization bound and margin-based linear model generalization bound tailored to policy learning. These results provide a general perspective for understanding how overparameterization can lead to welfare gains in high dimensional settings. Further simulations examine the robustness of the double ascent phenomenon under model misspecification and when using sieve estimators. Our findings suggest that overparameterization can be beneficial for welfare, particularly when rich covariate information is available, highlighting the potential value of flexible, high-dimensional policy rules.

    </details>

    [**Code**](https://github.com/eddie1wu/highDimPolicy) \| [**Draft**](assets/files/high_dim_policy.pdf) \| [**Slides**](assets/files/high_dim_policy_slides.pdf)

-   **Limitations and Opportunities of Bandit Algorithms for Feature Selection**

    <details>

    <summary>Abstract</summary>

    Feature selection is an important problem in statistical learning. This paper studies the performance of bandit-based feature selection and compares it with stability selection. Theories and simulation results show that bandit selection does not generally outperform stability selection for signal recovery and may suffer from high false positive rates, particularly in settings with correlated features or omitted variables. Nevertheless, bandit methods enjoy advantages in high-dimensional settings by allocating computational effort to promising regions of feature space and by adaptively handling combinatorial subset selection when exhaustive search is infeasible. We then discuss the strong identifiability condition under which bandit-based methods consistently select the set of true features, and propose a top-two Thompson sampling variant designed for pure exploration settings. Finally, we apply our method to the empirical asset pricing study of Gu et al (2020) and obtain similar conclusions regarding signal importance.

    </details>

    [**Code**](https://github.com/eddie1wu/bandit_selection) \| [**Draft**](assets/files/bandit_selection.pdf) \| [**Slides**](assets/files/bandit_selection_slides.pdf)

-   **Using Synthetic Control to Study the Economic Impact of the Brexit Referendum**

    <details>

    <summary>Abstract</summary>

    This research uses synthetic control methods, including the augmented synthetic control and the synthetic difference-in-differences, to evaluate the impacts of the Brexit referendum on the real GDP per capita and real gross disposable income per capita in the UK. I examine the short and medium term impacts till 2023Q3, and estimate that the Brexit referendum has caused a persistent drop in real GDP since 2016Q3, which accumulates to a 10% gap by 2023Q3. The same goes for real per capita gross disposable income, which amounts to a 16-22% gap by 2023Q3. By comparing the different methods, I find that the original synthetic control estimates are greater than those of the augmented synthetic control in magnitudes, although the assumptions for the original synthetic control are largely satisfied and there is no need to extrapolate beyond the convex hull of the control countries.

    </details>

    [**Code**](https://github.com/eddie1wu/applied_synthetic_control) \| [**Draft**](assets/files/applied_sc_paper.pdf) \| [**Slides**](assets/files/applied_sc_slides.pdf)

## Work-in-progress

-   **Augmenting Economic Data Using Variational Autoencoder**

    <details>

    <summary>Abstract</summary>

    Economic data often suffers from being limited or insufficient, making robust inference and prediction challenging. This research explores the usage of variational autoencoders (VAE) to generate synthetic tabular economic data that closely mirrors the true data distribution. Building on the work of Athey, Imbens, Metzger, and Munro (2021), who use Wasserstein GANs to simulate data from the classic Lalonde datasets, which are widely employed to evaluate causal inference methods, this research applies VAE to the same datasets to demonstrate its capability in simulating tabular data. Beyond cross-sectional data, this study aims to develop VAEs to generate sequential data such as time series. The ultimate goal is to create a systemic way of augmenting economic datasets to enhance the performances of causal inference methods and forecasting models.

    </details>

    [**Code**](https://github.com/eddie1wu/econ_VAE)

## Experiences

-   **[Jul-Sep, 2025]** <ins>Amazon researcher intern</ins>: signal research, revenue forecasting.
-   **[May-Jul, 2025]** <ins>Cubist Systematic quantitative researcher intern</ins>: alpha research, data computation, return forecasting.
-   **[Jun-Aug, 2024]** <ins>Brown University research assistant</ins> for Prof. Soonwoo Kwon and Prof. Jon Roth: wrote R package for inferring causal mechanisms, and constructed confidence intervals for high-dimensional linear regression.
-   **[Jun-Aug, 2023]** <ins>Brown University research assistant</ins> for Prof. Andriy Norets: implemented Bayesian conditional mixture model with variable number of components in Stan.
-   **[Sep 2021 - Apr 2022]** <ins>Institute for Fiscal Studies research assistant</ins> for Prof. Eric French: estimated structural models in MATLAB using simulated method of moments to study the economic dynamics of aging.
-   **[Sep 2021 - Feb 2022]** <ins>University of Cambridge research assistant</ins> for Prof. Kai Liu and Prof. Noriko Amano-Patino: conducted event studies on census data and used NLP methods to link and preprocess large datasets.
-   **[Jun-Aug, 2019]** <ins>J.P. Morgan London summer intern</ins> in global markets: exposure to hedging, pricing and risk management of equities, FX and rates derivatives.

## Teaching at Brown University

-   **[Fall 2024, Spring 2025] Lecturer for ECON0170:** Essential Mathematics for Economics.
-   **[Spring 2024] TA for ECON2020:** Applied Economic Analysis (R coding).
-   **[Fall 2023] TA for ECON1630:** Mathematical Econometrics.
