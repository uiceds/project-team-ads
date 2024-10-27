---
title: Machine Learning-Based Optimization Of The Mix Design Of Lightweight Concrete For Enhanced Mechanical Properties
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2024-10-27'
author-meta:
- Ayyan Iqbal
- Shayan Khan
- Dhatrika Varma Borukati
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Machine Learning-Based Optimization Of The Mix Design Of Lightweight Concrete For Enhanced Mechanical Properties" />
  <meta name="citation_title" content="Machine Learning-Based Optimization Of The Mix Design Of Lightweight Concrete For Enhanced Mechanical Properties" />
  <meta property="og:title" content="Machine Learning-Based Optimization Of The Mix Design Of Lightweight Concrete For Enhanced Mechanical Properties" />
  <meta property="twitter:title" content="Machine Learning-Based Optimization Of The Mix Design Of Lightweight Concrete For Enhanced Mechanical Properties" />
  <meta name="dc.date" content="2024-10-27" />
  <meta name="citation_publication_date" content="2024-10-27" />
  <meta property="article:published_time" content="2024-10-27" />
  <meta name="dc.modified" content="2024-10-27T02:55:40+00:00" />
  <meta property="article:modified_time" content="2024-10-27T02:55:40+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Ayyan Iqbal" />
  <meta name="citation_author_institution" content="University of Illinois" />
  <meta name="citation_author" content="Shayan Khan" />
  <meta name="citation_author_institution" content="University of Illinois" />
  <meta name="citation_author" content="Dhatrika Varma Borukati" />
  <meta name="citation_author_institution" content="University of Illinois" />
  <link rel="canonical" href="https://uiceds.github.io/project-team-ads/" />
  <meta property="og:url" content="https://uiceds.github.io/project-team-ads/" />
  <meta property="twitter:url" content="https://uiceds.github.io/project-team-ads/" />
  <meta name="citation_fulltext_html_url" content="https://uiceds.github.io/project-team-ads/" />
  <meta name="citation_pdf_url" content="https://uiceds.github.io/project-team-ads/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://uiceds.github.io/project-team-ads/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://uiceds.github.io/project-team-ads/v/82c9451c570edc811da9c00661f63ef4bcb49495/" />
  <meta name="manubot_html_url_versioned" content="https://uiceds.github.io/project-team-ads/v/82c9451c570edc811da9c00661f63ef4bcb49495/" />
  <meta name="manubot_pdf_url_versioned" content="https://uiceds.github.io/project-team-ads/v/82c9451c570edc811da9c00661f63ef4bcb49495/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...

## Authors



+ **Ayyan Iqbal**
  <br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [maiqbal2](https://github.com/maiqbal2)
    <br>
  <small>
     University of Illinois
  </small>

+ **Shayan Khan**
  <br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [shayank491](https://github.com/shayank491)
    <br>
  <small>
     University of Illinois
  </small>

+ **Dhatrika Varma Borukati**
  <br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [DeeVarma24](https://github.com/DeeVarma24)
    <br>
  <small>
     University of Illinois
  </small>



## 1. Project Proposal {.page_break_before}

<p align="justify">
The escalating global population drives the increasing demand for concrete, thereby fostering the development and adoption of Lightweight Aggregate (LWA)-based Lightweight Concrete (LWC). The widespread availability of LWAs, coupled with straightforward and conventional casting techniques, has facilitated industry-wide acceptance [@doi:10.3390/su15010641]. LWC has found extensive applications in lightweight infill panels, structural concrete, and precast concrete. Notably, LWC achieves comparable compressive strength to traditional concrete in specific scenarios, albeit with a 25-35% reduction in density [@doi:10.3390/app11020800]. This reduction yields additional benefits, including minimized foundation steel requirements, lower transportation costs, and decreased construction expenditures, rendering LWC a promising solution for sustainable and cost-effective infrastructure development.
A significant obstacle in the widespread adoption of Lightweight Concrete (LWC) lies in its intricate mix design process. Unlike Normal-Weight Concrete (NWC), which relies on established codes and iterative fine-tuning, LWC lacks standardized design guidelines. Furthermore, optimizing LWC's density while maintaining compressive and tensile strength poses a substantial challenge due to its sensitive nature, where minor mix design adjustments drastically impact mechanical properties. The complexity is compounded by the varied shapes, sizes, and densities of LWAs, which significantly influence the mix design. In contrast, NWC aggregates exhibit relatively consistent properties.
To address this challenge, a machine learning (ML) framework can be employed to predict LWA concrete's mechanical properties, including compressive strength, tensile strength, and density. The development of user-friendly tools, leveraging these ML models, would facilitate iterative design optimization and trial-and-error experimentation for researchers working on specialized LWC mix designs.
This predictive tool would not only streamline LWC mix design hence enhancing accuracy in mechanical property prediction but expedite the development of tailored LWC solutions for specific applications. By integrating ML and materials science, this innovative approach would overcome existing design complexities and unlock LWC's full potential.
For the CEE-492 semester project, our team objectives are to develop and compare the performance of Artificial Neural Networks (ANN), Gaussian Process Regression (GPR), and Decision Trees in predicting the mechanical properties of Lightweight Concrete (LWC), specifically density, compressive strength, and tensile strength. Initially, relevant data from published online articles would be collected, followed by data preprocessing to ensure consistency and quality. Next, we identify 10 influential input parameters governing LWC mix design through a comprehensive literature review of the latest published review articles. An exploratory data analysis (EDA) is then conducted to uncover trends and relationships within the data. Subsequently, the preprocessed data is divided into training (~70-80%) and testing sets (~20-30%). The training data is then normalized and scaled to optimize model performance.
Then the team aims to train the ANN, GPR, and Decision Tree models on the training data, fine-tuning hyperparameters through cross-validation and grid search. Model evaluation is performed on the testing data using the statistical performance indicators i.e., such as mean squared error (MSE), R-squared (R²), and mean absolute error (MAE). Finally, we compare the performance of the trained models and select the best-performing algorithm. The formulas for the performance metrics are mentioned below in [Table 1](#Table 1).
</p>

<p align="center" id="Table 1"><strong>Table 1. Mathematical formulation of the statistical performance indicators used in the report.</strong></p>

| Equations |
|:-----------------:|
| $$RMSE = \sqrt{\frac{1}{m} \sum_{i=1}^{m} \left( k_{act} - k_{pre} \right)^2}$$ |
| $$R^2 = 1 - \frac{\sum \left( k_{act} - k_{pre} \right)^2}{\sum \left( k_{act} - \bar{k_{pre}} \right)^2}$$ |
| $$MAE = \frac{1}{m} \sum_{i=1}^{m} \left\| k_{act} - k_{pre} \right\|$$ |
| $$MSE = \frac{1}{m} \sum_{i=1}^{m} \left( k_{act} - k_{pre} \right)^2$$ |
| $$VAF = \left( 1 - \frac{\text{var}(k_{act} - k_{pre})^2}{\text{var}(k_{act})} \right) \times 100$$ |

<p align="justify">
A longstanding controversy surrounds the efficacy and reliability of Machine Learning (ML) and Artificial Intelligence (AI)--based models, with critics labeling them as "black boxes" that merely identify patterns without providing meaningful insights. To address concerns regarding overfitting and model interpretability, we aim to explain or results by employing local explanation techniques, specifically Partial Dependence Plots (PDP) and Shapley Additive Explanations (SHAP). These methods decipher the relationships between individual input parameters and the model's output, demystifying the "black box" nature of ML models, validating their reliability and accuracy, and identifying potential biases.
</p>

### 1.1. Dataset description

<p align="justify">
The data set attached has been collected by the team members from all the scholarly articles from Scopus. The search query used for finding articles was “{Lightweight} AND {concrete} AND {aggregate} AND {strength} AND {density} AND {ML}”. The authors have collected 500 data points from over 50 articles. The data set has the quantities of Cement, sand, fly ash (FA), the density of lightweight aggregate, water absorption of lightweight aggregate, superplasticizer, curing time, and the amount of normal aggregate (normal agg.), as input parameters while the compressive strength, split tensile strength, and density of the concrete were taken as output parameters. The first test columns of the dataset correspond to inputs while the last three correspond to output. All the quantities were normalized by the cement quantity before the start of the analysis. The input and output parameters along with their units have been mentioned below in [Table 2](#Table 2) as well.
</p>

<p align="center" id="Table 2"><strong>Table 2. Input and output parameters of the dataset along with their units.</strong></p>

| Parameters                               | Categories (I/O) |
|:----------------------------------------:|:-----------------:|
| Cement (kg/m³)                           | I                |
| Fine agg. (kg/m³)                        | I                |
| w/b                                      | I                |
| LW agg. (kg/m³)                          | I                |
| LW agg. density (kg/m³)                  | I                |
| LW agg. water absorption (%)             | I                |
| NW agg. (kg/m³)                          | I                |
| HRWR (% of binder)                       | I                |
| Curing Time (days)                       | I                |
| Fly Ash (kg/m³)                          | I                |
| Compressive Strength of LW concrete (MPa)| O                |
| Split Tensile Strength of LW concrete (MPa) | O             |
| Density of LW concrete (kg/m³)           | O                |


<p align="justify">
* I = Input
* O = Output
* LW = Lightweight
* NW = Normal weight
* w/b = water to binder ratio
* HRWR = High range water reducer
</p>

## 2. Statistical distribution of dataset {.page_break_before}

<p align="justify">
Concrete is widely regarded as the most complex composite material, comprising various ingredients and exhibiting diverse properties that make its behavior challenging to predict. Its composition can vary significantly depending on application, environmental conditions, and performance requirements. [Figure 1](fig:Fig.1) illustrates the statistical distribution of input parameters for concrete compositions, revealing diverse applications and formulations contributing to complex datasets. Certain parameters, such as water-to-cement (W/C) ratio (0.35-0.5), superplasticizer content (typically ≤1% of binder weight), water absorption of aggregates (∼2% of aggregate weight), and curing time (predominantly 28 days), exhibit narrow interquartile ranges, indicating relatively fixed proportions in typical cement-based mixtures [@doi:10.1680/macr.2005.57.8.445; @lee2003; @goldman1993; @lai1997]. In contrast, lightweight aggregate types and corresponding variations in concrete compositions display larger interquartile ranges, reflecting the broad range of available materials, underscoring the complexity of concrete's widespread use as the world's most utilized composite material [@vilarinho2009researchgate].
</p>

<div style="text-align: center;">
  <img src="https://github.com/uiceds/project-team-ads/blob/main/content/images/Picture1.png?raw=true" id="fig:Fig.1" style="width: 75%;"/>
  <p><strong>Figure 1: Statistical distribution of the input parameters of the dataset compiled from articles.</strong></p>
</div>

<p align="justify">
The authors have comprehensively compiled a dataset encompassing a wide range of lightweight aggregates from existing literature. These aggregates, derived from industrial waste materials or naturally occurring sources, exhibit spatial variability due to regional differences in availability. Consequently, a diverse array of lightweight aggregates is utilized globally. [Figure 2](fig:Fig.2) illustrates the various types of aggregates incorporated in this study. Notably, the dataset reveals that clay-based Lightweight Expanded Clay Aggregate (LECA) predominates, reflecting clay's abundance as a raw material for artificial aggregate production [@doi:10.1016/j.surfin.2020.100705]. Furthermore, polystyrene, a prevalent waste material, emerges as a primary source of artificial lightweight aggregates in the dataset [@doi:10.1016/j.procs.2020.05.145].
</p>

<div style="text-align: center;">
  <img src="https://github.com/uiceds/project-team-ads/blob/main/content/images/Picture2.png?raw=true" id="fig:Fig.2" style="width: 75%;"/>
  <p><strong>Figure 2: Types of lightweight aggregates used by researchers in the article from which data has been obtained.</strong></p>
</div>

<p align="justify">
[Figure 3](fig:Fig.3) illustrates the statistical distribution of compressive strength, tensile strength, and concrete density. The results show that the mean tensile strength is approximately one-tenth of the mean compressive strength (∼30 MPa), aligning with established conventions (e.g., ACI codes) [@en13055-1-2016]. The average density of 1700 kg/m³ reflects the prevalence of expanded clay aggregate and polystyrene-based concretes since their density lies in this range, validating the dataset's accuracy and reliability for further analysis [@doi:10.1016/j.jclepro.2015.07.001; @sivakumar2015flyash].
</p>

<div style="text-align: center;">
  <img src="https://github.com/uiceds/project-team-ads/blob/main/content/images/Picture3.png?raw=true" id="fig:Fig.3" style="width: 75%;"/>
  <p><strong>Figure 3: Statistical distributions of the output parameters of the dataset compiled from articles.</strong></p>
</div>

### 2.1. Dataset cleaning and splitting

<p align="justify">
To maintain accuracy, completeness, consistency, relevance, and validity, the dataset underwent a rigorous cleaning process, a crucial step before applying any machine learning algorithm. This process ensures that the data is processable and enables effective learning for accurate output. Given that the dataset was compiled from X diverse articles sourced from online libraries, there was a high likelihood of human error. However, since most of the dataset was collected by our team, missing values were nonexistent, eliminating the need for removal or imputation. Data cleaning addressed potential issues such as data entry errors, equipment malfunctions, or incomplete surveys. Outliers were identified, and upon examination, most were found to originate from articles published by sources with questionable academic reputations [@doi:10.1016/j.bsecv.2021.11.003; @doi:10.3390/ma15113929; @doi:10.3390/ma11122434; @zach2009; @doi:10.1016/j.matdes.2013.12.013; @doi:10.3390/buildings12010060; @doi:10.3390/ma12020267]. These outliers were subsequently trimmed to prevent biased analysis and ensure data integrity.
Following data cleaning, the refined dataset was split into training (80%) and testing sets (20%). Summary statistics for both are presented in [Table 3](#Table 3) and [Table 4](#Table 4), providing a comprehensive foundation for reliable model development and evaluation.
</p>

<p align="center" id="Table 4"><strong>Table 3. Summary statistics of dataset set aside for ML model training.</strong></p>

| Parameters                               | Minimum | Maximum | Median | Mode | SD      | Type |
|:----------------------------------------:|:-------:|:-------:|:------:|:----:|:-------:|:----:|
| Cement (kg/m³)                           | 156     | 1500    | 467    | 480  | 378.42  | I    |
| Fine agg. (kg/m³)                        | 0       | 1193    | 664    | 0    | 330.15  | I    |
| w/b                                      | 0.15    | 0.80    | 0.45   | 0.5  | 0.08    | I    |
| LW agg. (kg/m³)                          | 23.80   | 1191    | 308    | 37   | 297.28  | I    |
| LW agg. density (kg/m³)                  | 415     | 1489    | 783    | 575  | 357.65  | I    |
| LW agg. water absorption (%)             | 0.92    | 58.30   | 25.20  | 40   | 13.83   | I    |
| NW agg. (kg/m³)                          | 0       | 1326    | 0      | 0    | 353.98  | I    |
| HRWR (% of binder)                       | 0       | 3       | 0      | 0    | 0.70    | I    |
| Curing Time (days)                       | 1       | 120     | 28     | 28   | 14.27   | I    |
| Fly Ash (kg/m³)                          | 0       | 540     | 0      | 0    | 117.61  | I    |
| Compressive Strength of LW concrete (MPa)| 2.03    | 79      | 24.58  | 25   | 16.68   | O    |
| Split Tensile Strength of LW concrete (MPa) | 1   | 7       | 3.5    | 3    | 2       | O    |
| Density of LW concrete (kg/m³)           | 900     | 2500    | 1855   | 1800 | 366     | O    |

<p align="center" id="Table 4"><strong>Table 4. Summary statistics of dataset set aside for ML model testing.</strong></p>

| Parameters                               | Minimum | Maximum | Median | Mode | SD      | Type |
|:----------------------------------------:|:-------:|:-------:|:------:|:----:|:-------:|:----:|
| Cement (kg/m³)                           | 139     | 1350    | 384    | 450  | 197.70  | I    |
| Fine agg. (kg/m³)                        | 0       | 1178    | 630    | 0    | 294.92  | I    |
| w/b                                      | 0.23    | 0.8     | 0.42   | 0.35 | 0.07    | I    |
| LW agg. (kg/m³)                          | 0       | 950     | 155    | 0    | 270.29  | I    |
| LW agg. density (kg/m³)                  | 406     | 1480    | 750    | 610  | 320.11  | I    |
| LW agg. water absorption (%)             | 0.92    | 56      | 20.5   | 20.5 | 13.54   | I    |
| NW agg. (kg/m³)                          | 0       | 941.2   | 0      | 0    | 282.15  | I    |
| HRWR (% of binder)                       | 0       | 2.5     | 0.5    | 0    | 0.687   | I    |
| Curing Time (days)                       | 1       | 120     | 28     | 28   | 23.4    | I    |
| Fly Ash (kg/m³)                          | 0       | 540     | 0      | 0    | 111.38  | I    |
| Compressive Strength of LW concrete (MPa)| 4.28    | 65.14   | 27     | 25   | 15.54   | O    |
| Split Tensile Strength of LW concrete (MPa) | 1.2  | 6.7     | 3.6    | 3.1  | 2.2     | O    |
| Density of LW concrete (kg/m³)           | 950     | 2670    | 1755   | 1650 | 354     | O    |


### 2.2. Dataset cleaning and splitting

<p align="justify">
Data normalization is a standardization technique for transforming variables to have a common scale. When working with data from different sources or formats, there can be variations in how it is represented, such as differences in units of measurement, data formats, and data structures, making it difficult to compare variables or perform statistical analysis. Data standardization is a crucial step in such cases. The major challenge faced after data collection is processing the raw data to make it compatible with the ML models used. For instance, there was a considerable difference in our dataset between the numerical values of cement, w/c, and normal aggregate used. This difference adversely affected the accuracy of our model. This issue was tackled using the data normalization technique. Data normalization means transforming data into the unit sphere or scaling down the actual values to numerical indexes between 0 and 1. It leads to data cleansing and convergence and significantly enhances the model's efficiency. It also improves data execution by reducing the data set's redundancy. The governing [Equation 1](#eq:Eq. 1) taken into consideration for data normalization is mentioned below, where the normalized value of a certain input variable is a function of the actual, minimum, and maximum values of that variable in the data set. The normalized dataset has been plotted in [Figure 4](fig:Fig.4) below
</p>


$$y = \frac{\sum_{i=1}^{n} \left( x_i - \bar{x} \right) \left( y_i - \bar{y} \right)}{\sqrt{\sum_{i=1}^{n} \left( x_i - \bar{x} \right)^2} \sqrt{\sum_{i=1}^{n} \left( y_i - \bar{y} \right)^2}}$$ {#eq:Eq. 1}

<div style="text-align: center;">
  <img src="https://github.com/uiceds/project-team-ads/blob/main/content/images/Picture4.png?raw=true" id="fig:Fig.4" style="width: 70%;"/>
  <p><strong>Figure 4: Statistical distribution of the parameters of the dataset compiled after standardization.</strong></p>
</div>

### 2.3. Correlation of input parameters with output parameters

<p align="justify">
The preprocessing phase proceeded with the plotting of Pearson correlation matrices [Figure 5](fig:Fig.5) to elucidate relationships between dependent and independent variables. This comprehensive graph displays pairwise correlations through Pearson correlation coefficients, ranging from -1 to +1. Diagonal entries show perfect correlation (1), while non-diagonal entries exhibit coefficients between -1 and +1, indicating varying degrees of correlation. In the graph template used for this article, blue the color shows the direction of the correlation, and the size of the circle shows magnitude/extent of correlation. Positive coefficients signify direct relationships, and negative coefficients indicate inverse relationships. This analysis, mathematically expressed through the Pearson correlation coefficient (r) [Equation 2](#eq:Eq. 2), provides valuable insights into variable interactions, informing the development of a robust ML model.
</p>

$$r = \frac{\sum (x_i - \bar{x})(y_i - \bar{y})}{\sqrt{\sum (x_i - \bar{x})^2 \sum (y_i - \bar{y})^2}}$$ {#eq:Eq. 2}

<p align="justify">
The correlation matrix of each input with a particular output has been shown separately for a deeper understanding. Keeping the number of input and output parameters in consideration in a single correlation matrix made the visualization difficult. From the correlation matrices, it is evident that the LWA density was the primary factor controlling compressive strength. As per S.A.Khan et al. [@doi:10.1155/2024/8263261], the difference between normal-weight concrete and lightweight concrete is that lightweight concrete fails due to the failure of aggregates, not matrix so failure concrete with increased lightweight aggregate density had increased compressive strengths as well. Also, an increase in the water-cement ratio causes a decrease in compressive strength, which can also be seen in the graph. Similarly the total fines content or total normal weight aggregate content has a good positive correlation with split tensile strength and concrete density which is also supported by the literature.
</p>

<div style="text-align: center;">
  <img src="https://github.com/uiceds/project-team-ads/blob/main/content/images/Picture5.png?raw=true" id="fig:Fig.5" style="width: 75%;"/>
  <p><strong>Figure 5: Pearson correlation matrices of input parameters with each output parameter.</strong></p>
</div>

<p align="justify">
Apart from the data cleaning standardization and visualization discussed above, the authors of the report did not require any data augmentation since the number of data points seemed enough for the types of models they intended to train. However, the authors might perform some feature engineering by combining some of the highly correlated input parameters if the statistical performance indicators do not meet their expectations upon training of the model hence changes will be made in the subsequent report
</p>

## 1. Methodology {.page_break_before}

<p align="justify">
This report aims to train, validate, and fine-tune Artificial Neural Networks (ANN), Gaussian Process Regression (GPR), and Decision Tree models on the training data for predicting concrete properties. The objectives are to leverage the unique strengths of each model, with ANN capturing non-linear relationships and patterns, Decision Trees providing interpretable results and feature selection, and GPR quantifying uncertainty and handling sparse data. By combining these models, the challenges in concrete property prediction, including non-linear relationships, variability, and limited data, can be effectively addressed.

Additionally, this report addresses the longstanding controversy surrounding the efficacy and reliability of Machine Learning (ML) and Artificial Intelligence (AI) based models, often labeled as "black boxes" that merely identify patterns without providing meaningful insights. To alleviate concerns regarding overfitting and model interpretability, local explanation techniques, specifically Partial Dependence Plots (PDP) and Shapley Additive Explanations (SHAP), will be employed to decipher the relationships between individual input parameters and the model's output. This approach ensures model interpretability, validity, reliability, and identification of potential biases, ultimately demonstrating the efficacy of ML models in concrete property prediction.
</p>

### 3.1. Artificial neural network

<p align="justify">
Artificial Neural Networks (ANNs) are complex computational models inspired by biological neural networks. They process input data, generate output, and adapt through backpropagation training. Proven effective in various domains, ANNs excel in classification, regression, forecasting, and clustering tasks. The implemented ANN model architecture has been depicted in [Figure 6](fig:Fig.6) below.
</p>

<div style="text-align: center;">
  <img src="https://github.com/uiceds/project-team-ads/blob/main/content/images/Picture6.png?raw=true" id="fig:Fig.6" style="width: 75%;"/>
  <p><strong>Figure 6: Model architecture of ANN.</strong></p>
</div>

### 3.2. Decision Tree 

<p align="justify">
Decision Trees, a supervised machine learning approach, effectively predicts concrete's mechanical characteristics by modeling complex relationships between input data and output labels.  The tree-like structure of Decision Trees provides transparency into prediction outcomes. As a valuable alternative to traditional methods, Decision Trees are a helpful tool for forecasting concrete's mechanical properties, as illustrated in [Figure 7](fig:Fig.7).
</p>

<div style="text-align: center;">
  <img src="https://github.com/uiceds/project-team-ads/blob/main/content/images/Picture7.png?raw=true" id="fig:Fig.7" style="width: 75%;"/>
  <p><strong>Figure 7: Working mechanism/flowchart of the Decision tree.</strong></p>
</div>

### 3.3. Gaussian Process of Regression

<p align="justify">
Gaussian Process Regression (GPR) is a supervised machine learning technique using Bayesian inference for predictions. As a non-parametric method [60, 61], GPR excels with limited data, modeling complex relationships between inputs and outputs. Ideal for predicting concrete's mechanical properties, GPR offers accuracy and versatility, making it suitable for diverse applications, as shown in [Figure 8](fig:Fig.8).
</p>

<div style="text-align: center;">
  <img src="https://github.com/uiceds/project-team-ads/blob/main/content/images/Picture8.png?raw=true" id="fig:Fig.8" style="width: 75%;"/>
  <p><strong>Figure 8: Working mechanism/flowchart of GPR.</strong></p>
</div>

<p align="justify">
In the [Figure 9](fig:Fig.9), a complete overview of the whole project is depicted pictorially.
</p>

<div style="text-align: center;">
  <img src="https://github.com/uiceds/project-team-ads/blob/main/content/images/Picture9.png?raw=true" id="fig:Fig.9" style="width: 75%;"/>
  <p><strong>Figure 9: A flowchart explaining the sequence of tasks in the project</strong>.</p>
</div>

### References {.page_break_before}

<div id="refs"></div>
