# QuantumGoldDAO

## Requirements
The contract contains the following functional requirements:

* Only QTG token holder can vote
* ChangeVotingRules (onlyOwner)
* newProposal/InEther
* checkProposalCode
* Vote
* executeProposal (onlyOwner)
* standard ownable function

You could reference the source code comment for more information.

## Suggested Settings for implementation

* 1 QTG: 1 Vote
* Initial Vote Settings: 
    * Support 50%
    * Min Quorum: 2.5%
    * Vote Duration: 1 week
    * Max Limit: When the vote token reached 20% of the QTG total supply, the voting will be closed outomatically
* The contract address should be redirect by ethereum naming service for upgrading the contract.
