### Hi! I'm Sean Kent 👋

I'm currently a Ph.D. student in Statistics at the University of Wisconsin - Madison.  You can see more of my experience, background, and blog posts on my website: <http://pages.stat.wisc.edu/~kent/>.  Here, I'll highlight a few of my favorite code projects.

## SVM-based algorithms for Multiple Instance Learning

[`mildsvm`](https://github.com/skent259/mildsvm) is an R package that implements functions to train a variety of models for multiple instance learning, a subset of machine learning where rows of data are grouped into bags and only outcomes on the bags are observed.  This incorporates methods proposed by our reserach where instances can be thought of as probability distributions and where the outcome label is ordinal.  It also includes previous SVM-based algorithms from the literature, including Andrews, Tsochantaridis, and Hofmann (2003) [Support Vector Machines for Multiple-Instance Learning](https://proceedings.neurips.cc/paper/2002/file/3e6260b81898beacda3d16db379ed329-Paper.pdf) and Xiao, Liu, and Hao (2018) [Multiple-Instance Ordinal Regression](https://ieeexplore.ieee.org/abstract/document/8107717?casa_token=-My_3w0W9PsAAAAA:3kuIvYYIFWOpNVCQl4rpI5iFBPPqdaQV57MRbC0GfWPbN45Za8YApt6-YjCeB6PomsehPuG0XjE).  This package can be installed via `install_github("skent259/mildsvm")`.  

## Causal Matching for Longitudinal Data

[`rsmatch`](https://github.com/skent259/rsmatch) is an R package designed to perform Risk Set Matching. Risk set matching is useful for causal inference in longitudinal studies where subjects are treated at varying time points. The main idea is that treated subjects can match with anyone who hasn't yet been treated and those who never get treatment, but each subject can only be used in one pair. This creates a mixed-integer programming problem that we implement based on Li, Propert, and Rosenbaum (2001) [Balanced Risk Set Matching](https://www.tandfonline.com/doi/abs/10.1198/016214501753208573). This package can be installed via `install_github("skent259/rsmatch")`.  

## Interactive Shiny Dashboards for COVID-19

I spent some time developing interactive visualizations and dashboards to help understand the COVID-19 pandemic in Wisconsin.  Most of these were joint work with [Srikanth Aravamuthan](https://github.com/aravamu2) and the AFI Data Science Institute's [COVID-19 Research Group](https://datascience.wisc.edu/covid19/).  These visualizations were developed with a variety of tools, including `shiny`, `plotly`, and `ggplot2`.

- **[Growth Rates of COVID-19 in Wisconsin Metropolitan Areas](https://github.com/UW-Madison-DataScience/wi-covid-growth)**.  We looked deeply into how COVID-19 was growing and whether growth was changing, which was useful in the pandemic's early days.  These visualizations were adapted for Gundersen Health System and Marshfield Clinic to look at growth in smaller counties. Daily updates are provided [here](https://data-viz.it.wisc.edu/wi-metro-growth-rate/). 

- **[Paltiel COVID-19 Screening for College Campuses](https://github.com/UW-Madison-DataScience/Paltiel-COVID-19-Screening-for-College)**.  This interactive dashboard was built to complement the paper by Paltiel et al. (2020) [Assessment of SARS-CoV-2 Screening Strategies to Permit the Safe Reopening of College Campuses in the United States](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2768923). It allows researchers to plug in values relevant to their campus/population to see how testing frequency, R0, and other parameters influence COVID-19 spread on campus.  The dashboard, built with R `shiny` with `shinydashboards`, is live [here](https://data-viz.it.wisc.edu/covid-19-screening/)

- **[Instantaneous R_0 Geofacetted by Wisconsin counties](https://github.com/aravamu2/jhepc)**.  This visualization was designed to illustrate how the instantaneous R_0 varies spatially and temporally in Wisconsin counties.  It's built with python + plotly and won an *honorable mention* at SciPy 2020's [John Hunter Excellence in plotting contest](https://jhepc.github.io/).

- **[Parameter Sweep Dashboard for Modelers](https://github.com/UW-Madison-DataScience/cornel-model-dashboard)**.  To analyze variuos potential scenarios for COVID-19 spread on campus and beyond, researchers at UW revised [Cornell's](https://datasciencecenter.cornell.edu/research/covid-19-mathematical-modeling-for-cornells-fall-semester/) COVID-19 model to fit the Madison campus and community.  This dashboard provides an interactive and detailed look at some of those scenarios, allowing researchers to find what parameters cause differences in the spread, quarantine populations, and time of peak COVID-19 cases. An interactive test version is available [here](https://data-viz.it.wisc.edu/cornell-parameter-sweep/).  

## Simulate the Game of Craps

I don't gamble often&mdash;but I find craps to be the most entertaining way to lose money in a casino.  As a side-project, I developed a simulator in python ([skent259/CrapsSim](https://github.com/skent259/CrapsSim)) to test various betting strategies. With it, I analyzed the best craps strategies for players on a budget, published on [my blog](http://pages.stat.wisc.edu/~kent/blog/2019.07.31_Craps_Budget/craps_best-strategies-on-a-budget.html).  

***

The rest of my repositories are a mixture of machine learning implementations, visualizations from other contexts, talks that I've given, and more.  Feel free to check out those projects below!

<!--
**skent259/skent259** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->





