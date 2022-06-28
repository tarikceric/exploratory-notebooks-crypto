# # Exploring trends that lead to outperforming weekly/daily price action

Analyze the volume/price action that lead to a significant price outperformance for lower cap coins. The pycoingecko library is used to retrieve token information from Coingecko.

The goal is to determine if there is any trend that tends to lead to a token having price action that outperforms the rest of the market. 

1. Extract price and volume data for tokens over the past month
2. Calculate daily price increases, over the previous day and week
3. Identify which tokens had the highest price increase for each day
4. Create a dataframe with each day's top mover and the preceding price/volume/etc. data

### Setup

Install dependencies

- virtualenv venv
- source venv/bin/activate
- pip3 install -r requirements.txt

Start Jupyter server in terminal via:
- jupyter notebook