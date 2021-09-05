# Welcome to the Machine-Learning (ML) Performance Clustering Project!
***
## <a id="Contents">Cotents</a>
[Project Description](#Project-Description)<br>
[Technologies and Resources](#Technologies-Resources)<br>
[Installation Guide](#Installation-Guide)<br>
[Usage](#Usage)<br>
[Contributors](#Contributors)<br>
[License](#License)<br>
[Bottom of Page](#Bottom-of-Page)<br>

***
## <a id="Project-Description">Project Description</a>
This project applies financial analysis experience combined with unsupervised machine-learning to classify cryptocurrency performance throughout time.<br>

Using unsupervised learning, this project makes sense of the unlclassified datasets by extracting features and patterns on its own. These operations are performed by utilizing dimensionality reduction and clustering, Principal Component Analysis (PCA) and K-Means respectively.<br>

Following the classification of the performance, this project presents visualizations to trend the performance over time.<br> 

#### Project layout:
The layout of this project is show below.<br>
.<br>
├── crypto_investments.ipynb<br>
├── data<br>
│   └── crypto_market_data.csv<br>
├── img<br>
│   ├── crypto-performance-clustering.png<br>
│   └── elbow-plot.png<br>
│   └── project_tree.png<br>
├── LICENSE<br>
├── README.md<br>
├── requirements.txt<br>
└── tree.txt<br>

***
## <a id="Technologies-Resources">Technologies and Resources</a>
#### Technologies:
<a href="https://docs.python.org/release/3.8.0/" title="https://docs.python.org/release/3.8.0/"><img src="https://img.shields.io/badge/python-3.8%2B-red">
<a href="https://pandas.pydata.org/docs/" title="https://pandas.pydata.org/docs/"><img src="https://img.shields.io/badge/pandas-1.3.1-green"></a>
<a href="https://jupyter-notebook.readthedocs.io/en/stable/" title="https://jupyter-notebook.readthedocs.io/en/stable/"><img src="https://img.shields.io/badge/jupyter--notebook-5.7.11-blue"></a>
    <a href="https://hvplot.holoviz.org/user_guide/Introduction.html" title="https://hvplot.holoviz.org/user_guide/Introduction.html"><img src="https://img.shields.io/badge/hvplot-0.7.3-orange"></a>
    <a href="https://scikit-learn.org/stable/user_guide.html" title="https://scikit-learn.org/stable/user_guide.html"><img src="https://img.shields.io/badge/scikit_learn-0.24.2-green"></a><br>

***
## <a id="Installation-Guide">Installation Guide</a>
### Project Installation
To install <a href="https://github.com/jasonjgarcia24/ml-performance-clustering.git" title="https://github.com/jasonjgarcia24/ml-performance-clustering.git">ml-performance-clustering</a>, type <code>git clone https://github.com/jasonjgarcia24/ml-performance-clustering.git</code> into bash in your prefered local directory.<br><br>
Alternatively, you can navigate to the same address (<code>https://github.com/jasonjgarcia24/ml-performance-clustering.git</code>) and download the full <code>main</code> branch's contents as a zip file to your prefered local directory.<br>

## <a id="Usage">Usage</a>
Observe price-dislocation with <code>crypto_investments.ipynb</code>. No input variables are required.<br>

### Outputs
This tool provides several necessary visualizations for Cryptocurrency performance analysis:
1. K versus Inertia plots for both price change percentage of 24 hours versus 7 days and the PCA data:<br>
<img src="img/elbow-plot.png" title="elbow plot"><br>
These inertia plots allow us to measure the distribution of the data within a cluster given the K values.<br>

2. Scatter plots of both the original dataset and the PCA clusters following dimensionality reduction:<br>
<img src="img/crypto-performance-clustering.png" title="crypto performance clustering"><br>

***
## <a id="Contributors">Contributors</a>
Currently just me :)<br>

***
## <a id="License">License</a>
Each file included in this repository is licensed under the <a href="https://github.com/jasonjgarcia24/ml-performance-clustering/blob/2370b0c29d2c11c57d7c41d581612a5ca8c35503/LICENSE" title="LICENSE">MIT License.</a>

***
[Top of Page](#Top-of-Page)<br>
[Contents](#Contents)<br>
[Project Description](#Project-Description)<br>
[Technologies and Resources](#Technologies-Resources)<br>
[Installation Guide](#Installation-Guide)<br>
[Usage](#Usage)<br>
[Contributors](#Contributors)<br>
[License](#License)<br>
<a id="Bottom-of-Page"></a>
