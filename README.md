# Short-Term Wave Forecasts Using Gated Recurrent Unit Model

This repository is the code for a paper by the same name, currently under review at Ocean Engineering journal. 
If you use this work for publication, please cite:


## Description

Short-term ocean waves forecasting requires a high degree of skill and knowledge, as one should observe the available model forecast and real-time measurement and reach a combined estimation. This paper presents a deep learning model providing a short-term wave height prediction derived from recent in-situ measurements and an available mid-rage forecast. The model is based of a gated recurrent unit, which is common in time-series forecasting. The model is able to improve significant wave height RMSE by as much as 76\% for 1 hour forecasts and converge to $\sim$12\% improvement for forecasts over 7 hours. The model is also shown to be easily transferable to another station and achieves good performance without further training in a "zero-shot" learning process. This model can prove valuable to various off-shore operations, allowing for data-driven decision making instead of skilled human operator and experience-based evaluation.

## Getting Started

Code is available in [this notebook](https://github.com/yuvalyevnin/GRU_buoy/blob/master/Final.ipynb). Example of data is available as well, but it is recommended to download full data.

### Dependencies

Downloading the full data from ECMWF requires registering, installing and configuring [cdsapi](https://cds.climate.copernicus.eu/api-how-to)
Downloading the full data from Poseidon requires registering and requesting data at https://poseidon.hcmr.gr/

## Authors

Yuval Yevnin (yuval.yevnin@gmail.com) and Yaron Toledo
