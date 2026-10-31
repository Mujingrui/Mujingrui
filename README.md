## Hi there 👋

## Jingrui (Murphy) Mu

Statistician / Machine Learning Researcher / Quantitative Researcher / Federated AI agents — PhD candidate in Statistics at McGill 

I build statistical learning methods at the intersection of federated learning, Heterogeneous Data Integration and high-dimensional regression. 

At McGill I am supervised by Prof. Abbas Khalili  and Prof. David Stephens, working on federated
multi-task regression with variable selection and Heterogeneous Data Integration. Before McGill I completed my MSc in Statistics at the University of Ottawa under
Prof. Mayer Alvo, building Bayesian spatio-temporal models of COVID-19 transmission across Ontario.

**R · Python · C++ (OpenMP) · SQL**

### Research Projects

- **[Heterogeneous Federated High-dimensional Regression: Covariate Shift]**
  - Hospitals, banks, and other organizations often want to build better predictive models together, but can’t pool their raw data, and their populations differ. Standard federated methods average each site’s model, which introduces bias when sites look different from one another. We developed methods that correct for this, producing accurate site-specific predictions and identifying which of many candidate variables actually matter, while individual-level data never leaves each site.
  - How it works: A personalized federated approach that models site-level differences, with sparse regression for variable selection in high dimensions. Customed optimization solver written from scratch in C++, parallelized with OpenMP. 

- **[Personalized Sparse Federated Learning: Shared Signals, Site-Specific Models Learn across sites. Preserve local differences. Keep data local.]**
  - Hospitals, labs, and devices can learn more together than alone, but the predictors that matter and how strongly they matter often differ by site. One global model hides those differences. Fully separate models waste shared signal. This project builds sparse federated regression methods that learn what is shared, flag what is site-specific, and keep raw data where it is.
  - Personalized by design: each site can have its own selected predictors and effect sizes. 
  - Interpretable and auditable: compact models that show which relationships are shared and which are local, which is useful for regulated settings. 
  - Communication-efficient: sparsity reduces what must be exchanged between sites. 
  - Judged by the worst site, not just the average: we report accuracy, signal recovery, and communication cost, including how the least-advantaged site fares.

- **[Code from my doctoral research will be released with the manuscript. In the meantime:]**

### Selected repositories

Code from my doctoral research will be released with the manuscript. In the meantime:

- **[Federated-Evidence-Lab](https://github.com/Mujingrui/Federated-Evidence-Lab)** —
  privacy-preserving evidence integration across independent sites, exchanging only aggregate
  statistics.
- **[viprs-x](https://github.com/Mujingrui/viprs-x)** — variational EM for Bayesian polygenic
  risk scores, written from scratch in R and extended to joint estimation across ancestries.
- **[shap-simulation-study](https://github.com/Mujingrui/shap-simulation-study)** — do SHAP
  values explain the data or the model? Checked against exact conditional SHAP computed from
  the Shapley definition.
- **[doubly-robust-estimation](https://github.com/Mujingrui/doubly-robust-estimation)** —
  replication of Kang & Schafer (2007): what happens to doubly robust estimators when both
  nuisance models are wrong.

📍 Montreal, Toronto · [LinkedIn](https://www.linkedin.com/in/jingrui-mu)
· mujingrui.uibe@gmail.com


