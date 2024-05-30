Explaination of code:

1) const myNFTS = [];
This line initializes an empty array named myNFTS which will be used to store the minted NFTs.

2)function mintNFT(user_name, user_age, profession, stipend) {
    const NFT = {
        name: user_name,
        age: user_age,
        profession: profession,
        stipend: stipend
    };
    myNFTS.push(NFT);
    console.log("Minted: " + user_name);
}

This function takes four parameters: user_name, user_age, profession, and stipend, which represent the metadata for the NFT.
It creates an object NFT containing the metadata provided and pushes it into the myNFTS array.
Finally, it logs a message confirming the minting of the NFT with the provided user name.

3)function listNFTs() {
    for (let i = 0; i < myNFTS.length; i++) {
        console.log(myNFTS[i]);
    }
}
This function iterates through the myNFTS array using a for loop and logs each NFT's metadata to the console.

4)function getTotalSupply() {
    return myNFTS.length;
}
This function simply returns the length of the myNFTS array, which represents the total number of minted NFTs.

5)mintNFT("PRATEEK", "20", "STUDENT", "20000");
mintNFT("AYUSH", "20", "STUDENT", "18000");
listNFTs();
const totalSupply = getTotalSupply();
console.log("Total NFTs minted:", totalSupply);
This part of the code demonstrates the usage of the defined functions. Two NFTs are minted with different metadata, then all minted NFTs are listed, and finally, the total supply of minted NFTs is printed to the console.

THANK YOU!



