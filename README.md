# Landscapes of Crashes

This presentation, titled **"Landscapes of Crashes,"** introduces a novel approach to analyzing financial markets and predicting crashes using **Topological Data Analysis (TDA)**. The core idea is that the "shape" of market data changes in detectable ways before a major crisis.

The method involves:
- Transforming multivariate financial time series (e.g., from several stock indices) into a sequence of geometric point clouds using a sliding window.
- Applying persistent homology to each point cloud to quantify its topological features, particularly the presence of loops, which can signify anomalous correlation structures.
- Representing these topological features as *persistence landscapes* and calculating their **L<sub>p</sub>-norm** to create a single time-series indicator of the market's "topological complexity."

The presentation validates this method on synthetic data, showing the indicator is sensitive to chaos, variance, and volatility shifts. When applied to real US market data from 1987–2016, the indicator shows massive spikes that align perfectly with major financial crashes.

A key finding is that this TDA-based indicator successfully signaled the 2000 dot-com crash, a period where the standard VIX "fear index" failed to do so, demonstrating that TDA can capture a different, more systemic type of risk based on the market's internal correlation structure.

---

In this repository, you will find the code used for some of the simulations shown in the presentation, including scripts to reproduce the figures and analyses.
