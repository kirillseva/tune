# tune: efficient hyperparameter tuning in R [![Build Status](https://travis-ci.org/kirillseva/tune.svg?branch=master)](https://travis-ci.org/kirillseva/tune)

An R alternative to python's [hyperopt](https://github.com/hyperopt/hyperopt) and [spearmint](https://github.com/JasperSnoek/spearmint)

This implementation does not focus on the multi-core optimizations like hyperopt. Instead, it is assumed that your machine learning classifier is already using all available resources, hence linear approach will be just as fast on a single machine.
