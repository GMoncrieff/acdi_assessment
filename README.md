# acdi_assessment
Senior Data Scientist Assessment for ACDI

## Setup

```bash
conda env create -f environment.yml
conda activate acdi_assess
```

## Contents

| File | Description |
|---|---|
| [`task_1.ipynb`](task_1.ipynb) | Moving window distribution parameters on a large 3-D climate dataset using xarray + Dask |
| [`task_2.ipynb`](task_2.ipynb) | ERA5-Land 2m temperature download via CDS API (earthkit.data and cdsapi), with data structure description |
| [`environment.yml`](environment.yml) | Conda environment specification |

## Notes

- CDS API credentials must be configured in `~/.cdsapirc` before running `task_2.ipynb`.
- NetCDF data files are excluded from version control via `.gitignore`.

## AI disclosure

This assessment was completed in VS Code using inline code completion from GitHub Copilot (Claude Sonnet 4.5). The solution approach, choice of packages, and workflows were decided by me, and I wrote the code myself using only the assistance of inline code completion  (without the use of agentic code completion). AI was used to help format markdown descriptions and comments, but the content of those descriptions and comments was written by me.