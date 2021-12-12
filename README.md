<div id="top"></div>
</br>
<div align="center">
  <img src="https://i.ibb.co/xHDbBM5/Block-Commerce-Logo-Rendered.png" alt="BlockCommerce Logo_Rendered" width="100" height = "100">
  <h3>BlockCommerce</h3>
	<p>A good tool for setting up Ethereum-based marketplace applications</p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project
Provide you with a package secured by Blockchain and Smart Contract to build, manage and revise all aspects between bulding and developing software for Ethereum-based marketplace projects.

### Built with
* [Ethereum](https://ethereum.org/en/)
* [Solidity](https://docs.soliditylang.org/en/v0.8.10/)
* [Web3js](https://web3js.readthedocs.io/en/v1.5.2/)
<!-- <p align="right">(<a href="#top">back to top</a>)</p> -->

## Setting Up
This section is all about relevant softwares, extensions and how to install this package.
### Prerequisites
For using BlockCommerce, you need first to have metamask available in your browser.
</br>
- Download metamask [here](https://metamask.io/download.html) (Choose the firefox to download it to your browser).
- See how to use metamask [here](https://metamask.io/faqs.html).
### Installation
Use the package manager [npm](https://docs.npmjs.com/) to install.
- npm
```
  npm install npm@latest -g
```
- block-commerce-contract
```
  npm install block-commerce-contract
```

<!-- FEATURES -->
## Features
Below are what BlockCommerce will provide for you:
- Contract: A smart library contract consists of a contract that creates, stores the NFT and a contract that serves its role as a marketplace for selling and exchanging NFTs. These contracts can be reused, secured and stored on blockchain, and are written by Solidity. Besides, all the functions are authorized according to the account's role. 
- Upgradable contract: A set of contract and tool is used for creating and managing contracts, it allows for the separation of upgradeable contracts on Ethereum.
- Lazy minting: Advanced feature, this helps the seller not to pay any fee from the time a product is created to the time it is sold. The fee in the end will be paid by the end user.
- Authorization: Advanced feature, this helps both the seller and buyer can controll the contract by themselves and execute it as they wished, instead of the inherent automatic execution of the contract.

<!-- Example -->
## Example
These are some code snippets to help you have a better understand what block-commerce-contract can do.
- Generate a NFT with the recipient's address _to be obtained from the _hash of the artwork
```
createNewNFT(_to, string _hash)
```
- Reset the owner rights for a _to address with the _tokenId token you want to transfer, this function is only called by the owner of _tokenId.
```
setOwnerToTokenId(_to, _tokenId)
```
- Create a new product for selling with with hashed information (_hashInfo), hashed image (_hashImg), and the desired price (_price) for this product
```
createNewProduct(_hashInfo, _hashImg,  _price)
```
- Buy the product with ETH cryptocurrency
```
buyWithETH(_tokenId)
```
- Buy the product with dollar currency
```
buyWithCurrency(_tokenId, transactionId)
```
- Create an offer for a product has id (_tokenId), with quantity of _amount, token ERC20 (_token20) as you wish, and the desired price (_price) for this product
```
offer(_tokenId, _amount, _token20, _timeout)
```
- Approve an offer
```
approveOffer(_tokenId, _index)
```
- Transfer owner after the offer was approved
```
Transfer(_tokenId, _oldOwner, _newOwner)
```
<!-- Usage -->
## Usage
For better understanding on how to use block-commerce-contract for an Ethereum-based marketplace web application, you can go to [this website](https://blockcommerce.herokuapp.com/products).
Some functions are currently availble:
- Create a new product.
- Create an offer.
- Approve an offer.
- Buy a product with ETH or other currency (currently Dollar).

<div align="center">
	<img src="https://i.ibb.co/6rZL0j9/Block-Commerce-Logo-homepage.png" alt="BlockCommerce Homepage" border="0">
</div>


<!-- Contributors -->
## Creators
We wish to give a big thanks to our contributors for building this project together and bringing it to life.
- [Mai Nguyen Duc Tho](https://github.com/Thomg102)
- [Tuong Thanh Long](https://github.com/longtuongthanh)
- [Nguyen Phuc Long](https://github.com/Sportaholic-21)
- [Truong Thi Y Lan](https://github.com/ylantt)
- [Phan Hoang Dung](https://github.com/PhanHoangDung)

<!-- LICENSE -->
## License
Distributed under MIT license. See `LICENSE.md` for more infomation.
