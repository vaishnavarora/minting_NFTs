/*
Assessment Requirements
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs. 
   The metadata values will be passed to the function as parameters. When the NFT is ready, 
   you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created
*/

// Solution --------->

let total_NFTs = 0;
function mintNFT(name, des, age){
    const nftMetaData = {
        name: name,
        des: des,
        age: age
    };
    total_NFTs++;

    nfts.push(nftMetaData);

    return nftMetaData;
}
function list_NFTs(){
    for (let i = 0; i < nfts.length; i++){
        const nft = nfts[i];
        console.log("Name: " + nft.name);
        console.log("Description: " + nft.des);
        console.log("Age: " + nft.age);
    }
}
function getTotalSupply(){
    return total_NFTs;
}
const nfts = []

const nft1 = mintNFT("NFT 1", "My 1st NFT", "20");
const nft2 = mintNFT("NFT 2", "My 2nd NFT", "22");
const nft3 = mintNFT("NFT 3", "My 3rd NFT", "26");

list_NFTs();

const total_supply = getTotalSupply();
console.log("Total NFT's: " + total_supply);
