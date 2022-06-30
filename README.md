1. Los Usuarios pueden entrar a la Loteria basada en ETH con USD gas o fee
2. Un Admin escogera cuando la loteria ha sido terminada
3. La Loteria seleccionara aleatoriamente al ganador

TODO:

1. crear app en alchemys.io.. "ViewKey"

Cmd:
Delete: mainnet-fork - brownie networks delete mainnet-fork

alchemys.io-APIKEY: brownie networks add development mainnet-fork cmd=ganache-cli host://127.0.0.1 fork=https://apikey-alchemysapi accounts=10 mnemonic=brownie port=8545

brownie test --network mainnet-fork-dev

brownie compile
