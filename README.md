# Commit-by-commit breakdown of "Design a Blockchain & Cryptocurrency | Full-Stack"

This is a commit-by-commit breakdown of "Design a Blockchain & Cryptocurrency | Full-Stack".

## References:
## Commits
- [Section 2: Blocks | The Blockchain Backend]
- [Section 3: The Chain | the Blockchain Backend]
- [Section 4: Proof of Work | the Blockchain Backend]
- [Section 5: API and Network | the Blockchain Backend]
- [Section 6: Wallets, Keys, and Transactions | the Blockchain Backend]
- [Section 7: Transaction Pool | The Blockchain and Cryptocurrency Backend]
- [Section 8: Mine Transactions | The Blockchain and Cryptocurrency Backend]
- [Section 10: The Frontend Blockchain]
- [Section 11: The Frontend Cryptocurrency]
- [Section 12: Deploying to Production and Full-Stack Improvements]

#### Section 2: Blocks | The Blockchain Backend
* [Set Up the Blockchain Application]
* [Create the Block Class]
* [Create the Block Class | TDD Style]
* [The Genesis Block | Tests]
* [The Genesis Block | Code]
* [Mine Blocks]
* [Crypto Hash and SHA-256]
* [Hash in MineBlock]

#### Section 3: The Chain | the Blockchain Backend
* [The Blockchain Class]
* [Chain Validation | Tests]
* [Chain Validation | Code]
* [Chain Replacement]
* [Stub Console Output in Tests]

#### Section 4: Proof of Work | the Blockchain Backend
* [Difficulty and the Nonce Value | Tests]
* [Difficulty and the Nonce Value | Code]
* [Dynamic Difficulty and the Mine Rate]
* [Adjust the Difficulty in MineBlock]
* [Improve the Proof of Work System | Average Work Script]
* [Improve the Proof of Work System | Binary hashes]
* [Prevent Difficulty Jumps]

#### Section 5: API and Network | the Blockchain Backend
* [Setup Express API]
* [Post Request to Mine a Block]
* [Redis Publisher/Subscriber Class]
* [PubNub: a Non-Redis Pub/Sub Alternative]
* [Broadcast Chain]
* [Start Peers and Broadcast Chain on API Mine]
* [Sync Chain on Connect]
* [Avoid Redundant Interactions]

#### Section 6: Wallets, Keys, and Transactions | the Blockchain Backend
* [Code Organization]
* [Create and Test Wallet Class]
* [Key Pair and Public Key Addresses]
* [Sign Data and Verifying Signatures]
* [Transaction Objects and the Output Map | Tests]
* [Transaction Objects and the OutputMap | Code]
* [Transaction Inputs]
* [Cohesive Utility]
* [Validate Transaction]
* [Wallet Create Transaction]
* [Update Transactions with Multiple Outputs]
* [Improve the CryptoHash]
* [Transaction Update Edge Cases]

#### Section 7: Transaction Pool | The Blockchain and Cryptocurrency Backend
* [Create the Transaction Pool and Set Transactions]
* [API Transactions and Main Transaction Pool]
* [Handle Invalid Transactions]
* [Transaction Updates in the API]
* [Broadcast Transaction]
* [Sync Transaction Pool Map on Connect]
#### Section 8: Mine Transactions | The Blockchain and Cryptocurrency Backend
* [Transaction Miner Class]
* [Grab Valid Transactions]
* [Reward Transaction]
* [Clear Blockchain Transactions]
* [Mine Transactions Endpoint]
* [Clear Recorded Transactions on Successful Replace]
* [Calculate the Wallet Balance]
* [Calculate the Balance before each Transaction]
* [Wallet Balance from Recent Transaction]
* [Wallet-Info Request]
* [Valid Transaction Data | Tests]
* [Validate Input Balances]
* [Prevent Duplicate Transactions in Block]
* [Validate Transaction Chain]

#### Section 10: The Frontend Blockchain
* [Serve a Frontend Page]
* [Add JavaScript to the Frontend]
* [Build React into the Frontend]
* [Frontend Development Workflow]
* [App component]
* [Fetch and Display Wallet-Info]
* [Visualize the Blocks]
* [Seed the Backend with Data]
* [Stylize the Application]
* [Make a Block Component with Props]

#### Section 11: The Frontend Cryptocurrency
* [Toggle Transaction Displays]
* [Transaction Component]
* [React Router]
* [Conduct Transaction Component]
* [Post Transaction with Component]
* [Transaction Pool Component]
* [Poll the Transaction Pool]
* [Mine a Block of Transactions through the Frontend]

#### Section 12: Deploying to Production and Full-Stack Improvements
* [Configure Production Code](https://github.com/15Dkatz/cryptochain_commits/commit/e1791c5e22c04b8d2bc3d33285a0685ffb2f8e87)
* [Known Adresses | Backend](https://github.com/15Dkatz/cryptochain_commits/commit/3581f482678e0b087339e065b591b04d0ca1e3e7)
* [Known Adresses | Frontend](https://github.com/15Dkatz/cryptochain_commits/commit/4a9ef451d41cdfd2e462a151907009f0c73e3960)
* [Blocks Pagination | Backend](https://github.com/15Dkatz/cryptochain_commits/commit/c943c72972cc44e026052d3146e1044075fa176e)
* [Blocks Pagination | Frontend](https://github.com/15Dkatz/cryptochain_commits/commit/b4deaf6bb76f1058969e2cbf48d48e367f30e204)
