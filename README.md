# 🌟 FNCYScan

FNCYScan is a platform that allows users to track and manage their NFTs. It is an open-source project that provides a simple and intuitive interface for users to easily view and manage their NFTs.

## 📝 PR Template

If you wish to add your NFT into FNCYScan, please follow the following PR template:

```json
{
    "id": integer,
    "name": text,
    "symbol": text,
    "description": text,
    "address": address hash,
    "image": link to your NFT image,
    "singleNftDomain": API domain where we can get your single NFT information
}
```

## 🎁 Example

Here is an example of how to submit a PR for adding your NFT to FNCYScan:

```json
[...{
  "id": 1,
  "name": "IUFC NFT",
  "symbol": "IUFC",
  "description": "NFT series for K-Leagues's Incheon United F.C. Special benefits are provided for the IUFC fans.",
  "address": "0x5f29aa5c4125038819dcde1405Ca1b602306d4E9",
  "image": "https://static.cube.store/markets/incheon-united/thumbnail.png",
  "singleNftDomain": "https://api.fncy.world/tankers/markets/incheon-united/nfts/0x5f29aa5c4125038819dcde1405ca1b602306d4e9"
}...]
```

Please provide all the requested info in the PR.

