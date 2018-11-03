# neurodsp

[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![Latest Version](https://img.shields.io/pypi/v/neurodsp.svg)](https://pypi.python.org/pypi/neurodsp/)
[![Build Status](https://travis-ci.org/voytekresearch/neurodsp.svg)](https://travis-ci.org/voytekresearch/neurodsp)
[![License](http://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat)](LICENSE.md)
[![Supported Python Versions](https://img.shields.io/pypi/pyversions/neurodsp.svg)](https://pypi.python.org/pypi/neurodsp/)
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/voytekresearch/neurodsp/master)

A package of modules to process and analyze neural recordings as individual voltage time series. The primary purpose of this library is to serve as the shared codebase for the [Voytek Lab](http://voyteklab.com/), but we welcome anyone's use and contributions.

## Python version support
This package has been tested on python 3.5, and 3.6 with the latest [Anaconda](https://www.continuum.io/downloads) distribution. Support for python 2 and earlier versions of python 3 is not guaranteed.

## Install

To install the latest release of neurodsp, you can install from pip:

`$ pip install neurodsp`

To get the development version (updates that are not yet published to pip), you can clone this repo.

`$ git clone https://github.com/voytekresearch/neurodsp.git`

To install this cloned copy of neurodsp, move into the directory you just cloned, and run:

`$ pip install .`

## Modules

- burst : Detect bursting oscillators in neural signals ([Tutorial](https://github.com/voytekresearch/neurodsp/blob/master/tutorials/Lagged%20coherence.ipynb))
- filt : Filter data with bandpass, highpass, lowpass, or notch filters ([Tutorial](https://github.com/voytekresearch/neurodsp/blob/master/tutorials/Filtering.ipynb))
- laggedcoherence : Estimate rhythmicity using the lagged coherence measure ([Tutorial](https://github.com/voytekresearch/neurodsp/blob/master/tutorials/Lagged%20coherence.ipynb))
- sim : Simulate bursting or stationary oscillators with brown noise ([Tutorial](https://github.com/voytekresearch/neurodsp/blob/master/tutorials/Simulating%20oscillators%20and%20noise.ipynb))
- spectral : Compute spectral domain features (PSD and 1/f slope, etc) ([Tutorial](https://github.com/voytekresearch/neurodsp/blob/master/tutorials/Spectral%20domain%20analysis.ipynb))
- swm : Identify recurrent patterns in a signal using sliding window matching ([Tutorial](https://github.com/voytekresearch/neurodsp/blob/master/tutorials/Sliding%20Window%20Matching.ipynb))
- timefrequency : Estimate instantaneous measures of oscillatory activity ([Tutorial](https://github.com/voytekresearch/neurodsp/blob/master/tutorials/Instantaneous%20measures%20of%20phase%20amplitude%20and%20frequency.ipynb))

## Dependencies

- numpy
- scipy
- matplotlib
- scikit-learn
- pytest (optional)
