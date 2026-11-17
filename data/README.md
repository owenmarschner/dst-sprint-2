# EuroSAT RGB data

| Folder | Images | Use |
| --- | ---: | --- |
| `EuroSAT_RGB/` | 27,000 | Full dataset for exploration and reference. It contains both splits. |
| `train/` | 21,600 | Shared training set for all five models. Take any validation subset from here. |
| `test/` | 5,400 | Shared test set for final evaluation after model and hyperparameter selection. |

The fixed 80/20 split was sampled within each of the 10 classes using random seed `42`. The two splits share no images and together cover the full dataset. Use these folders as provided for every model comparison.

Each folder has the same class subdirectories and can be loaded directly with `torchvision.datasets.ImageFolder`. From the repo root, pass `data/train` or `data/test` as the dataset root. The JPEGs are ready to use after cloning or pulling the repo.

Source: [EuroSAT RGB v2 by Helber, Bischke, Dengel and Borth](https://doi.org/10.5281/zenodo.7711810), released in 2018 under the [MIT License](LICENSE-EuroSAT.txt). EuroSAT contains modified Copernicus Sentinel-2 data. The split folders copy the original JPEGs byte for byte. [Copernicus Sentinel data terms](https://cds.climate.copernicus.eu/licences/ec-sentinel).
