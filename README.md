# Cloud Drive 3.0

A Decentralized Cloud Platform with Sharing feature

# Basic Requirement
1. Node should be installed in system
2. Metamask should be installed in browser

# Steps
1. Clone the repository
```
git clone https://github.com/shubhvishwas/Cloud-Drive-3.0.git
```
2. install modules for create-react-app
```
npm install create-react-app
```
3. Create client folder
```
npx create-react-app client
```
4. Go to the client folder and install axios
```
cd client
npm install axios
cd ..
```
5. Replace the src folder in client with src folder present in the folder

# Steps to start the Project

1. On a new terminal open hardhat. A blockchain will be created with 10 dummy accounts. copy private keys of 2-3 accounts and load them in your metamask
```
npx hardhat node
```
2. Type the following command on a new terminal
```
npx hardhat run --network localhost scripts/deploy.js
```
3. Finally type the command;
```
cd client
npm start
```
Project will be diplayed on the Local host 3000
