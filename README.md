# LSTM Climatological Time Series Analysis

Experiments in climatological time series analysis using deep learning.

## STATUS

Loss `0.0049` on SSN with 384-layer LSTM and 100 epochs (seems like 30 are enough). See [the notebook](LSTM-SSN.ipynb).

## PLAN

### Phase 1

1. [ ] create a generic LSTM framework/notebook
2. [x] analyze SSN (Solar Sunspot Numbers) monthly series
3. [ ] analyze Global/Local Datasets (temperature, precipitation, etc)
4. [ ] analyze climatic indices (ENSO, etc)

### Phase 2

1. [ ] modify the network in order to accept Continuous Wavelet Transform output
2. [ ] generate signal from predicted CWT spectra

## References

_John Abbot et al._: The application of machine learning for evaluating anthropogenic versus natural climate change, GeoResJ (2017). [DOI: 10.1016/j.grj.2017.08.001](http://dx.doi.org/10.1016/j.grj.2017.08.001)

_Qin Zhang et al._: Prediction of Sea Surface Temperature using Long Short-Term Memory. [arXiv:1705.06861 \[cs.CV\]](https://arxiv.org/abs/1705.06861)

_Bao W, Yue J, Rao Y_: A deep learning framework for financial time series using stacked autoencoders and long-short term memory. Podobnik B, ed. PLoS ONE. 2017;12(7):e0180944. [doi:10.1371/journal.pone.0180944](http://doi.org/10.1371/journal.pone.0180944)

_Franco Zavatti_:  Clima, Reti Neurali, Dati di Prossimità e Analisi Spettrali. http://www.climatemonitor.it/?p=46061

https://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/

## Links for self

http://www.willfleury.com/machine-learning/forecasting/lstm/2017/09/01/short-term-forceasting-lstm.html

https://github.com/simaaron/kaggle-Rain

https://thesai.org/Downloads/Volume8No2/Paper_43-Prediction_by_a_Hybrid_of_Wavelet_Transform.pdf

## Datasets

SSN Sunspot Number - Source: WDC-SILSO, Royal Observatory of Belgium, Brussels

