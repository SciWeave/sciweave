# SciWeave Protocol   

SciWeave is a modular stack for architecting DeSci DAOs and a base layer of DAOs, researchers, and investors.   

![Sciweave](https://github.com/SciWeave/sciweave/assets/44027725/3bf141f2-12bb-4325-9fc1-6ab9642cef2a)

DAO members contribute research papers to the DAO, which are encrypted and uploaded to Filecoin via the gateway. A token is attached to each upload, and other parties can buy access to the research from the DAO. Then upon successful payment, they get a token, which they must present to the gateway to assert that they have the right to get the research. The DAO then unlocks it.   

The smart contracts also contain options for funding research via the DAO. Anyone can contribute to any supported token. Investors can later on vote on the research and decide if it was successful.  

A collection of smart contracts and a frontend for scientists to create DAOs to pool funding together and publish research.    

A collection of smart contracts and a frontend for scientists to create DAOs to pool funding together and publish research.
Scientists can use this protocol to create daos, invite scientists as members, create funding proposals that investors can invest in to fund research, and they can publish research that is accessible through Filecoin.    

The project uses Filecoin and web3.storage to publish research to Filecoin.   

The smart contracts are deployed on multiple chains, including Filecoin Calibration testnet, Polygon zkEVM testnet, Mantle testnet, ZetaChain, Celo.   

The project uses The Graph on the front end to index and query the SciWeave smart contract.   

This monorepo contains three subrepos:   
- ```sciweave-contracts```: contains the smart contracts and the addresses of the deployments on various blockchains   
- ```sciweave-thegraph```: the code for using The Graph for all blockchains   
- ```sciweave-ui```: the code for the Vue.js frontend for the SciWeave Protocol
