# Project Title:
Using Bayesian Neural Network Ensemble to predict thermo-acoustic combustion instability.
# Project Description:
We used input parameters such as power, equivalence ratio, fuel composition, and boundary condition of the tube are varied, which creates 900 unique input parameters. At each operating point, the combustion noise is recorded. In addition, short acoustic pulses at the fundamental frequency are supplied to the tube with a loudspeaker and the decay rates of subsequent acoustic oscillations are measured.

Using this data for training, we show that it is possible for a Bayesian ensemble of neural networks to predict the decay rate from a 300 ms sample of the combustion noise and therefore forecast impending thermoacoustic instabilities. The ensemble consists of 10 neural networks. Performed PCA analysis on training data. We also show that it is possible to recover the equivalence ratio and power of the flame from these noise snippets, confirming our hypothesis that combustion noise indeed provides a fingerprint of the combustor’s internal state.

The Bayesian ensemble accurately predicts decay rates, power, and equivalence ratios with low root-mean-squared errors, The RMSE was 0.028 on test data. Uncertainty estimates are higher for inputs differing significantly from training data, reflecting model reliability.
