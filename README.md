# SOMTimeS: Self-Organizing Maps for TIME Series

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

## Background

SOMEtimeS is an unsupervised machine learning algorithm that uses dynamic time warping and self-organized maps to discover and intuitively display patterns among complex communication features that happen over the course of conversation.

Libraries Imported:

* numpy: For numerical operations.
* matplotlib.pyplot: For plotting (though not used in the code shown).
* csv and random: Handle CSV files and randomness.
* defaultdict, multiprocessing, time: For organizing data, parallel processing, and timing.
* joblib.Parallel: To parallelize tasks.
* dtaidistance.dtw: For computing Dynamic Time Warping (DTW), which measures similarity between time series.
* tslearn.metrics: For time series metrics.
* scipy.spatial.distance.cdist: To compute pairwise distances.
* copy: For deep copying of objects.
* sklearn.cluster: Clustering algorithms like KMeans, Agglomerative Clustering, and Spectral Clustering.

## Install
somtime is available on PyPI 

```console
$ pip install somtimes
```

### Install from source


```console
$ python setup.py install
```

## Usage

see demo.py for example and explaination of usage
The SOM can cluster time series data.

## Contributing
Pull Requests are accepted, please review the [the contributing file](CONTRIBUTING.md)!

## License

[MIT licensee](../LICENSE)

## Citation
If you use this code please cite SOMTimeS paper.
Javed A, Rizzo D, Suk Lee B, Gramling R. SOMTimeS: Self Organizing Maps for Time Series Clustering and its Application to Serious Illness Conversations. (Pre-print [https://arxiv.org/abs/2108.11523](https://arxiv.org/abs/2108.11523)

or use
```
@misc{javed2021somtimes,
      title={SOMTimeS: Self Organizing Maps for Time Series Clustering and its Application to Serious Illness Conversations}, 
      author={Ali Javed and Donna M. Rizzo and Byung Suk Lee and Robert Gramling},
      year={2021},
      eprint={2108.11523},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```

