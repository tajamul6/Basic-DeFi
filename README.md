<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>


<!-- PROJECT LOGO -->
<br />


<h3 align="center">Basic DeFi App</h3>

  <p align="center">
    An app that allows the depositing of ETH, allows the borrowing DAI and also repay the loaned DAI (made whilst following the fcc tutorial)
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


This project was built while following Patrick at freecodecamp and is a basic version of a DeFi Application
It performs the following actions:
1. Deposit collateral || ETH/WETH
2. Borrow another asset: DAI
3. Repay the DAI
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
### Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - You'll know you did it right if you can run `git --version` and you see a response like `git version x.x.x`
- [Nodejs](https://nodejs.org/en/)
  - You'll know you've installed nodejs right if you can run:
    - `node --version` and get an ouput like: `vx.x.x`
- [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/) instead of `npm`
  - You'll know you've installed yarn right if you can run:
    - `yarn --version` and get an output like:`x.x.x`
    - You might need to install it with npm


### Installation

 Clone the repo
   ```sh
   git clone https://github.com/tajamul6/Basic-DeFi.git
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

This repo requires a mainnet rpc provider. Through `forking` the mainnet, we will pretend as if we are interacting with mainnet contracts. 

All you'll need, is to set a `MAINNET_RPC_URL` environment variable in a `.env` file that you create. You can get setup with one for free from [Alchemy](https://alchemy.com/?a=673c802981)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

Run:

```
yarn hardhat run scripts/aaveBorrow.js
```

# Running on a testnet or mainnet
You'll want to set your `GOERLI_RPC_URL` and `PRIVATE_KEY` as environment variables. You can add them to a `.env` file, similar to what you see in `.env.example`.

- `PRIVATE_KEY`: The private key of your account (like from [metamask](https://metamask.io/)). **NOTE:** FOR DEVELOPMENT, PLEASE USE A KEY THAT DOESN'T HAVE ANY REAL FUNDS ASSOCIATED WITH IT.
  - You can [learn how to export it here](https://metamask.zendesk.com/hc/en-us/articles/360015289632-How-to-Export-an-Account-Private-Key).
- `GOERLI_RPC_URL`: This is url of the goerli testnet node you're working with. You can get setup with one for free from [Alchemy](https://alchemy.com/?a=673c802981)

2. Get testnet ETH

Head over to [faucets.chain.link](https://faucets.chain.link/) and get some tesnet ETH. You should see the ETH show up in your metamask.

3. Run

```
yarn hardhat run scripts/aaveBorrow.js --network goerli
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- CONTACT -->
## Contact

Tajammal Ahmed - [@tajamul676](https://twitter.com/tajamul676) - tajamul676@gmail.com

Project Link: [https://github.com/tajamul6/Basic-DeFi](https://github.com/tajamul6/Basic-DeFi)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Made with the help of Patrick Collins tutorial of freecode camp found here:
[https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=69421s](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=69421s)

<p align="right">(<a href="#readme-top">back to top</a>)</p>