# chetan CLI

Command line interface written in Node.js to check cryptocurrency prices

Register an API key at https://nomics.com

## Usage

```
npm install

npm link
```

## Commands

```
# Help & Commands
chetan -h

# Version
chetan -V

# API Key Commands
chetan key set
chetan key show
chetan key remove

# Crypto Check Commands
chetan check price

# Check Specific Coins (default: BTN,ETH,XRP)
chetan check --coin=BTC,ETH

# Choose Currency (Default: USD)
chetan check --cur=EUR
```

### Version

1.0.0

### License

MIT
