---
title: Machine Learning-Based Optimization Of The Mix Design Of Lightweight Concrete For Enhanced Mechanical Properties
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2024-09-27'
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
  <meta name="dc.date" content="2024-09-27" />
  <meta name="citation_publication_date" content="2024-09-27" />
  <meta property="article:published_time" content="2024-09-27" />
  <meta name="dc.modified" content="2024-09-27T07:12:04+00:00" />
  <meta property="article:modified_time" content="2024-09-27T07:12:04+00:00" />
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
  <link rel="alternate" type="text/html" href="https://uiceds.github.io/project-team-ads/v/00ad041d069f64bc1339e743a640a55fe281a454/" />
  <meta name="manubot_html_url_versioned" content="https://uiceds.github.io/project-team-ads/v/00ad041d069f64bc1339e743a640a55fe281a454/" />
  <meta name="manubot_pdf_url_versioned" content="https://uiceds.github.io/project-team-ads/v/00ad041d069f64bc1339e743a640a55fe281a454/manuscript.pdf" />
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






<small><em>
This manuscript
([permalink](https://uiceds.github.io/project-team-ads/v/00ad041d069f64bc1339e743a640a55fe281a454/))
was automatically generated
from [uiceds/project-team-ads@00ad041](https://github.com/uiceds/project-team-ads/tree/00ad041d069f64bc1339e743a640a55fe281a454)
on September 27, 2024.
</em></small>



## Authors



+ **Ayyan Iqbal**
  ^[✉](#correspondence)^<br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [maiqbal2](https://github.com/maiqbal2)
    <br>
  <small>
     University of Illinois
  </small>

+ **Shayan Khan**
  ^[✉](#correspondence)^<br>
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


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/uiceds/project-team-ads/issues)
or email to
Ayyan Iqbal \<\>, 
Shayan Khan \<\>.


:::


## Project Proposal {.page_break_before}

<p align="justify">
The escalating global population drives the increasing demand for concrete, thereby fostering the development and adoption of Lightweight Aggregate (LWA)-based Lightweight Concrete (LWC). The widespread availability of LWAs, coupled with straightforward and conventional casting techniques, has facilitated industry-wide acceptance [@doi:10.3390/su15010641]. LWC has found extensive applications in lightweight infill panels, structural concrete, and precast concrete. Notably, LWC achieves comparable compressive strength to traditional concrete in specific scenarios, albeit with a 25-35% reduction in density [@doi:10.3390/app11020800]. This reduction yields additional benefits, including minimized foundation steel requirements, lower transportation costs, and decreased construction expenditures, rendering LWC a promising solution for sustainable and cost-effective infrastructure development.
A significant obstacle in the widespread adoption of Lightweight Concrete (LWC) lies in its intricate mix design process. Unlike Normal-Weight Concrete (NWC), which relies on established codes and iterative fine-tuning, LWC lacks standardized design guidelines. Furthermore, optimizing LWC's density while maintaining compressive and tensile strength poses a substantial challenge due to its sensitive nature, where minor mix design adjustments drastically impact mechanical properties. The complexity is compounded by the varied shapes, sizes, and densities of LWAs, which significantly influence the mix design. In contrast, NWC aggregates exhibit relatively consistent properties.
To address this challenge, a machine learning (ML) framework can be employed to predict LWA concrete's mechanical properties, including compressive strength, tensile strength, and density. The development of user-friendly tools, leveraging these ML models, would facilitate iterative design optimization and trial-and-error experimentation for researchers working on specialized LWC mix designs.
This predictive tool would not only streamline LWC mix design hence enhancing accuracy in mechanical property prediction but expedite the development of tailored LWC solutions for specific applications. By integrating ML and materials science, this innovative approach would overcome existing design complexities and unlock LWC's full potential.
For the CEE-492 semester project, our team objectives are to develop and compare the performance of Artificial Neural Networks (ANN), Gaussian Process Regression (GPR), and Decision Trees in predicting the mechanical properties of Lightweight Concrete (LWC), specifically density, compressive strength, and tensile strength. Initially, relevant data from published online articles would be collected, followed by data preprocessing to ensure consistency and quality. Next, we identify 10 influential input parameters governing LWC mix design through a comprehensive literature review of the latest published review articles. An exploratory data analysis (EDA) is then conducted to uncover trends and relationships within the data. Subsequently, the preprocessed data is divided into training (~70-80%) and testing sets (~20-30%). The training data is then normalized and scaled to optimize model performance.
Then the team aims to train the ANN, GPR, and Decision Tree models on the training data, fine-tuning hyperparameters through cross-validation and grid search. Model evaluation is performed on the testing data using the statistical performance indicators i.e., such as mean squared error (MSE), R-squared (R²), and mean absolute error (MAE). Finally, we compare the performance of the trained models and select the best-performing algorithm. The formulas for the performance metrics are mentioned below in Table 1.
</p>

<p align="center">
Table 1. Mathematical formulation of the statistical performance indicators used in the report.
</p>

(https://github.com/uiceds/project-team-ads/blob/2a98874527713e85004b85271e1885919a5ee534/content/images/Eqs.png){#fig:Eq}

<p align="justify">
A longstanding controversy surrounds the efficacy and reliability of Machine Learning (ML) and Artificial Intelligence (AI)--based models, with critics labeling them as "black boxes" that merely identify patterns without providing meaningful insights. To address concerns regarding overfitting and model interpretability, we aim to explain or results by employing local explanation techniques, specifically Partial Dependence Plots (PDP) and Shapley Additive Explanations (SHAP). These methods decipher the relationships between individual input parameters and the model's output, demystifying the "black box" nature of ML models, validating their reliability and accuracy, and identifying potential biases. In the figure, a complete overview of the whole project is depicted pictorially.
</p>

1[A flowchart explaining the sequence of tasks in the project](https://github.com/uiceds/project-team-ads/blob/2a98874527713e85004b85271e1885919a5ee534/content/images/Flow Chart.png){#fig:Fc}

<p align="center">
Figure 1. A flowchart explaining the sequence of tasks in the project.
</p>

### Dataset description

<p align="justify">
The data set attached has been collected by the team members from all the scholarly articles from Scopus. The search query used for finding articles was “{Lightweight} AND {concrete} AND {aggregate} AND {strength} AND {density}AND{ML}”. The authors have collected 500 data points from over 50 articles. The data set has the quantities of Cement, sand, fly ash (FA), the density of lightweight aggregate, water absorption of lightweight aggregate, superplasticizer, curing time, and the amount of normal aggregate (normal agg.), as input parameters while the compressive strength, split tensile strength, and density of the concrete were taken as output parameters. The first test columns of the dataset correspond to inputs while the last three correspond to output. All the quantities were normalized by the cement quantity before the start of the analysis. The input and output parameters along with their units have been mentioned below in Table 2 as well.
</p>

<p align="center">
Table 2. Input and output parameters of the dataset along with their units.
</p>

| Parameters | Categories (I/O) |
|:-----------------:|:-------------:|
| Binder (kg/m3) | I |
| Fine agg. (kg/m3) | I |
| w/b | I |
| LW agg. (kg/m3) | I |
| LW agg. density (kg/m3) | I |
| LW agg. water absorption (%) | I |
| NW agg. (kg/m3) | I |
| HRWR (% of binder) | I |
| Curing Time (days) | I |
| Fly Ash (kg/m3) | I |
| Compressive Strength of LW concrete (MPa) | O |
| Split Tensile Strength of LW concrete (MPa) | O |
| Density of LW concrete (kg/m3) | O |

* I = Input
* O = Output
* LW = Lightweight 
* NW = Normal weight
* w/b = water to binder ratio
* HRWR = High range water reducer

This manuscript is a template (aka "rootstock") for [Manubot](https://manubot.org/ "Manubot"), a tool for writing scholarly manuscripts.
Use this template as a starting point for your manuscript.

The rest of this document is a full list of formatting elements/features supported by Manubot.
Compare the input (`.md` files in the `/content` directory) to the output you see below.

## Basic formatting

**Bold** __text__

[Semi-bold text]{.semibold}

[Centered text]{.center}

[Right-aligned text]{.right}

*Italic* _text_

Combined *italics and __bold__*

~~Strikethrough~~

1. Ordered list item
2. Ordered list item
    a. Sub-item
    b. Sub-item
        i. Sub-sub-item
3. Ordered list item
    a. Sub-item

- List item
- List item
- List item

subscript: H~2~O is a liquid

superscript: 2^10^ is 1024.

[unicode superscripts](https://www.google.com/search?q=superscript+generator)⁰¹²³⁴⁵⁶⁷⁸⁹

[unicode subscripts](https://www.google.com/search?q=superscript+generator)₀₁₂₃₄₅₆₇₈₉

A long paragraph of text.
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Putting each sentence on its own line has numerous benefits with regard to [editing](https://asciidoctor.org/docs/asciidoc-recommended-practices/#one-sentence-per-line) and [version control](https://rhodesmill.org/brandon/2012/one-sentence-per-line/).

Line break without starting a new paragraph by putting  
two spaces at end of line.

## Document organization

Document section headings:

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### A heading centered on its own printed page{.center .page_center}

<!-- an arbitrary comment. visible in input, but not visible in output. -->

Horizontal rule:

---

`Heading 1`'s are recommended to be reserved for the title of the manuscript.

`Heading 2`'s are recommended for broad sections such as *Abstract*, *Methods*, *Conclusion*, etc.

`Heading 3`'s and `Heading 4`'s are recommended for sub-sections.

## Links

Bare URL link: <https://manubot.org>

[Long link with lots of words and stuff and junk and bleep and blah and stuff and other stuff and more stuff yeah](https://manubot.org)

[Link with text](https://manubot.org)

[Link with hover text](https://manubot.org "Manubot Homepage")

[Link by reference][manubot homepage]

[Manubot Homepage]: https://manubot.org

## Referencing figures, tables, equations

Figure @fig:square-image

Figure @fig:wide-image

Figure @fig:tall-image

Figure @fig:vector-image

Table @tbl:bowling-scores

Equation @eq:regular-equation

Equation @eq:long-equation

## Quotes and code

> Quoted text

> Quoted block of text
>
> Two roads diverged in a wood, and I—  
> I took the one less traveled by,  
> And that has made all the difference.

Code `in the middle` of normal text, aka `inline code`.

Code block with Python syntax highlighting:

```python
from manubot.cite.doi import expand_short_doi

def test_expand_short_doi():
    doi = expand_short_doi("10/c3bp")
    # a string too long to fit within page:
    assert doi == "10.25313/2524-2695-2018-3-vliyanie-enhansera-copia-i-insulyatora-gypsy-na-sintez-ernk-modifikatsii-hromatina-i-svyazyvanie-insulyatornyh-belkov-vtransfetsirovannyh-geneticheskih-konstruktsiyah"
```

Code block with no syntax highlighting:

```
Exporting HTML manuscript
Exporting DOCX manuscript
Exporting PDF manuscript
```

## Figures

![
**A square image at actual size and with a bottom caption.**
Loaded from the latest version of image on GitHub.
](https://github.com/manubot/resources/raw/15493970f8882fce22bef829619d3fb37a613ba5/test/square.png "Square image"){#fig:square-image}

![
**An image too wide to fit within page at full size.**
Loaded from a specific (hashed) version of the image on GitHub.
](https://github.com/manubot/resources/raw/15493970f8882fce22bef829619d3fb37a613ba5/test/wide.png "Wide image"){#fig:wide-image}

![
**A tall image with a specified height.**
Loaded from a specific (hashed) version of the image on GitHub.
](https://github.com/manubot/resources/raw/15493970f8882fce22bef829619d3fb37a613ba5/test/tall.png "Tall image"){#fig:tall-image height=3in}

![
**A vector `.svg` image loaded from GitHub.**
The parameter `sanitize=true` is necessary to properly load SVGs hosted via GitHub URLs.
White background specified to serve as a backdrop for transparent sections of the image.
Note that if you want to export to Word (`.docx`), you need to download the image and reference it locally (e.g. `content/images/vector.svg`) instead of using a URL.
](https://raw.githubusercontent.com/manubot/resources/main/test/vector.svg?sanitize=true "Vector image"){#fig:vector-image height=2.5in .white}

## Tables

| *Bowling Scores* | Jane          | John          | Alice         | Bob           |
|:-----------------|:-------------:|:-------------:|:-------------:|:-------------:|
| Game 1 | 150 | 187 | 210 | 105 |
| Game 2 |  98 | 202 | 197 | 102 |
| Game 3 | 123 | 180 | 238 | 134 |

Table: A table with a top caption and specified relative column widths.
{#tbl:bowling-scores}

|         | Digits 1-33                        | Digits 34-66                      | Digits 67-99                      | Ref.                                                        |
|:--------|:-----------------------------------|:----------------------------------|:----------------------------------|:------------------------------------------------------------|
| pi      | 3.14159265358979323846264338327950 | 288419716939937510582097494459230 | 781640628620899862803482534211706 | [`piday.org`](https://www.piday.org/million/)               |
| e       | 2.71828182845904523536028747135266 | 249775724709369995957496696762772 | 407663035354759457138217852516642 | [`nasa.gov`](https://apod.nasa.gov/htmltest/gifcity/e.2mil) |

Table: A table too wide to fit within page.
{#tbl:constant-digits}

|          | **Colors** <!-- $colspan="2" --> |                      |
|:--------:|:--------------------------------:|:--------------------:|
| **Size** | **Text Color**                   | **Background Color** |
| big      | blue                             | orange               |
| small    | black                            | white                |

Table: A table with merged cells using the `attributes` plugin.
{#tbl: merged-cells}

## Equations

A LaTeX equation:

$$\int_0^\infty e^{-x^2} dx=\frac{\sqrt{\pi}}{2}$$ {#eq:regular-equation}

An equation too long to fit within page:

$$x = a + b + c + d + e + f + g + h + i + j + k + l + m + n + o + p + q + r + s + t + u + v + w + x + y + z + 1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9$$ {#eq:long-equation}

## Special

<i class="fas fa-exclamation-triangle"></i> [WARNING]{.semibold} _The following features are only supported and intended for `.html` and `.pdf` exports._
_Journals are not likely to support them, and they may not display correctly when converted to other formats such as `.docx`._

[Link styled as a button](https://manubot.org "Manubot Homepage"){.button}

Adding arbitrary HTML attributes to an element using Pandoc's attribute syntax:

::: {#some_id_1 .some_class style="background: #ad1457; color: white; margin-left: 40px;" title="a paragraph of text" data-color="white" disabled="true"}
Manubot Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot.
Manubot Manubot.
Manubot.
:::

Adding arbitrary HTML attributes to an element with the Manubot `attributes` plugin (more flexible than Pandoc's method in terms of which elements you can add attributes to):

Manubot Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot.
Manubot Manubot.
Manubot.
<!-- $id="element_id" class="some_class" $style="color: #ad1457; margin-left: 40px;" $disabled="true" $title="a paragraph of text" $data-color="red" -->

Available background colors for text, images, code, banners, etc:  

`white`{.white}
`lightgrey`{.lightgrey}
`grey`{.grey}
`darkgrey`{.darkgrey}
`black`{.black}
`lightred`{.lightred}
`lightyellow`{.lightyellow}
`lightgreen`{.lightgreen}
`lightblue`{.lightblue}
`lightpurple`{.lightpurple}
`red`{.red}
`orange`{.orange}
`yellow`{.yellow}
`green`{.green}
`blue`{.blue}
`purple`{.purple}

Using the [Font Awesome](https://fontawesome.com/) icon set:

<!-- include the Font Awesome library, per: https://fontawesome.com/start -->
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.2/css/all.css">

<i class="fas fa-check"></i> <i class="fas fa-question"></i> <i class="fas fa-star"></i> <i class="fas fa-bell"></i> <i class="fas fa-times-circle"></i> <i class="fas fa-ellipsis-h"></i>

[
<i class="fas fa-scroll fa-lg"></i> **Light Grey Banner**<br>
useful for *general information* - [manubot.org](https://manubot.org/)
]{.banner .lightgrey}

[
<i class="fas fa-info-circle fa-lg"></i> **Blue Banner**<br>
useful for *important information* - [manubot.org](https://manubot.org/)
]{.banner .lightblue}

[
<i class="fas fa-ban fa-lg"></i> **Light Red Banner**<br>
useful for *warnings* - [manubot.org](https://manubot.org/)
]{.banner .lightred}


### References {.page_break_before}

<div id="refs"></div>
