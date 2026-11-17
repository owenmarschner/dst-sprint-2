# Owen — SatMAE

**Starting point** — Load the single-image RGB SatMAE checkpoint, freeze its backbone, and add a 10-class head.

**Task** — Train the classifier on EuroSAT RGB using features from the frozen SatMAE backbone. Follow the [shared training and evaluation protocol](../data/README.md) and record test accuracy and training time for the group comparison.
