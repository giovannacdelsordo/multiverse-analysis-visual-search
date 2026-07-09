# multiverse-analysis-visual-search
This repository hosts interactive visualizations accompanying the manuscript: "Using a Multiverse Analysis to Determine Best-Practice Recommendations for Cleaning Datasets from Online and In-Person Visual Search Experiments"

The analyses examine how data-cleaning decisions influence conclusions drawn from visual search data. A multiverse of defensible cleaning pipelines is enumerated, and each pipeline is carried through the same analysis.

**Authors**
Giovanna C. Del Sordo, Michael C. Hout & Hayward J. Godwin

**Visual Search Task**
The data come from a visual search experiment in which participants decided, on each trial, whether a T-shaped target was present among L-shaped distractors. Target–distractor colour similarity was manipulated across three between-subjects conditions (low, medium, high)

**The multiverse**

Each specification corresponds to one combination of data-cleaning decisions applied to the same raw dataset. The reaction time and accuracy analyses use separate decision grids. Fully crossing the decisions yields 13,824 specifications for each reaction time curve and 72 specifications for each accuracy curve.

**Contents**

Four interactive specification curves are provided, corresponding to two outcomes (RT and accuracy) crossed with two trial types (target-absent and target-present trials). 

Each plot shows the result of the similarity effect estimated across every universe in the multiverse — one point per data-cleaning specification. Points are sorted left to right by effect size (partial η²), so the curve traces how the estimated effect grows across the specification space. The vertical axis is the effect size; hovering over any point reveals that universe's exact partial η², p-value, retained sample size, and the specific level chosen for all eight (RT) or four (accuracy) cleaning decisions.

By default, points are coloured by statistical significance (red = p < .05, grey = p ≥ .05), showing at a glance what fraction of the specification space yields a significant effect. The dropdown menu re-colours the same points by any single cleaning decision — selecting, for example, the upper RT cutoff shades each point by which cutoff that universe applied. This makes it possible to see whether a particular decision systematically drives the effect up or down: if one level of a decision clusters at the low or high end of the curve, that decision is a source of the variation.

Four curves are provided, one per analysis: reaction time and accuracy, each split by target-present and target-absent trials.

**Viewing the visualizations**

The specification curves are best viewed in a web browser:

- [Reaction time, target-absent trials](https://giovannacdelsordo.github.io/multiverse-analysis-visual-search/multiverse_RT_ABSENT.html)
- [Reaction time, target-present trials](https://giovannacdelsordo.github.io/multiverse-analysis-visual-search/multiverse_RT_PRESENT.html)
- [Accuracy, target-absent trials](https://giovannacdelsordo.github.io/multiverse-analysis-visual-search/multiverse_Accuracy_ABSENT.html)
- [Accuracy, target-present trials](https://giovannacdelsordo.github.io/multiverse-analysis-visual-search/multiverse_Accuracy_PRESENT.html)



Hover over a point to get its associated cleaning decisions.
