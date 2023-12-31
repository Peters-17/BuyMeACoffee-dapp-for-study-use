## Following tutorial link: https://docs.alchemy.com/docs/how-to-build-buy-me-a-coffee-defi-dapp

# Buy Me a Coffee DeFi dapp

Blockchain technology empowers us to program money using code and software, opening up new possibilities for applications and protocols. This project demonstrates how to build a decentralized "Buy Me a Coffee" smart contract, allowing users to send (fake) ETH as tips and leave messages. The dapp is developed using Alchemy, Hardhat, Ethers.js, and Ethereum Goerli.

## Features

- Accept tips in the form of (fake) ETH from users worldwide.
- Visitors can leave messages along with their tips.
- Easy setup and usage with a MetaMask wallet on the Goerli test network.

## Prerequisites

Before running the project, make sure you have the following installed:

- Node.js and npm (Node Package Manager)
- MetaMask extension for your browser

## Installation

Set up by creating a `.env` file, and filling out these variables:

```
GOERLI_URL="your Alchemy RPC URL"
GOERLI_API_KEY="your Alchemy API key"
PRIVATE_KEY="your wallet private key"
```

You can get an Alchemy RPC URL for free [here](https://alchemy.com/?a=roadtoweb3weektwo).

Clone the repository:
   ```
   git clone https://github.com/your-username/BuyMeACoffee-dapp-for-study-use.git
   ```
   
Navigate to the project directory:
   ```
   cd BuyMeACoffee-dapp-for-study-use
   ```
   
Install the dependencies:
   ```
   npm install
   ```

## Usage

1. Configure MetaMask:
   - Connect MetaMask to the Goerli test network.
   - Get test ETH from [goerlifaucet.com](https://goerlifaucet.com).
   
2. Start the development server:
   ```
   npm start
   ```

3. Open the application in your browser at `http://localhost:3000`.

## Contributing

Contributions are welcome! If you find any issues or have ideas for improvements, please submit an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Resources

- Video tutorial: [YouTube link](https://www.youtube.com/watch?v=your-video-id)
- Alchemy: [Documentation](https://docs.alchemy.com)
- Hardhat: [Documentation](https://hardhat.org)
- Ethers.js: [Documentation](https://docs.ethers.io)

## Disclaimer

This dapp is developed for educational purposes only. Use it at your own risk.

---

Feel free to modify and customize this README file according to your project's specific details and requirements.
