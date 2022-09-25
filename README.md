# Decyd.io

Decyd.io is a blockchain-based voting system, with zero-knowledge proof voter verification. It empowers decision-making through leveraging digitized, decentralized, public ledger. In its current iteration, it is a functional voting system with real-time addition the blockchain for an initial group of polls.


## Approach

- Decyd.io is a blockchain-based voting system, with zero-knowledge proof voter verification. It empowers decision-making through leveraging digitized, decentralized, public ledger. In its current iteration, it is a functional voting system with real-time addition the blockchain for an initial group of polls.
- Considering the challenges with current voting systems—prone to tampering, fraudulent voting, and inconsistent reporting; blockchain provides a powerful solution through digitized, decentralized, public ledger and paves a way to an empowered form of making group choices—crowd-deciding.
- Database is entirely based on blockchain, and the back-end is in fact real. Every time a vote is submitted, it is written and can never be changed. I use the LotionJS wrapper to write to Tendermint, which helps keep state machines & nodes in sync. For the web-app we use express & React with the Grommet.IO component library. All designs were done with sketch using the Grommet.IO pack.
- In the future, I also look forward to measuring the impact that truly democratized, decentralized voting has on transparency and accountability, both within small groups and to the system as a whole. I have created some interesting feedback loops through the surveys and functional poll, including connecting with individuals actually working on creating voting systems to increase transparency in countries where this can be an issue.

## Features
- Voters vote with confidence
- 100% Secure backed by Blockchain
- Anonymous, immutable, can't be rigged
- Openn source, anyone can edit the ballot
- Real-Time tracking
- Cost-effective
- ![features](https://user-images.githubusercontent.com/93969295/192134615-ec4aab71-7bee-471e-a4d4-f3b4f3addebd.png)


## Video Demonstration

https://user-images.githubusercontent.com/93969295/192134599-e2bd7ad8-e695-4a10-878e-f45468bf99db.mp4

## How to test-run

To run this application, execute the following commands:

  1. Install NPM modules

    ```
    $ npm install (or yarn install)
    ```

  2. Start the back-end server:

    ```
    $ npm run dev-server
    ```

  3. Start the front-end dev server:

    ```
    $ npm run dev
    ```

  4. Create the app distribution to be used by a back-end server

    ```
    $ NODE_ENV=production grommet pack
    ```

  5. Start the server in production mode:

    ```
    $ npm start
    ```

  6. Test and run linters:

    ```
    $ npm test
    ```
    
## Future work and enhancements
- More R&D effort on wallet which securely saves voter's confidential data (e.g. birthdate, residential address, ethnic group, political party affiliation) and ZK-proof scheme.
- Scale the blockchain, make it able to have throughput of 2000 TPS.
- Design a more economic incentive mechanism to better secure the system. The voting system faces various attacks: sybil attack, DDoS, 51% attack, fake/double voting conducted by foreign states, political activist groups and individuals.
1. Sybil attack, fake/double voting problems can be prevented by the underlying blockchain.
2. DDoS requires infrastructure protection and local node failover.
3. To tackle the 51% attack challenge, I believe the mining nodes plays an essential role and must be prequified to prevent foreign states' influence to the voting process. I plan to adopt a PoS (proof-of-stake) mechanism for relevant citizens become the mining node or elect their delegate monitor the election on their behalf. I called it "citizen watch". With this design, 51% attacks no longer makes sense.
- In the future, I also look forward to measuring the impact that truly democratized, decentralized voting has on transparency and accountability, both within small groups and to the system as a whole. I have created some interesting feedback loops through the surveys and functional poll, including connecting with individuals actually working on creating voting systems to increase transparency in countries where this can be an issue.

## References
- https://core.ac.uk/download/pdf/155779036.pdf
- https://ieeexplore.ieee.org/document/8457919
- https://ethereum.org/en/developers/docs/
- https://github.com/nomic-io/lotion
-https://www.geeksforgeeks.org/decentralized-voting-system-using-blockchain/
