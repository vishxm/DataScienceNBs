
# Welcome to the repository!

This repository helps in determining the **top 10 colleges for Civil Engineering under Savitribai Phule University**. To do so, we first scrape the data off of the pdf provided by the **Maharashtra** government. Then with the help of pandas, we do the processing to get the results.

 - [Top 10 colleges according to **General Open Category Cut-Offs**](https://github.com/vishxm/DataScienceNBs/blob/master/CapGuideTask/civilTop10.ipynb)
 - [Top 10 colleges according to **General and Ladies Open Category Cut-Offs**](https://github.com/vishxm/DataScienceNBs/blob/master/CapGuideTask/civilTop10New.ipynb)

## Resources

 1. [The PDF with all the rank details.](https://github.com/vishxm/DataScienceNBs/blob/master/CapGuideTask/college_cutoffs.pdf)
 2. [The refined version of above PDF that has only Savitribai Puhle University backed colleges.](https://github.com/vishxm/DataScienceNBs/blob/master/CapGuideTask/needed_pages.pdf)
 3. [The excel version of refined PDF made using ILovePdf.com](https://github.com/vishxm/DataScienceNBs/blob/master/CapGuideTask/needed_pages.xlsx)
 4. [Generated CSV file containing GOPEN rank data.](https://github.com/vishxm/DataScienceNBs/blob/master/CapGuideTask/college_Open.csv)
 5. [Generated CSV file containing GOPEN as well as LOPEN rank data.](https://github.com/vishxm/DataScienceNBs/blob/master/CapGuideTask/college_GL_Open.csv)

## Future additions

Work to determine the top 10 colleges considering cut-off ranks of various categories is going on. More commits will be done in future. Star the repo for updates!

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install PyPDF2, pandas and matplotlib.

```bash
pip install PyPDF2 pandas matplotlib
```

## Usage

```python
import matplotlib.pyplot as plt
import pandas as pd
import PyPDF2
```

## Contributions
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update the tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)



