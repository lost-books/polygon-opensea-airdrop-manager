# AIRLIFT: A Polygon OpenSea Airdrop Manager

## Summary

**AIRLIFT is a simple specification for a utility to manage bulk Polygon NFT transfers (airdrops) using the OpenSea API.**

## Problem Statement

OpenSea's support for the Polygon blockchain is enabling content creators to mint and transfer Polygon-based NFTs at little or no cost. However, for managing airdrops and other bulk NFT transfers, OpenSea's existing manual tooling is tedious and error-prone. 

AIRLIFT seeks to use OpenSea's API to create a better user experience for NFT airdrop managers working with Polygon on OpenSea.

## User Stories

As a user of AIRLIFT (who is also an OpenSea user), I can do the following:

**Account**

- Connect a wallet to AIRLIFT that I also connected to OpenSea, so that I can be authenticated as a user.
- Export my account data
- Delete my account data

**Gallery**

- View my Polygon-enabled OpenSea collections and NFTs in a gallery or list in AIRLIFT

**Transfers**

- Choose one or several of my NFTs from my gallery to include in an individual or bulk transfer
- Optionally paste in the URL of one or multiple Polygon NFTs I own that I want to transfer (as alternative to picking from gallery)
- Define a quantity of how many of each included NFT(s) to include in the transfer
- Input manually one or multiple recipient wallet addresses into a form field (using comma or spaces delimited wallet addresses) at time of transfer
- Upload a CSV file of recipient wallet addresses (at time of transfer)
- Automatically check if recipient wallet(s) already own(s) the NFT to be transferred, and notify user with choice to remove or proceed if they do
- Transfer one or multiple NFTs to one or multiple recipient wallet addresses

**Error handling**

- Receive meaningful error messages when transfers fail (e.g., what the specific error was, which wallets failed)
- Enable automatic retries when transfers fail, until they go through successfully

**Address book**

- Maintain an address book of recipient wallet addresses
- Input manually one or multiple recipient wallet addresses into address book (using comma or spaces delimited wallet addresses)
- Upload a CSV file of recipient wallet addresses to address book
- Delete one or multiple wallet addresses
- Create, assign, or remove groups of wallet addresses with a custom name
- Add a custom note to wallet addresses
- Add origin field where I received this wallet address initially 
- View a log of which NFTs I sent to a given wallet address and when
- Search for wallet addresses in my address book which already own a given NFT (e.g., search by NFT URL)

