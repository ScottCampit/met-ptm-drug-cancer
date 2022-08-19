# met-ptm-drug-cancer
Machine learning to learn metabolite-histone-drug interactions in cancer.

There are 5 notebooks relevant to this analysis:
  1. PCC: Generates pearson correlation coefficient profiles between metabolite/PTM/drug datasets.
  2. TrainLASSO: Trains LASSO models using TensorFlow.
  3. EMT: Applies the trained LASSO models to EMT datasets.
  4. AggregateCoefficients: Aggregates coefficients from LASSO, stepwise regression, and k-TSP.
  5. SynergyAntagonism: Visualizes cell count percent changes using metabolite/drug profiles.
