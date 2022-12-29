# recbaselines2022  
This dataset describes baseline models, which were used for comparative experiments in papers on different type of recommender systems. It consists of 1208 papers and 350 baseline models, having 5480 interractions between them. 

The data was collected from [Google Scholar](https://scholar.google.com/). The collected articles were published between 2010 and 2022. The dataset will be supplementing as new papers are being released. If you find any inconsistency or would like your paper to be included in the dataset, please contact us. 

Each row of the dataset consists of following collumns:
| Column | Description | Example |
|:--------|:-----------:|:--------:|
| Paper_id | Unique paper identification | 1 |
| URL | WEB link to a paper | https://arxiv.org/pdf/1809.07053.pdf |
| Title | Paper title | NAIS: Neural Attentive Item Similarity Model for Recommendation |
| Year | A year of publishing | 2018 |
| Baselines | List of used recommender algorithms | MF;MLP;FISM;NAIS |
