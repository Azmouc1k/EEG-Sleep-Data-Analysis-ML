Sleep stage classification is crucial to understand sleep patterns and it aids in predicting sleep disorders early 
on, which is one of the main problems: people are too late to diagnose the disorders. 
In this study, Using the PhysioNet 
Sleep-EDF Expanded Dataset, I evaluate the impact of incorporating temporal context (TC) and Leave-One-Subject
Out (LOSO) cross-validation for generalizability in two main models: 

Random Forest (RF) and Long Short-Term Memory (LSTM) networks.

The data contains EEG recordings of patients during sleep and PSG recording with 
corresponding annotations of events. Containing EEG recordings annotated for five sleep stages: Wake (W), Stage 1, 
Stage 2, Stage 3/4 (merged), and REM. There are many analyses already done to classify different sleep stages in 
EEG, however, certain stages, such as Stage 1 sleep are still very hard to classify due to their transitional nature. RF 
achieved a mean accuracy of 68% under LOSO, while LSTM with temporal context attained 66%. I discuss the 
strengths, weaknesses, and potential future directions of these models in sleep stage classification.
