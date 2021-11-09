#### FinTech Bootcamp - Module 10 Challenge
---
# Crypto Portfolio Performance through K-Means Unsupervised Learning

Competition in the cryptocurrency market is fierce, so I propose a novel approach to assembling crypto investment portfolios. Instead of basing analysis on just  returns and volatility, I have included other factors that might impact the crypto market—leading to better performance for your portfolio.

This is a prototype for submitting my crypto portfolio proposal to the *Company XYZ* board of directors.

---

## Technologies

This program was written in Python 3.9.4 using Windows OS. It is a Jupyter notebook, but was developed in VSCode.

Imports required:

```python
import pandas as pd
import hvplot.pandas
from pathlib import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
```

---

## Usage

This is a **Jupyter notebook** that clusters cryptocurrencies by their performance in different time periods. The results are plotted so one can visualize each coin/token's performance.

The .csv file within *Starter_code* contains the price change data of the cryptocurrencies in question in different periods.

---

## Contributors


Developed by E. Kenny, acting as "an advisor in one of the top five financial advisory firms in the world.", per assignment instructions. 

[LinkedIn](www.linkedin.com/in/e-kenny)

ekenny3@uncc.edu

---

## License

MIT

License included in repository.