---
title: "Research"
date: 2026-01-01
ShowToc: false
TocOpen: false
weight: 2
---


My research is in Mathematical Finance, with a focus on pricing catastrophe (CAT) bonds under sudden, extreme market shocks using jump-diffusion models

## Current Projects

### Jump-Diffusion CAT Bond Pricing
Extended the diffusion-only CAT bond model by adding jump-diffusion dynamics to the spot exchange rate and the domestic and foreign interest rates. This yields closed-form and semi-analytical pricing formulas for zero-coupon bonds and FX call options that account for market jumps, which standard diffusion-only models miss. Validated against large-scale Monte Carlo simulation and performed parameter sensitivity analysis across jump intensity, jump size, volatility, and mean-reversion speed.

### Multi-Currency Extension
Extended the model to a multi-currency setting, covering four currency pairs (USD/EUR, USD/INR, USD/BRL, USD/JPY) chosen to span stable and volatile exchange rate regimes. The pairs span stable developed-market and volatile, jump-prone emerging-market regimes. I calibrate each pair separately on monthly data from January 2015 to January 2025 (121 observations) and compare the derived CAT bond price with a Monte Carlo simulation using 500,000 paths and 150 time steps. The proposed model tracks the simulation closely in all four pairs, with the largest deviation for USD/INR, where jumps dominate the variance approximation.

### Correlated Jump Extension of above CAT Bond Pricing Model (In progress)
This project extends the jump-diffusion CAT bond model by allowing jumps to be correlated. The exchange rate, the domestic interest rate, and the foreign interest rate share one common jump shock. Each pair of these rates also has its own common shock, on top of idiosyncratic (unique) jumps in each rate. This lets the model capture joint market moves that independent jumps cannot. My goals are to derive a CAT bond price under this model, then check it numerically against an independent pricing method.

### Multi-Label Emotion Classification with LLMs 
Built and compared multiple approaches for multi-label emotion classification (28 emotion categories), including fine-tuned DistilBERT and BERT models and embedding-based pipelines (Logistic Regression, SVM, Random Forest, KNN). Applied hyperparameter tuning with Optuna and class-imbalance handling via oversampling and per-class threshold tuning.


## Publications
- Ridhima Nehra and I. SenGupta (2026), "The catastrophe bond price under the jump diffusion model: a multi-currency comparison", (2026), _Stats_, **9**(5), 112. [Read the article here](https://doi.org/10.3390/stats9050112)
- (Submitted) Ridhima Nehra and I. SenGupta (2026), “The valuation of catastrophe bonds under domestic and foreign interest rates with jumps”, 2026. doi: 
- (Working Paper) Ridhima Nehra and L. Liu (2026), "Emotion Detection in Text Using Large Language Models for Enhanced Mental Health Support". 
- Sushma Dave, Pratik Jagtap, Sanjana Verma, \textbf{R. Nehra}, et al. (2021), “Mathematical Modeling and Surface Response Curves for Green Synthesized Nanomaterials and Their Application in Dye Degradation.” Book Chapter in Photocatalytic Degradation of Dyes, Elsevier, 2021. [Read the article here](https://doi.org/10.1016/B978-0-12-823876-9.00027-5)
- Ridhima Nehra, Rojin Joseph, and Aparna Vyas. “Comparison of Image Denoising Using Wavelet Transform and Wavelet Packet Transform.” International Conference Proceedings, Tokyo Summit II, 2020. 

## Presentations
- (Upcoming) "Joint Mathematics Meetings 2027'', Chicago, January 12-15, 2027.  
- "American Mathematical Society (AMS) 2026 Fall Western Sectional Meeting", Special Session on Stochastic Analysis and Applications, Arizona State University, Tempe, AZ, November 7-8, 2026.
- "AMS Spring Southeastern Sectional Meeting", Special Session on Mathematical Finance and Risk Management, Georgia Southern University-Armstrong Campus, Savannah, GA, March 28-29, 2026.
- "2nd International Conference on Innovative Studies of Contemporary Sciences”, Tokyo, Japan, August 17-19, 2020.
- “Green and Sustainable Chemistry Conference GSCC”, Manav Rachna University, India, November 7-8, 2019.
---
- "Graduate Colloqium", Department of Mathematics, NDSU, October 29, 2026.
- “Analysis, Applied Math & Geometry” Department Seminar, NDSU, March 24, 2026.
- “Graduate Research Days”, NDSU, April 09, 2026. 

## Research Interests

Financial Mathematics, Jump-Diffusion Models, Stochastic Processes, Monte Carlo Simulation, Differential Equations, Time Series Forecasting, Machine Learning, Large Language Model Fine-Tuning, Wavelets, Mathematical Modeling.

<!--## Collaborators --!>
<!-- - *Update with collaborator information* --!>


<br>

<p><em>Research page is continuously updated as projects progress.</em></p>
