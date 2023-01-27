# MVP and risk analysis of cryptocurrency since 2021

project for FIN-525

author: Ke Ma, Shufan Wang

## Files

1. `data/clean/whole_usdt_merge.pkl`: we store the itermediary data which are merged and cleaned raw files

2. `data/clean/in_out_risk*.pkl`: we store the rolling window results with different methods.

3. `project_main.ipynb`: the main file which contains files downloading, pre-processing, merge, and mvp computation.

4. `plot_risk_analysis.ipynb`: plot the in and out of sample risk.

5. `plot_cumulative_return.ipynb`: plot the cumulative returns of portfolio with different methods.

## How to use

Running the download code takes half to one day, we provide a zip file which contains all the raw files we downloaded from binance: https://drive.google.com/file/d/16lMA8q5Mpnr2Yedev_2EZeluZX5jgjtb/view?usp=share_link

You can uncomment the last block in `project_main.ipynb` to compute the risks and mvp based on our merged dataframe `data/clean/whole_usdt_merge.pkl` (392 cryptocurrencies with 8000 hours)

