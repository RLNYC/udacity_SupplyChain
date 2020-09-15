

## Project Write-up
1. UML Diagrams

     ![Activity Diagram](https://raw.githubusercontent.com/RLNYC/udacity_StarNotary/master/screenshots/passing%20test.jpg)

     ![State Diagram](https://raw.githubusercontent.com/RLNYC/udacity_StarNotary/master/screenshots/passing%20test.jpg)

     ![Sequence Diagram](https://raw.githubusercontent.com/RLNYC/udacity_StarNotary/master/screenshots/passing%20test.jpg)

     ![Data Model Diagram](https://raw.githubusercontent.com/RLNYC/udacity_StarNotary/master/screenshots/passing%20test.jpg)

2. Libraries
    - A library is used for managing define access and role of farmer, distributor, retailer, and consumer. Role contracts for different parties are similar and requires similar logics. 
      Deploying a common code by creating a library reduces the gas cost. 

3. IPFS
   - IPFS is not used to store any files, but it could be potentially used for farmer uploading pictures of their coffee harvest.  

## Rinkeby Testnet Deploy/Contract Info
- Contract address on Rinkeby Network: 0xe3A6Db508C51eC7d09574115be521eAABe9776C0
- Etherscan link: https://rinkeby.etherscan.io/address/0xe3a6db508c51ec7d09574115be521eaabe9776c0

## Truffel Test Result

    ![Passing Tests](https://raw.githubusercontent.com/RLNYC/udacity_StarNotary/master/screenshots/passing%20test.jpg)

## Front end screen shot
tes
    ![Passing Tests](https://raw.githubusercontent.com/RLNYC/udacity_StarNotary/master/screenshots/passing%20test.jpg)

## Instructions
   
   Backend: start up local blcokchain
   - In the root folder directory, run "truffle migrate --reset"

   Frontend: start up frontend interface
   - In a separate terminal window, run "npm run dev"

