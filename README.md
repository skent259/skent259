### Hi! I'm Sean Kent 👋

I love to write code at the intersection of statistics, machine learning, and new research. Here, I'll highlight a few of my favorite code projects.

## SVM-based algorithms for Multiple Instance Learning

[`mildsvm`](https://github.com/skent259/mildsvm): Weakly supervised, multiple instance data lives in numerous interesting applications such as drug discovery, object detection, and tumor prediction on whole slide images. The `mildsvm` package provides an easy way to learn from this data by training Support Vector Machine (SVM)-based classifiers. It also contains helpful functions for building and printing multiple instance data frames. `mildsvm` includes an implementation of MI-SMM from our research paper [Kent and Yu
    (2022)](https://arxiv.org/abs/2206.14704) "Non-convex SVM for cancer diagnosis based on morphologic features of
tumor microenvironment". The package can be installed via `install.packages("mildsvm")` in R.  

## Causal Matching for Longitudinal Data

[`rsmatch`](https://github.com/skent259/rsmatch) is an R package designed to perform Risk Set Matching. Risk set matching is useful for causal inference in longitudinal studies where subjects are treated at varying time points. The main idea is that treated subjects can match with anyone who hasn't yet been treated and those who never get treatment, but each subject can only be used in one pair. This creates a mixed-integer programming problem that we implement based on Li, Propert, and Rosenbaum (2001) [Balanced Risk Set Matching](https://www.tandfonline.com/doi/abs/10.1198/016214501753208573). This package can be installed via `install_github("skent259/rsmatch")`.  

## Simulate the Game of Craps

I don't gamble often&mdash;but, for me, the most entertaining way to lose money in a casino is playing craps.  As a side-project, I developed a simulator in python ([skent259/CrapsSim](https://github.com/skent259/CrapsSim)) to test various betting strategies. With it, I analyzed the best craps strategies for players on a budget, published on [my blog](http://pages.stat.wisc.edu/~kent/blog/2019.07.31_Craps_Budget/craps_best-strategies-on-a-budget.html).  

***

The rest of my repositories are a mixture of machine learning implementations, visualizations from other contexts, talks that I've given, and more. Feel free to check out those projects below!

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





