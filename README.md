# MixedModelANOVA
Mixed Model ANOVA using Pingouin package in Python
A mixed-design analysis of variance model is useful when there is both a between-subjects factor (e.g. Group: control or meditation) and a within-subjects factor (e.g. Time: August, January or June)
There is indeed a significant interaction in this example, however, knowing this does not tell us which specific contrast is actually significant. The next step is that we need to perform post-hocs tests on the interaction. This can be done very easily as seen here, using Pingouin's pairwise_ttests function.
