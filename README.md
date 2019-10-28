### What this be?
We will
use the ALARM (A Logical Alarm Reduction Mechanism) dataset to infer a consistent Bayesian Network underlying a complex medical dataset. This Bayes-Net can
then be used for constructing a data-driven medical diagnostic system using inference
algorithms, such as Belief-Propagation.
Three type of variables are present in the ALARM dataset- diagnoses, measurements,
and intermediate variables. After constructing a suitable probabilistic model, the resulting model can be used for automatically diagnosing a patient with a set of symptoms and test results. For details on the variables present in the dataset, please refer to
the original paper and the webpage https://rdrr.io/cran/bnlearn/man/alarm.
In this exercise, we will be estimating the most likely tree-structured probabilistic
graphical model underlying the ALARM dataset.


* Go to PSET2-EE16B070.ipynb for problem 1.
* Tree Diagrams Obtained are at mi_10k.gv.pdf and mi_jvhw_10k.gv.pdf
* Collaborators: Siddharth Nayak

### Requirements:
* graphviz
* numpy
* matplotlib
* pandas
* sklearn

#### For installing graphviz you have to install the graphviz package along with the python graphviz package.
##### For MacOSX: `brew install graphviz`
##### For Ubuntu: `sudo apt-get install graphviz`
After the above step,
* `pip install graphviz` or `conda install graphviz`

#### For other python libraries, just do `pip install <package-name>`

## References:
* Prim's Algorithm: CoderByte tutorial on [Minimum Spanning Tree](https://coderbyte.com/algorithm/find-minimum-spanning-tree-using-prims-algorithm)
* JVHW Mutual Information Estimator: [GitHub Repository](https://github.com/EEthinker/JVHW_Entropy_Estimators)

