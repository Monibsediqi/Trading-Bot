Trading Bot for Alpaca

link to image: ![Trading Bot](https://github.com/Monibsediqi/Trading-Bot/assets/42628945/a90d9b52-bce6-4a3d-a957-f489bafcc555)

## Description

This is a trading bot that uses the Alpaca API to trade stocks. It uses the Alpaca API to get current news data, and uses the data to make decisions on whether to buy or sell a stock. The bot uses a simple sentiment analysis to make decisions. The bot also uses the Alpaca API to get account information and to place orders.

## Startup and Dependencies

1. Createa virual environemnt using conda `conda create -n alpacaenv python=3.7`
2. Activate the virtual environment `conda activate alpacaenv`
3. Install the required packages `pip install -r requirements.txt`
4. Update the API_KEY and SECRETE_KEY with values from your Alpaca account
5. Run the bot `python trading_bot.py`

### Torch Installation

1. Install torch `conda install pytorch torchvision torchaudio cpuonly -c pytorch`
2. Install transformers `pip install transformers`

## Usage

The bot can be run by executing the `trading_bot.py` file. The bot will run indefinitely and will make trades based on the current news data. The bot will also print out the current account information and the current news data.

## Contributors

- Author: [Monib Sediqi]
- Email: monib.korea@gmail.com
- Version: 1.x.x
- Date: 2024-02-10
- License: MIT
