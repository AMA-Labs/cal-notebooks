# cal-notebooks
CEOS Analytics Laboratory notebooks and tools

To add these notebooks to your user enviroment just click on the link below:
[Click here to add notebooks!](https://hub.cal.ceos.org/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FAMA-Labs%2Fcal-notebooks&branch=main&urlpath=lab%2Ftree%2Fcal-notebooks%2F)

This link will pull the latest version of the notebooks into your enviroment while merging your changes. If you click the link again all un changed notebooks will be updated to the most recent version. If you would like the original version of the notebook simply change the nameo of your copy and click the link again.



## Contributing

Contributions are welcome.

A `pre-commit` hook is provided in `/bin`. For each notebook committed:

1. Create an HTML copy of the notebook into `html/`.
1. Strip *outputs* from the notebook to limit the size of the repository.

The `apply_hooks.sh` script creates a symlink to `bin/pre-commit`.

```bash
# Run this in your local repository
sh bin/apply_hooks.sh
```

For contributors:

1. Apply the pre-commit hook.
1. Run each notebook (that has been updated) to populate the figures, tables and other *outputs* as you want them.
1. For each new notebook add a link to `html/readme.md`.
1. `git add` and `git commit`.
1. If eveything looks ok, `git push` to your fork of this repository and create a *pull request*.


## HTML examples
* [EAIL_Cloud_Statistics_L8.html](https://raw.githack.com/CSIRO-Chile/cal-notebooks/main/examples/html/EAIL_Cloud_Statistics_L8.html)
* [EAIL_Cloud_Statistics_S2.html](https://raw.githack.com/CSIRO-Chile/cal-notebooks/main/examples/html/EAIL_Cloud_Statistics_S2.html)
* [EAIL_S1_Land_Change.html](https://raw.githack.com/CSIRO-Chile/cal-notebooks/main/examples/html/EAIL_S1_Land_Change.html)
* [EAIL_S1_Water_Threshold.html](https://raw.githack.com/CSIRO-Chile/cal-notebooks/main/examples/html/EAIL_S1_Water_Threshold.html)
* [EAIL_S2_Vegetation_Phenology.html](https://raw.githack.com/CSIRO-Chile/cal-notebooks/main/examples/html/EAIL_S2_Vegetation_Phenology.html)
* [EAIL_Spectral_Products_L8.html](https://raw.githack.com/CSIRO-Chile/cal-notebooks/main/examples/html/EAIL_Spectral_Products_L8.html)
* [EAIL_Spectral_Products_S2.html](https://raw.githack.com/CSIRO-Chile/cal-notebooks/main/examples/html/EAIL_Spectral_Products_S2.html)
* [EAIL_Vegetation_Change_L8.html](https://raw.githack.com/CSIRO-Chile/cal-notebooks/main/examples/html/EAIL_Vegetation_Change_L8.html)
* [EAIL_Water_GA_WOFS_L8.html](https://raw.githack.com/CSIRO-Chile/cal-notebooks/main/examples/html/EAIL_Water_GA_WOFS_L8.html)
* [EAIL_Water_GA_WOFS_S2.html](https://raw.githack.com/CSIRO-Chile/cal-notebooks/main/examples/html/EAIL_Water_GA_WOFS_S2.html)
* [EAIL_Water_WOFS_L8.html](https://raw.githack.com/CSIRO-Chile/cal-notebooks/main/examples/html/EAIL_Water_WOFS_L8.html)
* [EAIL_Water_WOFS_S2.html](https://raw.githack.com/CSIRO-Chile/cal-notebooks/main/examples/html/EAIL_Water_WOFS_S2.html)