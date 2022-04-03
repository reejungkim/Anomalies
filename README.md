# Anomalies

[![Gmail Badge](https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=mailto:reejugn.kim@gmail.com)](mailto:reejung.kim@gmail.com) 
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=www.linkedin.com/in/reejungkim/)](https://www.linkedin.com/in/reejungkim/) 
[![Git page](http://img.shields.io/badge/-Portfolio-black?style=flat-square&logo=github&link=https://reejungkim.github.io/)](https://reejungkim.github.io/)
<br></br>

## 1. Anomaly detection and visualization
[Jupyter notebook](Boston%20housing%20outliers.ipynb)

<img src="img/outliers.png" height="200" width="400"><img src="img/cooks_distance.png" height="40" width="80">
    
## 2. Irregularity (card fraud) detection


### Supervised learning model applied: random forest

Parameter optimization: random search

[Jupyter notebook](credit%20card%20fraud%20detection%20v2.ipynb)

<img src="img/difference.png" height="200" width="400"><img src="img/fraud_detection_roc.png" height="200" width="400">

<p>Strength: High accuracy </p>
<p>Weakness: Class-imbalance problem exists (only 0.172% of fraud labelled data)</p>

<br></br>
### Semi-Supervised learning model applied: One-Class SVM

Strength: learning is enabled without fraud labelled data

Weakness: Lower accuracy rate compare to supervised learning models
<br></br>

### Autoencoder 

Strength: No need of labelling pocedures

Weakensss: Low accuracy. Sensitive to hyper paramter

