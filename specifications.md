# Technical Inforamtion
<!-- [![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/) -->





<!-- [![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/Naereen/ama) -->

<!-- [![Static Badge](https://img.shields.io/badge/any_text-you_like-blue)]() -->




| Feature                        | Details                                                                                                                                         |
|---------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| **Contact**                     | [![Static Badge](https://img.shields.io/badge/Contact_Author-11a600)](mailto:oleksandr.ilchenko@slu.se)                                        |
| **Download installer**          | [Download](https://github.com/CreMoProduction/pyromics/releases/latest)                                                                        |
| **Publications**                | NA                                                                                                                                             |
| **Training datasets**           | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18458637.svg)](https://doi.org/10.5281/zenodo.18458637)                                    |
| **Processing source code**      | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18608843.svg)](https://doi.org/10.5281/zenodo.18608843)                                    |
| **Documentation and user guide**| [![Docsify powered on GitHub](https://img.shields.io/badge/github-repo-blue?logo=github)](https://github.com/CreMoProduction/pyromics)         |
| **Programming languages**       | [![made-with-python](https://img.shields.io/badge/Made%20with-Python-fcd303.svg)](https://www.python.org/)                                     |
| **Platforms**                   | [![Windows](https://badgen.net/badge/icon/windows?icon=windows&label)](https://microsoft.com/windows/)                                         |
| **IDE**                         | [![Visual Studio](https://badgen.net/badge/icon/visualstudio?icon=visualstudio&label)](https://visualstudio.microsoft.com)                     |
| **Output formats**              | CSV                                                                                                                                            |
| **Input formats**               | netCDF                                                                                                                                         |
| **Web platform**                | No                                                                                                                                             |
| **Desktop client**              | Yes                                                                                                                                            |
| **CLI**                         | No                                                                                                                                             |
| **GUI**                         | Yes                                                                                                                                            |
| **License**                     | [License](LICENSE.md),                                                                                                                         |
| **Privacy policy**              | [Privacy policy](privacy_policy.md)                                                                                                            |
| **Instruments tested**          | **Agilent**: 7890A GC/5975C MSD, 8890 GC/5977 MSD                                                                                     |

# Data processing




Pyromics provides a range of state-of-the-art methods for each step of the data processing pipeline. This modular approach allows you to customize your workflow and choose the best algorithm for your specific dataset and export the processing settings to a preset file. Tables below provide a concise overview of the available methods for each stage.

| Step                                   | Methods                                                      |
|-----------------------------------------|--------------------------------------------------------------|
| [Denoising](denoising.md)               | Gaussian, Moving average                                     |
| [Baseline correction](baseline_correction.md) | Polynomial fitting, Asymmetric least squares            |
| [Sample alignment](sample_alignment.md) | Correlation optimized warping (COW)                          |
| [Deconvolution](deconvolution.md)       | Multivariate curve resolution alternative regression (MCR-ALS) |
| [Annotation](annotation.md)             | Dot product, Pearson correlation, Squared Euclidean               |

<br><br>

| MCR-ALS Options               | Methods                              |
|------------------------------|--------------------------------------|
| Constraints                  | Non-negativity least squares         |
| Initialization               | SVD, PCA, VCA                |
| Rank determination           | Mean Square Error minimization, eigenvalue, singular value        |
