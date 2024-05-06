# Supply-Chain-Manager-Blockchain-React
It leverages React.js for the frontend, offering a user-friendly UI for supply chain managers to track and manage logistics, inventory, and transactions securely on a blockchain network. The platform provides transparency, immutability, and traceability of goods throughout the supply chain, enhancing efficiency and reducing fraud risks.

-> This is a decentralized application (dApp) built with React.js and integrated with blockchain technology. It facilitates a supply chain process involving sellers, buyers, and couriers, with three key statuses: "created," "paid," and "delivered." Sellers list products with names and costs in SepoliaETH, which are then created as orders with a "created" status.
-> Buyers can purchase products by paying the price plus gas fees through MetaMask, providing delivery addresses. The orders are updated to "payed" status. 
-> Couriers view paid products with addresses and mark them as delivered, triggering the "releasePayment" event to transfer money to the seller. The dApp enforces strict access control, allowing sellers ,buyers and couriers to access ONLY their respective dashboard, ensuring confidentiality and security in the supply chain process.
-> Solidity contract is deployed using REMIX

NOTE:
#### 1: The seller account & courier account is hardcoded into solidity contract. Any new account is Logged in as buyer.
#### 2: Since 10 Sepolia ETH is a large amt , in our project we have transferred amt divided by 10^5 to contract(contract balance) and that is the amt that releaed to seller on release payment

## All Orders
![image](https://github.com/ViditaShetty/Supply-Chain-Manager-Blockchain-React/assets/96463276/4157142d-65a9-4c95-8207-e61dc2d5ef1e)

## Seller DashBoard
![image](https://github.com/ViditaShetty/Supply-Chain-Manager-Blockchain-React/assets/96463276/6a755f98-0f0c-41cd-91d9-d080fb4b2895)
![image](https://github.com/ViditaShetty/Supply-Chain-Manager-Blockchain-React/assets/96463276/5ef8dd6a-0f12-4ed6-b38e-9d8cdb8f5063)
### Creating New Listing
![image](https://github.com/ViditaShetty/Supply-Chain-Manager-Blockchain-React/assets/96463276/083fa63d-379f-4efc-8e6b-1452fa486bf0)
![image](https://github.com/ViditaShetty/Supply-Chain-Manager-Blockchain-React/assets/96463276/dcce7d1a-5a74-40f8-9dfa-46ade7de50d0)

## Guarded UI (Seller cannot access Buyer or Courier DashBoards)
![image](https://github.com/ViditaShetty/Supply-Chain-Manager-Blockchain-React/assets/96463276/40837bf7-9c20-4d26-8091-06a1b43fe4a5)

## Buyer DashBoard
![image](https://github.com/ViditaShetty/Supply-Chain-Manager-Blockchain-React/assets/96463276/b07e13b2-0477-484b-a6a1-ae2ffd6c4b75)
### Buying a prooduct
![image](https://github.com/ViditaShetty/Supply-Chain-Manager-Blockchain-React/assets/96463276/c291950f-36ee-4855-9f37-59601980f00c)

## Courier DashBoard
![Screenshot 2024-05-06 134520](https://github.com/ViditaShetty/Supply-Chain-Manager-Blockchain-React/assets/96463276/4d15730c-ac50-4a77-952c-b800e3e38640)
![Screenshot 2024-05-06 134950](https://github.com/ViditaShetty/Supply-Chain-Manager-Blockchain-React/assets/96463276/2ff39457-580f-4c64-87b7-b8a6bfa2a2f7)
![Screenshot 2024-05-06 135027](https://github.com/ViditaShetty/Supply-Chain-Manager-Blockchain-React/assets/96463276/92a73a26-9d3f-40db-8b52-a624363ebc6a)
### Releasing Payment to seller
![Screenshot 2024-05-06 135101](https://github.com/ViditaShetty/Supply-Chain-Manager-Blockchain-React/assets/96463276/f4c750ae-75ae-45b6-9e27-046a1dc0aa18)
![Screenshot 2024-05-06 135134](https://github.com/ViditaShetty/Supply-Chain-Manager-Blockchain-React/assets/96463276/1d66adcd-25fa-4e4f-9333-1b2f76922c5d)


## Etherscan Sepolia Testnet
![Screenshot 2024-05-06 140303](https://github.com/ViditaShetty/Supply-Chain-Manager-Blockchain-React/assets/96463276/70f52ed9-e5d6-4693-9a35-0b0b09f8392d)
