# Welcome to the repository! 

This repository helps in determining the customer's intent when brosing in an online shopping store. To do so, relationship between available attributes is found out. Then clutering is done to divide the transactions happened into clusters. Then after the cluters are formed, we can predict whether the current transaction will result in genration of revenue. One can work on those clusters formed to do more analysis.

## Visualisations

To  see the plotly visualisations, please clone the notebook, and convert the plotly code cells to 'code' cells from 'markdown' cells. You should also uncomment the plotly code whenever necessary. Thank you!

## Future additions

Work is going on making models to do deeper analysis on the clusters so formed.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install PyPDF2, pandas and matplotlib.

```bash
pip install pandas 
pip install matplotlib
pip install plotly
```

## Usage

```python
import matplotlib.pyplot as plt
import pandas as pd
import plotly.express as px
```

## Resources
The dataset has been downloaded from UCI's ML repository. [Click here to download the dataset.](https://archive.ics.uci.edu/ml/machine-learning-databases/00468/online_shoppers_intention.csv)

The dataset has been created by the authors Sakar, C.O., Polat, S.O., Katircioglu. They have written a paper on this [which you can read here.](https://doi.org/10.1007/s00521-018-3523-0)
[The citation file](https://github.com/vishxm/DataScienceNBs/blob/master/CustomerIntention/10.1007_s00521-018-3523-0.ris) is uploaded in the folder alongside with theJupyter notebook. 

## Contributions
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)


