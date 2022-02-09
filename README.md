**To use this code:**

- Clone this repo or download the latest release zip file.
- Unzip, if needed, and open the folder in VS Code.
- From the terminal type:
  - `npm install`
- Copy your image layers into the `layers` folder.
- Use the `src/config.js` file to set up your layers and NFT information.
- To Generate Layers:
  - `npm run generate`
- To Upload Layers:
  - `node utils/nftport/uploadFiles.js` **Generate-Files**
  - `node utils/nftport/uploadMetas.js` **--optional--**
  - `node utils/nftport/mint.js` **Mint-Upload**

- All in One:
 `npm run generate && node utils/nftport/uploadFiles.js && node utils/nftport/uploadMetas.js && node utils/nftport/mint.js`

**Varun Jain Stickers Certificate:** 
{
  "response": "OK",
  "chain": "rinkeby",
  "transaction_hash": "0x0ff76a02a13341def89be72b326d0af38684367f8e98a4b6bfc46e6f01b6b9f9",
  "transaction_external_url": "https://rinkeby.etherscan.io/tx/0x0ff76a02a13341def89be72b326d0af38684367f8e98a4b6bfc46e6f01b6b9f9",
  "owner_address": "0x4Cd16BEdb72ad2DB27F293C4839569528DaB1659",
  "name": "Varun Jain",
  "symbol": "M"
}

{
  "response": "OK",
  "chain": "polygon",
  "transaction_hash": "0xf607204b03b5cb202da59e9306cabbfec680c8ceadf8ceac77b6de1c3b7e701e",
  "transaction_external_url": "https://polygonscan.com/tx/0xf607204b03b5cb202da59e9306cabbfec680c8ceadf8ceac77b6de1c3b7e701e",
  "owner_address": "0x4Cd16BEdb72ad2DB27F293C4839569528DaB1659",
  "name": "VarunJain",
  "symbol": "ME"
}

{
  "response": "OK",
  "chain": "polygon",
  "transaction_hash": "0x1a038105f4db33630d9e091bc53ee0247659d8d6b508cb0673052b1284c75484",
  "transaction_external_url": "https://polygonscan.com/tx/0x1a038105f4db33630d9e091bc53ee0247659d8d6b508cb0673052b1284c75484",
  "owner_address": "0x4Cd16BEdb72ad2DB27F293C4839569528DaB1659",
  "name": "Varun Jain",
  "symbol": "S"
}

{
  "response": "OK",
  "chain": "polygon",
  "transaction_hash": "0x492568325f7f9f15f9af514e55f93d5e73fb4dbecc335fb27afc10aa8a6026e4",
  "transaction_external_url": "https://polygonscan.com/tx/0x492568325f7f9f15f9af514e55f93d5e73fb4dbecc335fb27afc10aa8a6026e4",
  "owner_address": "0x4Cd16BEdb72ad2DB27F293C4839569528DaB1659",
  "name": "Varun Jain",
  "symbol": "C"
}