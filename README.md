# CryptoBot

CryptoBot is an easy to use bot for Twitter that can check the crypto prices across 40 blockchains. It uses the [CoinGecko API](https://www.coingecko.com/en/api) to fetch the latest market data and tweets it to your followers.

## Features

- Supports 40 blockchains, including Bitcoin, Ethereum, Cardano, Polkadot, and more.
- Tweets the current price, 24-hour change, and market cap of any crypto you choose.
- Allows you to customize the tweet format, frequency, and hashtags.
- Runs on a serverless platform, such as [AWS Lambda](https://aws.amazon.com/lambda/), for low cost and high scalability.

## How to use

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Create a [Twitter developer account](https://developer.twitter.com/en/apply-for-access) and get your API keys and tokens.
4. Create a [CoinGecko account](https://www.coingecko.com/account/sign_up) and get your API key.
5. Edit the `config.py` file with your credentials and preferences.
6. Deploy the `bot.py` file to your serverless platform of choice.
7. Enjoy your CryptoBot!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
