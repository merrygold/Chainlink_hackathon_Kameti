# Social Impact using Chainlink Services & Polygon ID

## Solidity code inside contracts

## Run locally on Remix (Polygon Mumbai Testnet) with Subscription Id: 2651


# Motivation 

We wanted to build something in the Social Impact category. We interviewd some locals to get a better idea of pain points that "Blockchain tech, Chainlink & Polygon" can solve while being user-friendly.

# What is (Decentralized) Kameti?
We came across a problem thats a very common cause of People losing their life-savings to fraudsters and lack of paperwork & trust, knows as KAMETI's in Asia or more generally ROSCA(Rotating Savings And Credit Association). 

In simple words, a group of people agree to save collectively and an organizer chooses a person (in a so-called random process writing names on paper pieces and picking one from them) every month who access the whole pool for that month. So, 5 people with 100$ monthly payment means 500$ pool every month. So, everyone gets access to a big amount randomly.

There are other types of these kind's of savings that our dapp's code can support with just a little bit changing for each.

# Problems:
We pin-pointed some of the most crucial problems in this process that everyone involved face

- Trust Issues (more specifically organizer favors people in the selection process)   => Solved using Chainlink VRF

- Identity Issues (in case someone defaults, we don't have their right ID)     => Solved using Polygon ID

- Transaction Records => Solved using IPFS storage & Polygon's native ledger (no one can manipulate or delete)

# Technologies:
# Using Chainlink (Eliminate Trust Issues)

=> Getting a random number from chainlink VRF to select the winner

# Using PolygonID (Eliminate Identity issues)

- We can't upload People's ID directly on the chain, thanksfully Polygon ID allows us to issue zk-claims (by getting their ID details off-chain and saving cryptographically) to people that they can later use for authentication on smart contracts & our other services.

# Using Polygon (Eliminate Transaction Records issue)

- Uploading all the event data & Transaction details on the Polygon Network. We get an immutable ledger that no one can manipulate or delete like physical ledgers.
