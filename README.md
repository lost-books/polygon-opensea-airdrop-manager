# AIRLIFT: A Polygon OpenSea Airdrop Manager

## Summary

**AIRLIFT is a simple specification for a utility to manage bulk Polygon NFT transfers (airdrops) using the OpenSea API.**

## Problem Statement

OpenSea's support for the Polygon blockchain is enabling content creators to mint and transfer Polygon-based NFTs at little or no cost. However, for managing airdrops and other bulk NFT transfers, OpenSea's existing manual tooling is tedious and error-prone. 

AIRLIFT seeks to use OpenSea's API to create a better user experience for NFT airdrop managers working with Polygon on OpenSea.

## User Stories

As a user of AIRLIFT (who is also an OpenSea user), I can do the following:

- Connect a wallet to AIRLIFT that I also connected to OpenSea, so that I can be authenticated as a user.
- View my Polygon-enabled OpenSea collections and NFTs in a gallery in AIRLIFT
- Transfer one or multiple NFTs to one or multiple recipient wallet addresses
  - Choose one or several of my NFTs from my gallery to include in an individual or bulk transfer
  - Input manually one or multiple recipient wallet addresses into a form field (using comma or spaces delimited wallet addresses)
  - Upload a CSV file of recipient wallet addresses
