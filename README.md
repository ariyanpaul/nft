# NFT minting 
## Description:
This is a simple JavaScript project that demonstrates how NFTs can be created, stored, listed, and counted using basic programming concepts.

## The project uses:
1. Variables
2. Arrays
3. Objects
4. Functions
5. Loops
6. Console output

## Each NFT contains basic metadata such as:
1. Name
2. Description
3. Image

## Code Overview
numNFTs

let numNFTs = 0;

>This variable keeps track of the total number of NFTs minted.

nfts

const nfts = [];

>This array stores all the NFT objects.

mintNFT()
function mintNFT(name, description, image)

>This function creates a new NFT object using the given name, description, and image.

>After creating the NFT, it adds the NFT to the nfts array and increases the total NFT count.

listNFTs()

function listNFTs()

>This function loops through the NFT array and prints each NFT’s metadata to the console.

getTotalSupply()
function getTotalSupply()

>This function returns the total number of NFTs that have been minted.

### Example NFTs

The following NFTs are minted in the program:

mintNFT("Bird", "blueFeather", "image1.jpg");

mintNFT("harambe", "gorilla", "image2.jpg");

**Expected Output**

Name: Bird

Description: blueFeather

Image: image1.jpg

Name: harambe

Description: gorilla

Image: image2.jpg

Total Supply: 2

## How to Run
Make sure Node.js is installed on the system.

Save the JavaScript code in a file, for example:

index.js
Open the terminal in the project folder.

Run the file using:

node index.js

Project Purpose

The purpose of this project is to understand the basic logic behind minting NFTs by creating NFT objects and storing their metadata in an array.

This is a beginner-friendly project for learning JavaScript fundamentals.
