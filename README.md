### Hi! I'm Sean Kent 👋

I'm currently a PhD Student in Statistics at the University of Wisconsin - Madison.  You can see more of my experience, background, and blog posts on my personal website: <http://pages.stat.wisc.edu/~kent/>.  Here, I'll highlight a few of my favorite code projects.

## Causal Matching for Longitudinal Data

[`rsmatch`](https://github.com/skent259/rsmatch) is an R package designed to perform Risk Set Matching. Risk set matching is useful for causal inference in longitudinal studies where subjects are treated at varying time points. The main idea is that treated subjects can match with anyone who hasn't yet been treated and those who never get treatment, but each subject can only be used in one pair. This creates a mixed-integer programming problem that we implement based on [Li, Propert, and Rosenbaum (2001) "Balanced Risk Set Matching"](https://www.tandfonline.com/doi/abs/10.1198/016214501753208573). This package can be installed via `install_github("skent259/rsmatch")`.  

## Interactive Shiny Dashboards for COVID-19

I spent some time developing interactive visualizations and dashboards to help understand the COVID-19 pandemic in Wisconsin.  Most of these were joint work with [Srikanth Aravamuthan](https://github.com/aravamu2) and other members of the AFI Data Science Institute's [COVID-19 Research Group](https://datascience.wisc.edu/covid19/).  These visualizations are hosted on the web for all to access, and mostly developed with `shiny`, `plotly`, and `ggplot2` in R

- **[Growth Rates of COVID-19 in Wisconsin Metropolitan Areas](https://github.com/UW-Madison-DataScience/wi-covid-growth)**.  More useful in the early days of the pandemic, we looked deeply into how COVID-19 was growing and whether growth was changing in key areas.  These visualizations were adapted for Gundersen Health System and Marshfield Clinic to look at growth in smaller counties. Daily updates are provided [here](https://data-viz.it.wisc.edu/wi-metro-growth-rate/). 

- **[Paltiel COVID-19 Screening for College Campuses](https://github.com/UW-Madison-DataScience/Paltiel-COVID-19-Screening-for-College)**.  This interactive dashboard was built to complement the paper by Paltiel et al. (2020) “Assessment of SARS-CoV-2 Screening Strategies to Permit the Safe Reopening of College Campuses in the United States” and allows researchers to plug in values relevant to their campus/population to see how testing frequency, R0, and other parameters influence COVID-19 spread on campus.  The dashboard, built in R `shiny` with `shinydashboards`, is live [here](https://data-viz.it.wisc.edu/covid-19-screening/)

- **[Instantaneous R_0 Geofacetted by Wisconsin counties](https://github.com/aravamu2/jhepc)**.  This visualization was designed to allow an understanding of how the instantaneous R_0 vaires spatially and temporally in Wisconsin counties.  It's built in python + plotly was won an *honorable mention* at SciPy 2020's [John Hunter Excellence in plotting contest](https://jhepc.github.io/).

- **[Parameter Sweep Dashboard for Modelers](https://github.com/UW-Madison-DataScience/cornel-model-dashboard)**.  In order to analyze a variety of potential scenarios for COVID-19 spread on campus and beyond, researchers at UW adapted a model from [Cornell](https://datasciencecenter.cornell.edu/research/covid-19-mathematical-modeling-for-cornells-fall-semester/) to fit the Madison campus and community.  This dashboard provides an interactive and detailed look at some of those scenarios and allows researchers to find what parameters play a key difference in the spread, quarantine populations, and time of peak COVID-19 cases. An interactive test version is available [here](https://data-viz.it.wisc.edu/cornell-parameter-sweep/).  

## Simulate the Game of Craps

I don't gamble often&mdash;but I find craps to be the most entertaining way to lose money in a casino.  As a side-project, I developed a simulator in python ([skent259/CrapsSim](https://github.com/skent259/CrapsSim)) to test out a variety of betting strategies. This led to some interesting results published on [my blog](http://pages.stat.wisc.edu/~kent/blog/2019.07.31_Craps_Budget/craps_best-strategies-on-a-budget.html).  

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





