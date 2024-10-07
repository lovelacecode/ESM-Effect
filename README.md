This notebook contains the code accompanying the ICLR submission "ESMGain: EFFECTIVE AND EFFICIENT PREDICTION
OF MUTATION’S FUNCTIONAL EFFECT VIA ESM2 TRANSFER LEARNING AND ROBUST BENCHMARKS".

In the notebook we:
- download the dataset for training and evaluating on the DMSs used for the comparison with PreMode
- define the model, preprocess the data and construct the dataloader
- write a training and comprehensive evaluation function (incl. Harmonic Spearman)
- train & evalute the model on the DMSs.
