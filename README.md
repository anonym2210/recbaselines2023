# recbaselines2022  

## Dataset description

This dataset describes baseline models, which were used for comparative experiments in papers on different type of recommender systems. It consists of 1208 papers and 350 baseline models, having 5480 interractions between them. The dataset includes paper - baseline models interractions and additional data on each paper, such as WEB link to a paper, paper title and year of publishing. 

The data was collected from [Google Scholar](https://scholar.google.com/). The collected articles were published between 2010 and 2022. The dataset will be supplementing as new papers are being released. If you find any inconsistency or would like your paper to be included in the dataset, please contact us. 

Each row of the dataset consists of following collumns:
| Column | Description | Example |
|:--------|:-----------:|:--------:|
| Paper_id | Unique paper identification | 1 |
| URL | WEB link to a paper | https://arxiv.org/pdf/1809.07053.pdf |
| Title | Paper title | NAIS: Neural Attentive Item Similarity Model for Recommendation |
| Year | A year of publishing | 2018 |
| Baselines | List of used recommender algorithms | MF;MLP;FISM;NAIS |

## Dataset statistics

| Number of papers | Number of models | Number of interactions | Density |
|:--------|:-----------:|:--------:|
| 1,208 | 350 | 5,480 | 1.3\% |
