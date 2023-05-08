🔍 FNCYScan: A Token Tracking and Management Platform

FNCYScan is an open-source platform designed to help users track and manage their tokens, including ERC20, ERC721, and ERC1155. The platform provides a simple and intuitive interface that allows users to easily update their tokens through GitHub repo. 

## Adding Your ERC20 Token to FNCYScan

If you wish to add your ERC20 token to FNCYScan, follow the instructions below:

1. Use the following PR template:

   ```
   {
       "id": integer,
       "name": text,
       "symbol": text,
       "description": text,
       "address": address hash,
       "image": link to your token image,
   }
   ```

2. Provide all the requested information in the PR, including:

   - `id`: a unique identifier for your token
   - `name`: the name of your token
   - `symbol`: the symbol of your token
   - `description`: a brief description of your token
   - `address`: the address hash of your token
   - `image`: a link to your token image

3. Submit your PR to FNCYScan.

Here is an example of how to submit a PR for adding your ERC20 token to FNCYScan:

```
{
  "id": 2,
  "name": "Binance USD",
  "symbol": "BUSD",
  "description": "BUSD is a 1:1 USD-backed stablecoin approved by the New York State Department of Financial Services (NYDFS), issued in partnership with Paxos.",
  "address": "0x0facd73fc3e354b688323e9bcd1637d01ed94c4e",
  "image": "https://cryptologos.cc/logos/binance-usd-busd-logo.png?v=025",
}
```

## Adding Your NFT to FNCYScan

If you wish to add your NFT to FNCYScan, follow the instructions below:

1. Use the following PR template:

   ```
   {
       "id": integer,
       "name": text,
       "symbol": text,
       "description": text,
       "address": address hash,
       "image": link to your token image,
       "singleNftDomain": provide an API domain where we can get your single NFT information,
   }
   ```

2. Provide all the requested information in the PR, including:

   - `id`: a unique identifier for your NFT
   - `name`: the name of your NFT
   - `symbol`: the symbol of your NFT
   - `description`: a brief description of your NFT
   - `address`: the address hash of your NFT
   - `image`: a link to your NFT image
   - `singleNftDomain`: an API domain where FNCYScan can get your single NFT information

3. Submit your PR to FNCYScan.

Here is an example of how to submit a PR for adding your NFT to FNCYScan:

```
{
    "id": 1,
    "name": "IUFC NFT",
    "symbol": "IUFC",
    "description": "NFT series for K-Leagues's Incheon United F.C. Special benefits are provided for the IUFC fans.",
    "address": "0x5f29aa5c4125038819dcde1405Ca1b602306d4E9",
    "image": "https://static.cube.store/markets/incheon-united/thumbnail.png",
    "singleNftDomain": "https://api.fncy.world/tankers/markets/incheon-united/nfts/0x5f29aa5c4125038819dcde1405ca1b602306d4e9"
}
```

Thank you for using FNCYScan!