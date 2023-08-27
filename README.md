# Wallet-browser-extension

The Wallet Browser Extension is a versatile tool designed to simplify wallet management, facilitate transfers through ENS names, and generate QR codes for user profiles. The extension harnesses Moralis APIs to retrieve token and NFT information for the logged-in account.

<p align="center">
    <img src="./mwallet/src/display.png" width="50%">
</p>

<br />

## Features

### Wallet Management

- **Create New Wallet:** Generate a new wallet
- **Load Existing Wallet:** Import an existing wallet for seamless access.

### ENS Resolution and Transfers

- **ENS Name Resolution:** Enter an ENS name to promptly obtain the corresponding address for transfers.
- **Recipient's Address:** When entering the recipient's address for transfers, remember to include a space after the address.
- ENS resolution works only on Ethereum Mainnet

<br />

<p align="center">
    <img src="./mwallet/src/transfer.png" width="50%">
</p>

<br />

### QR Code Generation

- **Generate QR Codes:** Create QR codes effortlessly, which can then be scanned to link to ENS profiles.

<br />

<p align="center">
    <img src="./mwallet/src/generateqr.png" width="50%">
</p>

<br />

### Moralis API Integration

- **Token and NFT Information:** Utilize Moralis APIs to query comprehensive token and NFT data associated with the logged-in account.
- **Backend Setup:** To integrate Moralis APIs, you'll need an API key to facilitate seamless data retrieval.

### Supported Chains

The extension is compatible with the following chains:

- Ethereum Mainnet
- Polygon (MATIC) Mumbai Testnet
- Goerli Testnet
- Polygon Mainnet
- Avalanche Mainnet
