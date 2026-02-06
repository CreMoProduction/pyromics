# Technical Inforamtion
<!-- [![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/) -->


[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![Visual Studio](https://badgen.net/badge/icon/visualstudio?icon=visualstudio&label)](https://visualstudio.microsoft.com)
[![Windows](https://badgen.net/badge/icon/windows?icon=windows&label)](https://microsoft.com/windows/)
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/Naereen/ama)
[![Static Badge](https://img.shields.io/badge/any_text-you_like-blue)]()
[![Static Badge](https://img.shields.io/badge/Contact-8A2BE2)]()



| Feature                        | Details                                                                                                                                         |
|---------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| **Publications**                | PMID:32541957                                                                                                                                   |
| **Training datasets**           | Yes                                                                                                                                            |
| **Documentation and user guide**| Docsify powered on GitHub                                                                                                 |
| **Download / Web-service link** | Yes                                                                                                                                            |
| **Programming languages**       | Python                                                                                                                                             |
| **Platforms**                   | Windows                                                                                                                    |
| **Output formats**              | CSV                                                                                                                                            |
| **Input formats**               | netCDF     |
| **Web platform**                | No                                                                                                                                             |
| **Desktop client**              | Yes                                                                                                                                            |
| **CLI**                         | No                                                                                                                                            |
| **GUI**                         | Yes                                                                                                                                            |
| **License**                     | LGPL v3 (code) / CC-BY-SA (software)                                                                                                           |

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
