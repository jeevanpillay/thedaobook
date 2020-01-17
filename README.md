# thedaobook

## DISCLAIMER: CONCEPTUAL PHASE

The following document outlines the structure of thedaobook. This is no means a guide on how the final product will turn out.

---

# Decentralised Autonomous Organisations

## Definition

A Decentralised Autonomous Organisations; offen referred to as "DAO", is a collection of autonomous agents acting independently in a decentralised network that is governed by smart contracts. These smart contracts enforce strict business policies and rules by implementing logic that is cryptographically secure. Essentially, the system ensures that each entity in the system is allocated rights in a fair and distributed manner. The source code governing the DAO is also completely open source to encourage complete transparency in a publicly auditable manner.

---

## Hierarchically Stake Governed DAO (hsDAO)

### Definition

A Hierarchically Stake Governed Decentralised Autonomous Organisation is a self governing organisation that consist of several committee members and the community. It incorporates a very basic hierarchial structure, whereby, there is a set of committee members governing the DAO. This DAO structure mimics existing company structures, whereby, there is there is a central board that governs the day to day operations of the entity. This DAO implementation extends on the concept of voting rights by ensuring that amount of stake (in this case the native cryptocurrency, eg. ETH) is proportional to the voting rights in the entity.

The set of committee members, which are also commonly known as `Board of Executive`'s maintains all rights to the DAO's fund.

### Implementation

The implementation of this contract is acts as the base layer to provide most of the functionality that exist in a DAO. It consist of very basic functions and roles such as the election of `BoE`'s.

1. The system should be able to allow developers to create a DAO that acts as an open source project with a set of participants acting as the committee members (Board of Executives) of the project.
2. These set of committee members are the main board members of the DAO.
3. The members of the DAO are able to elect the board members at intervals set at the beginning of the DAO Genesis Contract.
4. The DAO Genesis Contract acts the initiator contract that creates the DAO by accepting a set of committee members (using public key cryptographic scheme) which end up representing the number of the committee members and initial committee members, election intervals, etc.
5. Each member of the DAO Genesis Contract signs the contract to enforce the start of the DAO. This function named `Start` act as the first term of the DAO.
6. During one term of the DAO, there will be several round of project proposals and nominations that the community collective decides to implement.
7. Project proposals can occur in two ways:
   - Proposal by Board of Executives

### Additional Details

This contract should also be extendable so that entities can incorporate additional functionality such as `CEO`'s, `CTO`'s, etc.

---

## Flat Stake Governed DAO (fsDAO)

### Definition

A Flat Stake Governed Decentralised Autonomous Organisation is a self governing organisation that does not maintain a set of committee members by enforcing a flat structure. Each individual in the fsDAO will acts as an independent entity whose voting rights is directly pegged to the stake in the DAO.

---

## Basic DAO (DAO)

### Definition

---

### Helpers and Questions

#### Current DAO Implementation

The DAO maintains a collection of `Contractor`'s that have the ability to submit `Proposal`'s for the development of a product or service. Then, a group of signatories called `Curators` validate the contractors proposals by collectively deciding to authorize the `Contractor` to receive money. At any time, with majority vote, any `Curator` can be kicked out the DAO.

[GitHub](https://github.com/lpfloyd/DAO?organization=lpfloyd&organization=lpfloyd)

---
