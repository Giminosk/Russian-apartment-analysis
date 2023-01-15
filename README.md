# Russian apartment analysis

To analyze the situation on the real estate market, I used a ready-made [dataset](https://www.kaggle.com/datasets/mrdaniilak/russia-real-estate-20182021?datasetId=1340021&sortBy=voteCount), which of unique objects of popular real estate portals in Russia. Feature engineering, EDA were performed, then XGBRegressor was trained on the dataset. The model trained on this dataset with manually collected samples from [web archive](https://web.archive.org/).

## Result from comparison
<img src="/result/comparison.png" width="300" height="400"/>

## File structure
- `data` is folder with data in .csv format
- `result` is folder with screenshoted results of applying model on samples not from dataset
- `russian-estate.ipynb` is main notebook
