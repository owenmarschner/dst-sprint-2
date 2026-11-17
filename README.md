# Data Science Toolbox — Sprint 2

Compare neural networks for land-use and land-cover classification on EuroSAT satellite images, and assess how their computational requirements scale to 1,000 times as much data. See the [assessment brief](brief/sprint-2-description.pdf).

## Deadline

The group report and individual reflections are due on Blackboard by **12 noon on Wednesday 2 December 2026 (Week 11)**.

## Group members

- Alice
- Emily
- Oliwer
- Owen
- Tyler

| Model | Starting point |
| --- | --- |
| Two-layer CNN | Build a small CNN with random weights. |
| ResNet-18 from scratch | Load Torchvision ResNet-18 with `weights=None`. |
| ResNet-18 from ImageNet | Load ImageNet weights and add a 10-class head. |
| ResNet-18 from Sentinel-2 | Load TorchGeo’s RGB MoCo weights and add a 10-class head. |
| SatMAE | Load the single-image RGB checkpoint, freeze the backbone, and train a 10-class head. |
