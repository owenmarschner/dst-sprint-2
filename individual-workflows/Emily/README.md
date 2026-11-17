# Emily — ResNet-18 from Sentinel-2

**Starting point** — Load TorchGeo’s RGB MoCo ResNet-18 weights pretrained on Sentinel-2 imagery and add a 10-class head.

**Task** — Adapt the pretrained network to EuroSAT RGB to assess transfer from satellite imagery. Follow the [shared training and evaluation protocol](../data/README.md) and record test accuracy and training time for the group comparison.
