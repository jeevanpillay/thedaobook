# thedaobook

## DISCLAIMER: CONCEPTUAL PHASE

The following document outlines the structure of thedaobook. This is no means a guide on how the final product will turn out.

---

## Helpers

---

# Decentralised Autonomous Organisations

## Project Information

What it will not do?

---

## Definition

A Decentralised Autonomous Organisations; offen referred to as "DAO", is a collection of autonomous agents acting independently in a decentralised network that is governed by smart contracts. These smart contracts enforce strict business policies and rules by implementing logic that is cryptographically secure. Essentially, the system ensures that each entity in the system is allocated rights in a fair and distributed manner. The source code governing the DAO is also completely open source to encourage complete transparency in a publicly auditable manner.

## Hierarchial Decentralised Autonomous Organisations

A Hierarchial Decentralised Autonomous Organisation is a self governing organisation that consist of several committee members and the community.

1. The system should be able to allow developers to create a DAO that acts as an open source project with a set of participants acting as the committee members (Board of Executives) of the project.
2. These set of committee members are the main board members of the DAO.
3. The members of the DAO are able to elect the board members at intervals set at the beginning of the DAO Genesis Contract.
4. The DAO Genesis Contract acts the initiator contract that creates the DAO by accepting a set of committee members (using public key cryptographic scheme) which end up representing the number of the committee members and initial committee members, election intervals, etc.
5. Each member of the DAO Genesis Contract signs the contract to enforce the start of the DAO. This function named `Start` act as the first term of the DAO.
6. During one term of the DAO, there will be several round of project proposals and nominations that the community collective decides to implement.
7. Project proposals can occur in two ways:
   - Proposal by Board of Executives

## DAO Implementation

The DAO maintains a collection of `Contractor`'s that have the ability to submit `Proposal`'s for the development of a product or service. Then, a group of signatories called `Curators` validate the contractors proposals by collectively deciding to authorize the `Contractor` to receive money. At any time, with majority vote, any `Curator` can be kicked out the DAO.

---

## Questions?

1. Will Thorchain support smart contracts?
