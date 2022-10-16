# telegram-bitcoin-p2p-exchange
Implementation of a cryptocurrency P2P exchange service based on the telegram messenger.

This implementation uses the following stack:
- Java
- Spring
- MySql
- Telegram-bot-api
- Bitcoin-rpc

The service does not use external resources to control balances, create and confirm transactions. Instead, it is customary to use a BitcoinD node via Bitcoin-rpc client.

The BitcoinD client can be installed on the same machine as the service, or on a remote machine.

View an example of the service:
- http://t.me/BTC_source_bot

To purchase the service, please contact https://t.me/LexProfi
