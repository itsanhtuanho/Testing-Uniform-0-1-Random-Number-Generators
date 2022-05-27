# Testing-Uniform-0-1-Random-Number-Generators
Conducted empirical tests to assess how closely the random numbers generated from some popular random number generators resemble true independent and identically distributed Unif(0,1) numbers.
## Background and Description of Problem
For this project, I will conduct some empirical tests to assess how closely the random numbers generated from various popular RNGs resemble truly IID Unif(0,1). I have chosen 3 criteria that will be assessed for a “good enough” RNG. A good RNG, at a **bare minimum**, should have the following traits:

>**<font size="4">1. Can generate values that are i.i.d. Unif(0,1)</font>** <br>
**<font size="4">2. Very fast </font>** <br>
**<font size="4">3. Reproducible </font>** <br>


I have selected 3 RNGs: **RANDU, Desert Island, and L'ecuyer Combined Generator**, and will assess criteria (1) for each of them. After that, I will discuss criteria (2) and (3). But first let's import all the necessary libraries needed to conduct the relevant analysis.

## Required Libraries/Modules
1. numpy
2. pandas
3. matplotlib.pyplot
4. seaborn
5. time
6. scipy.stats
7. statsmodels.sandbox.stats.runs.runstest_1samp
