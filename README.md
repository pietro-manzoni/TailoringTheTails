# Tailoring the Tails

[![Paper](https://img.shields.io/badge/Paper-PMLR-blue)](https://proceedings.mlr.press/v230/baviera24a.html)
[![Proceedings](https://img.shields.io/badge/PMLR-230%3A508--521-blue)](https://proceedings.mlr.press/v230/baviera24a.html)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

This repository contains supporting material for the paper:

> **Tailoring the Tails: Enhancing the Reliability of Probabilistic Load Forecasts**<br>
> Roberto Baviera, Pietro Manzoni<br>
> *Proceedings of the Thirteenth Symposium on Conformal and Probabilistic Prediction with Applications*<br>
> PMLR 230:508–521, 2024<br>
> Paper: https://proceedings.mlr.press/v230/baviera24a.html

## Overview

The paper studies probabilistic load forecasting, with a particular focus on the reliability of predicted distribution tails.

The proposed approach introduces a loss function designed to improve the balance between **forecast sharpness** and **forecast reliability**. The methodology is applied to electricity-load forecasting, where reliable uncertainty quantification is especially important for tail events.

This repository provides a lightweight companion to the paper, including selected code, documentation, and examples related to the forecasting framework.

## Models and Methods

The repository includes material related to:

* probabilistic load forecasting,
* density forecast evaluation,
* tail reliability assessment,
* sharpness-reliability trade-offs,
* loss-function design for reliable probabilistic forecasts.


## Citation

If you use this repository or build on the methodology in the paper, please cite:

```bibtex
@InProceedings{pmlr-v230-baviera24a,
  title     = {Tailoring the Tails: Enhancing the Reliability of Probabilistic Load Forecasts},
  author    = {Baviera, Roberto and Manzoni, Pietro},
  booktitle = {Proceedings of the Thirteenth Symposium on Conformal and Probabilistic Prediction with Applications},
  pages     = {508--521},
  year      = {2024},
  volume    = {230},
  series    = {Proceedings of Machine Learning Research},
  month     = {09--11 Sep},
  publisher = {PMLR},
  url       = {https://proceedings.mlr.press/v230/baviera24a.html}
}
```

## Paper

The published conference paper is available here:

https://proceedings.mlr.press/v230/baviera24a.html

## License

This repository is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**. This strong copyleft license requires that modified versions of the code remain open source, including when the software is used to provide a network service.

Please see the repository [`LICENSE`](LICENSE) file for the full license text.

Note that datasets used in the original analysis may be subject to separate licenses and may not be distributed with this repository.
