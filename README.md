# crossfabric
# Overview
`crossfabric` is a blockchain based Crossplane Objects management, based on plexus with Hyperledger Fabric.
# Background
Crossplane is a framework for building cloud native control planes. These control planes sit one level above the cloud providers and allow you to customize the APIs they expose. Same as Crossplane add flexibility for manage resources, is also make control planes fragile and do not protected agains acitendal disaster. 
Based on this problem, appears necessaty of protected and transparent storage of control plane state.
# Goals
The proposal put forward by this document should:
- Consensus state mutability
- Transparent state history
- Disaster protection
- Attacks protection
# Proposal
Use Hyperlesger Fabric for store Crossplane state in blockchain and apply Crossplane object changes by Chaincode.
