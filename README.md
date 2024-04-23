# behavysis_core

[Documentation](https://tlee08.github.io/behavysis_core/)

Core functionalities shared across the Behavysis suite.

## Installation

### Dev installation

```bash
conda env create -f conda_env.yaml
conda activate ba_pipeline_env
pip install poetry
poetry install
```

### User installation

```bash
conda env create -f conda_env.yaml
conda activate ba_pipeline_env
pip install .
```

## References

Mathis, A., Mamidanna, P., Cury, K. M., Abe, T., Murthy, V. N., Mathis, M. W., & Bethge, M. (2018, August 20). DeepLabCut: markerless pose estimation of user-defined body parts with deep learning. Nature Neuroscience. Springer Science and Business Media LLC. http://doi.org/10.1038/s41593-018-0209-y

Nath, T., Mathis, A., Chen, A. C., Patel, A., Bethge, M., & Mathis, M. W. (2019, June 21). Using DeepLabCut for 3D markerless pose estimation across species and behaviors. Nature Protocols. Springer Science and Business Media LLC. http://doi.org/10.1038/s41596-019-0176-0

Lauer, J., Zhou, M., Ye, S., Menegas, W., Schneider, S., Nath, T., … Mathis, A. (2022, April). Multi-animal pose estimation, identification and tracking with DeepLabCut. Nature Methods. Springer Science and Business Media LLC. http://doi.org/10.1038/s41592-022-01443-0
