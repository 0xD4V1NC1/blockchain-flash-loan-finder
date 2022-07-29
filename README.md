# flash-loan-finder
Steps:
1. Clone Repo

2. run npm install or yarn install

3. create a .env file

4. go to infura.io and sign up for the free plan. Create a project/node and copy the Project ID to your .env file (see .env.example for reference)

5. edit index.js with your desired start block. You can google the most recent block of the blockchain you are working with and decide a reasonable amount of blocks to go back. It is also important to note you are not limited to the AAVE lending pool. You can google other lend pool addresses from AAVE, Cream Finance, or other lending protocols that provide flash loans.

6. run the command node index.js

Main branch - Ethereum Blockchain
Polygon branch - Polygon Blockchain (currently being worked on)
Avalanche branch - Avalanche Blockchain (currently being worked on)
Fantom branch - Fantom Opera Blockchain (currently being worked on)
BSC branch - Binance Smart Chain (currently being worked on)