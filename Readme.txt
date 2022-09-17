# Electronic Voting System
A decentralized electronic voting system using blockchain which helps users to cast their votes using the web portal in an efficient and secure manner. 
This DApp aims to revolutionize how voting works, by leveraging the power of Blockchain. The blockchain technology is an emerging solution to these concerns. 
This evolving technology is immutable i.e. after a vote is casted, it cannot be undone. It is decentralized and distributed which means that there’s no central authority over the voting system. 
Due to aforementioned factors, it brings transparency in elections.

## DApp Workflow
- The voter must first login to the dapp using their mobile number via OTP confirmation & then their Aadhaar Number.
- After authentication, the voter can now begin the process of voting.
- If the voter is valid then the voting pallete will be opened with candidate names.
- Now, the voter can cast their vote by clicking on the vote button next to their preferred candidate.
- A voter can cast their vote only once. After which, the voter’s automatically logged out after giving a notification.
- Same process continues for many more voters irrespective of their voting wards.
- Vote count for each candidate is displayed on the portal, next to the candidate, when the voter logs in again after casting a vote.

## Technology Stack:
1. React.js
2. Truffle
3. Ganache
4. Metamask
5. Web3.js
6. Solidity
7. Node.js
8. Express.js

## Methodology Steps

Step 1: We have to download Truffle Framework and install it with the below command: npm install -g truffle.

Step 2: Download and install Ganache. ( https://trufflesuite.com/ganache)

Step 3: Add a new workspace on Ganache under a test name. Import the 'truffle-config' file under the "Add Project" section.

Step 4: Save the settings and launch the workspace.

Step 5: Now, add the Metamask extension to your Google Chrome. Then create an account in Metamask.  

Step 6: Choose private key by clicking on key option and create private network in meta mask by providing url http://127.0.0.1:7545.

Step 7: Import private key to connect to localhost account.

Step 8: After pasting private key, click on import and metamask will be connected to localhost test account to perform transactions.

Step 9: Inside the project directory (Voting App), run the command: npm install

Step 10: Go inside the 'ui' directory and then again run the command: npm install.

Step 11: Go back to the main project directory and then run the command: truffle migrate.

Step 12: Open Twilio (https://www.twilio.com/login) and log into the account using the credentials (Username: vanshkaushik2705@gmail.com; Password: VanshKumarKaushik). The voter has to first verify their number here, by adding their valid mobile number.

Step 13: Go inside the 'ui' directory, and start the web application by running the command: npm start.

Step 14: Go back to the main project directory and then run the command: node server.js.

Step 15: After opening the React application in your browser it will trigger Metamask to interact with your blockchain network. Then by logging into your account, your metamask will be connected to blockchain.

Step 16: Now you can test your application accordingly. Use only the numbers registered on Twilio to receive the OTP.





