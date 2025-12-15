# applied-statistics-assessment
by Zoe McNamara Harlowe

### Welcome to my submission for the assessment for the Applied Statistics module. This module is provided by ATU (Atlantic Technological University) as part of the HDip in Computing in Data Analytics.

---

## Table of Contents

1. [Prerequisites](#prerequisites)  
2. [Setup](#setup)
3. [Technologies](#technologies)
4. [Libraries](#libraries)
5. [Project Structure](#project-structure)    
6. [Problems](#problems)

---

## Prerequisites

- Python 3.7 or higher  
- Required packages (listed in `requirements.txt`):  
  ```bash
  numpy
  scipy.stats
  itertools
  math
  matplotlib.pyplot
  collections

---

## Setup

**View the repository online using Github Codespaces:**
1. Sign up for a free Github account.
2. Go to the repository page in your browser.
3. Click the green 'Code' button.
4. Click the 'Codespaces' tab.
5. Click 'Create New Codespace' on main.


**Or you can clone the repository onto your own machine:**
1. In Commander, clone the repo and change directory:
```bash 
git clone <https://github.com/zoeharlowe/applied-statistics-assessment>
cd <applied-statistics-assessment>
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Launch the Jupyter Notebook problems.ipynb locally:
```bash
jupyter notebook problems.ipynb
```

--- 

## Technologies

- Python
- Git
- Github
- Codespaces
- Jupyter

---

## Libraries

- Numpy: https://numpy.org/doc/2.3/user/absolute_beginners.html
- Scipy: https://docs.scipy.org/doc/scipy/reference/stats.html
- Itertools: https://docs.python.org/3/library/itertools.html
- Matplotlib: https://matplotlib.org/3.5.3/api/_as_gen/matplotlib.pyplot.html
- Math: https://docs.python.org/3/library/math.html
- Collections: https://docs.python.org/3/library/collections.html

--- 

## Project Structure

### Applied Statistics Assessment:
- .gitignore
- README.md            
- requirements.txt      
- problems.ipynb:
  - [Imports](problems.ipynb#imports)
  - [Problem 1: Extending the Lady Tasting Tea](problems.ipynb#problem-1-extending-the-lady-tasting-tea)
  - [Problem 2: Normal Distribution](problems.ipynb#problem-2-normal-distribution)
  - [Problem 3: t-Tests](problems.ipynb#problem-3-t-tests)
  - [Problem 4: ANOVA](problems.ipynb#problem-4-anova)

---

## Problems

- ### Problem 1: Extending the Lady Tasting Tea
Based on the famous experiment by Ronald Fisher, this exercise extends this idea to explore permutation tests and the logic of hypothesis testing. I compare the 12-cup extension to the original 8-cup problem, discussing whether the p-value threshold should be extended or relaxed in the new version.
  - **References:** 
    - *Background of Lady Tasting Tea Experiment:* https://medium.com/data-science/lady-tasting-tea-a-bayesian-approach-1b0b94ca1530
    - *numpy.random.shuffle() documentation:* https://numpy.org/doc/2.1/reference/random/generated/numpy.random.shuffle.html
    - *ChatGPT: Writing code for counter in simulation:* https://chatgpt.com/share/690f7e85-5580-800c-bff9-2e3903c5923d
    - *numpy.random.choice() documentation:* https://numpy.org/doc/2.1/reference/random/generated/numpy.random.choice.html
    - *math.comb() documentation:* https://docs.python.org/3/library/math.html#math.comb

- ### Problem 2: Normal Distribution
This problem focuses on the properties of the normal distribution. It involves simulating data, visualizing distributions, and calculating probabilities. I explored the difference between the population standard deviation and the sample standard deviation.
  - **References:**
    - *Allen Downey: Which Standard Deviation?* https://www.allendowney.com/blog/2024/06/08/which-standard-deviation/
    - *ChatGPT: Creating transparent histogram of SDs:* https://chatgpt.com/share/691b2267-2d10-800c-9a24-fe39970893b9
    - *Investopedia: The Law of Large Numbers:* https://www.investopedia.com/terms/l/lawoflargenumbers.asp

- ### Problem 3: t-Tests
This problem looks into independent two-sample t-tests. In this problem, I tun a simulation in which I compare samples of varying means, explore p-values, and interpret the results. I also note the change in Type II error rate based on the change in means.
  - **References:**
    - *Wikipedia: Type I and II errors:* https://en.wikipedia.org/wiki/Type_I_and_type_II_errors
    - *Lecture notes about t-Tests and ANOVA:* https://github.com/ianmcloughlin/applied-statistics/blob/main/materials/anova.ipynb
    - *Copilot: Help with writing code for t-test simulation:* https://copilot.microsoft.com/shares/KZJYtYbm5fxb8ntvFFHbq

- ### Problem 4: ANOVA
In this problem, I compare ANOVA results with multiple t-tests, illustrating why ANOVA is the preferred approach for multi-group comparisons.
    - **References:**
      - *Wikipedia: ANOVA:* https://en.wikipedia.org/wiki/Analysis_of_variance
      - *Copilot: Help with interpreting ANOVA test results:* https://copilot.microsoft.com/shares/CZnMsyFYGU6TTPGCUSUze
      - *StatisticHowTo: Tukey Test:* https://www.statisticshowto.com/probability-and-statistics/statistics-definitions/post-hoc/tukey-test-honest-significant-difference/
      - *Laerd Statistics: Independent t-test for two samples:* https://statistics.laerd.com/statistical-guides/independent-t-test-statistical-guide.php
      - *Copilot: Plotting side-by-side comparisons between different test methods:* https://copilot.microsoft.com/shares/N2Y2pfMvus7yu6aTyKsyg
      - *Copilot: Help with analysis of plot:* https://copilot.microsoft.com/shares/UXWniKfmX3DN8iHPqZVfJ
      - *Laerd Statistics: ANOVA one-way:* https://statistics.laerd.com/statistical-guides/one-way-anova-statistical-guide-2.php